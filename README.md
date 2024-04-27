# MVC-Ponderada
# Diagrama Model-View-Controller

## Análise e Definição do Escopo

<b> Principal Objetivo:</b> A aplicação web foi construída com ajuda do framework Sails.js que tem como principal objetivo estabelecer uma plataforma eficiente, na qual a interação do usuário é constituída por meio de uma interface desenvolvida com HTML, CSS e Javascript. Dessa forma, com uma interface amigável e responsiva será possível proporcionar uma experiência fluida ao usuário, permitindo uma navegação intuitiva e agradável.

&nbsp;&nbsp;&nbsp;&nbsp; Ademais, essa interface interage com uma API backend desenvolvida em Node.js, seguindo a arquitetura MVC e framework Sails.js. Nesse sentido, essa API oferece uma comunicação eficaz entre o front-end e o banco de dados PostgreSQL. Nessa lógica, utiliza-se sistema de ORM (Object-Relational Mapping) do Sails.js, na qual a aplicação consegue gerenciar e segurar as operações de acesso e manipulação dos dados armazenados no banco.

&nbsp;&nbsp;&nbsp;&nbsp; Portanto, com uma arquitetura bem definida, a aplicação web oferece não obstante de uma interface eficaz e responsiva para os usuários finais, como também uma estrutura sólida e confiável para o desenvolvimento e manutenção contínua da plataforma. Outrossim, a modularidade e extensibilidade do Sails.js permitem uma facilidade de integração de novos recursos e funcionalidades, desse modo, garante-se uma plataforma que seja possível crescer e se adaptar às constantes variações das necessidades dos usuários e do mercado.


<b> Principais Módulos, Funcionalidades e Recursos:</b> 

&nbsp;&nbsp;&nbsp;&nbsp; - Autenticação de Usuários: Registro de novos usuários; login e logout, controle de acesso às funcionalidades do site.

&nbsp;&nbsp;&nbsp;&nbsp; - Feed:
Publicação de ideias e/ou projetos de voluntariado anteriores, classificação e filtragem de publicações por categorias.

&nbsp;&nbsp;&nbsp;&nbsp; - Comunidade:
Este recurso oferece um catálogo abrangente de ONGs registradas, fornecendo aos usuários acesso fácil a informações cruciais sobre cada uma delas, incluindo sua missão, projetos em andamento e formas de contato. Além disso, disponibiliza recursos que incentivam o engajamento dos usuários com as ONGs, como oportunidades de doação e voluntariado. O serviço também apresenta uma lista de projetos que podem ser replicados, oferecendo detalhes específicos sobre cada iniciativa, como objetivos, metodologia e recursos necessários.

## Diagrama
&nbsp;&nbsp;&nbsp;&nbsp; Para o diagrama, pensamos em quebrá-la em duas partes: a Landing Page e seus conteúdos e outra para a plataforma em si.
### Diagrama da Landing Page
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo, o diagrama da nossa página inicial (Landing Page):
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Landing Page</sub><br><br>
<img src = "assets/MVC .drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp; Nessa lógica, o usuário só terá interação de input ao fazer login e cadastro. Em todas as outras páginas, nossa API só responderá à listagens (requisições GET) e a chamadas de endpoint para o frontend.

### Diagrama da Plataforma
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo, o diagrama da nossa plataforma:
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Plataforma</sub><br><br>
<img src = "assets/MVC Plataforma.drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp; Por fim, após efetuar o login, o usuário ganha acesso a uma variedade de funcionalidades que permitem interações diversas com o banco de dados, o qual inclui desde a realização de postagens até a visualização do feed, como também a busca por ONGs, projetos similares e pessoas com interesses em comum.




