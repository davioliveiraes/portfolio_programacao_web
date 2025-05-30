<h1 align="center">Portfólio: Programação Web [Gerenciador de Usuários]</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <a href="#-Para-executar-o-projeto">Para executar o projeto</a>
</p>

<br>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Java 17
- Spring Boot 3.2.5
- Spring Data JPA
- Banco H2 (em memória)
- Maven

## 💻 Projeto

Um projeto utilizando o framework Spring Boot para o gerenciamento dos usuários de um sistema.
Se tratará de um projeto backend baseado RestAPI, ou seja, serão disponibilizados os endpoints necessários
para realizar as operações de gerenciamento de usuários (CRUD). O projeto é MVC e será necessário realizar
o modulo lógico para a criação da base de dados, bem como a conexão com o mesmo. Além da lógica base, será
necessário realizar os tratamentos de exceções.

## 👨‍💻 Para executar o projeto

<strong>Pré requisitos</strong>
- Java 17 ou superior
- Maven 3.6+

<strong>Verificar versões instaladas</strong>
```
java -version
javac -version
mvn -version
```

1. Clone o repositório: `git clone https://github.com/davioliveiraes/portfolio_programacao_web.git`
2. cd `portfolio_programao_web`
3. Instale as dependências: `mvn clean install`
4. Execute a aplicação: `mvn spring-boot:run`
5. Acesse a aplicação: Abra o navegador e acesso: `http://localhost:8080`
6. Teste o CRUD no POSTMAN: `http://localhost:8080/users`
   - POST: Criar novos registros
   - GET: Buscar e visualizar registros
   - PUT: Atualizar registros existentes
   - DELETE: Remover registros <br>
   <strong>Endpoints disponíveis: Após executar a aplicação, você pode testar os endpoints da API REST para operações CRUD</strong>
7. Link do vídeo demonstrando a aplicação: `https://www.youtube.com/watch?v=SWCz3fE4BW0&t=1138s`


