<h1 align="center">
    <img src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" alt="GoStack" />
</h1>

<h3 align="center">
  Projeto: GoBarber
</h3>

<blockquote align="center">“Sua única limitação é você mesmo!”</blockquote>

<p align="center">
  <img src="https://img.shields.io/github/languages/count/alleycarvalho/gobarber?color=%2304D361" alt="GitHub language count">

  <img src="https://img.shields.io/badge/license-MIT-%2304D361" alt="License">

  <a href="https://github.com/alleycarvalho/gobarber/stargazers">
    <img src="https://img.shields.io/github/stars/alleycarvalho/gobarber?style=social" alt="Stargazers">
  </a>
</p>

## :rocket: Sobre o projeto

Um aplicação de agendamentos para salão de beleza.

## :computer: Testar aplicação

### Executar contêiner do postgres com docker:

```js
docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres:11
```

### Executar migrations (Após criação do Banco de Dados):

```js
yarn sequelize db:migrate
```

## :mortar_board: Ferramentas e conceitos utilizados

- Framework [Express](https://expressjs.com/pt-br/)
- Reiniciar servidor automaticamente com [Nodemon](https://github.com/remy/nodemon/)
- Sintaxe moderna com [Sucrase](https://github.com/alangpierce/sucrase/)
- Utilizando [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) & [EditorConfig](https://editorconfig.org/)
- Arquitetura MVC (Model-View-Controller)
- ORM: Abstração do Banco de Dados com [Sequelize](https://github.com/alangpierce/sucrase/)
- Migrations: Controle de versão para base de dados
- Seeders: Popular base de dados em desenvolvimento
- Utilização do [Docker](https://www.docker.com/)
- Banco de Dados: [PostgreSQL](https://www.postgresql.org/)
- Gerenciamento de Banco de Dados com [Postbird](https://electronjs.org/apps/postbird)
- Autenticação [JWT: Json Web Token](https://jwt.io/)
- Utilização de middlewares
- Validação dos dados de entrada com [YUP](https://github.com/jquense/yup)

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Projeto prático desenvolvido por <b>Alley M. Carvalho</b>
