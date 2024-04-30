# Trabalho Prático: Autenticação com JWT em Node.js e Express com Sequelize e SQLite

## Introdução

Neste trabalho prático, você irá aprender a implementar um sistema de autenticação utilizando JSON Web Tokens (JWT) em uma aplicação Node.js com Express. Além disso, você utilizará o Sequelize como ORM (Object-Relational Mapping) para lidar com o banco de dados SQLite.

## Objetivos

- Compreender os conceitos fundamentais de autenticação e autorização em aplicações web.
- Implementar um sistema de autenticação utilizando JWT em uma aplicação Node.js.
- Utilizar o Sequelize para criar e manipular modelos de dados e interagir com o banco de dados SQLite.

## Pré-requisitos

- Conhecimento básico de Node.js e Express.
- Familiaridade com conceitos de banco de dados relacionais.
- Ter o Node.js e o npm (Node Package Manager) instalados em sua máquina.

## Tarefas

### 1. Configuração do Projeto

1. Crie um novo projeto Node.js.
2. Instale as dependências necessárias, incluindo Express, Sequelize e jsonwebtoken.
3. Configure o Sequelize para trabalhar com o banco de dados SQLite.

### 2. Modelagem de Dados

1. Crie os modelos de dados necessários para o sistema de autenticação, incluindo usuário (com campos como nome, email e senha).
2. Utilize o Sequelize para definir as associações entre os modelos, como relacionamentos entre usuário e outras entidades.

### 3. Implementação da Autenticação

1. Crie rotas para registro (cadastro de novos usuários) e login.
2. Implemente a lógica de autenticação utilizando JWT, gerando tokens para usuários autenticados.
3. Utilize middlewares do Express para proteger rotas que exigem autenticação, verificando a presença e validade dos tokens JWT.

### 4. Testes e Documentação

1. Teste as rotas de autenticação para garantir seu funcionamento correto.
2. Documente o processo de configuração e implementação, incluindo instruções claras sobre como executar o projeto e utilizar as funcionalidades implementadas.

## Recursos

- [Documentação do Express](https://expressjs.com/)
- [Documentação do Sequelize](https://sequelize.org/)
- [Documentação do JWT](https://jwt.io/)
- [Tutoriais e exemplos online sobre autenticação com JWT em Node.js e Express.](https://www.youtube.com/results?search_query=autentica%C3%A7%C3%A3o+com+jwt+em+node.js+e+express+sqlite)

## Entrega

- O trabalho deve ser entregue em formato repositório git com um Markdown, contendo todas as seções descritas acima.
- Envie o link do repositório no formulário https://forms.gle/Usr8or91EqtDRRyb8

## Considerações Finais

Este trabalho prático fornecerá a você uma compreensão prática dos conceitos de autenticação em aplicações web, bem como experiência na implementação de um sistema de autenticação utilizando tecnologias populares do ecossistema Node.js. Certifique-se de seguir as melhores práticas de segurança ao lidar com dados sensíveis dos usuários. Boa sorte!
