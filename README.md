<h1 align="center">
    <img alt="GoBarber" src="https://ik.imagekit.io/hwyksvj4iv/gobarber_19xmN2BUU.svg" width="250px" />
</h1>

<p align="center">
  <a href="#page_with_curl-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-começando">Começando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-iniciando-back-end">Node.js</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-iniciando-front-end">ReactJS</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#iphone-iniciando-mobile">React Native</a>
</p>

<h1 align="center">
    <img alt="GoBarber" src="" />
    <img alt="GoBarber Mobile" src="" />
</h1>

## :page_with_curl: Sobre
Este repositório inclui uma API REST em Node.js como back-end, um aplicativo em ReactJS como front-end e um aplicativo móvel em React Native, todos usando TypeScript.

Aqui está o GoBarber, uma plataforma para proprietários de barbearias ou salões de beleza agendarem serviços. Com este aplicativo móvel, os usuários podem visualizar todos os prestadores de serviços cadastrados e selecionar um para marcar um agendamento.

O provedor de serviços pode acessar todos os seus horários por meio de uma interface web, visualizando tanto os horários ocupados quanto os disponíveis.

**Node.js**: É uma API REST que realiza todas as operações de criação, leitura, atualização e exclusão de dados da aplicação, além de gerenciar a persistência de dados e tratar exceções. A API é capaz de fornecer dados tanto para o front-end quanto para dispositivos móveis.

**ReactJS**: Esta é uma página web na qual o provedor de serviços tem acesso a todo o calendário de agendamentos.

**React Native**: É um aplicativo que permite ao usuário acessar todos os prestadores de serviço cadastrados no App. Dessa forma, é possível agendar um serviço com o prestador de sua preferência.

## :books: Requisitos
- Ter [**Git**](https://git-scm.com/) para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.
- Ter [**Docker**](https://www.docker.com/) rodando um container PostgreSQL.
- Um dispositivo ou emulador iOS ou Android

## :rocket: Começando
``` bash
  # Clonar o projeto:
  $ git clone xxxxx

  # Entrar no diretório:
  $ cd gobarber
```

## :gear: Iniciando back-end
```bash
  # Entrar no diretório do back-end:
  $ cd backend

  # Instalar as dependências:
  $ yarn

  # Rodar as migrations:
  $ yarn typeorm migration:run

  # Rodar a aplicação:
  $ yarn dev:server
```

## :computer: Iniciando front-end
```bash
  # Entrar no diretório do front-end:
  $ cd frontend

  # Instalar as dependências:
  $ yarn

  # Rodar a aplicação:
  $ yarn start
```

## :iphone: Iniciando mobile
```bash
  # Entrar no diretório do mobile:
  $ cd mobile

  # Instalar as dependências:
  $ yarn

  # Rodar a aplicação:
  $ yarn ios ou yarn android 
```

Feito por Vinicius Meirelles 👋🏻 [Get in touch!](https://github.com/vnmeirelles)
