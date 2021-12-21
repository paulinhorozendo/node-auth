# Autenticação com Node.js e MongoDB + JWT - Login e Registro com Node.js

## Introdução

API criada com Express e MongoDB.
Endpoints públicos e privados.
Os endpoints privados precisam do token para serem acessados.
O token é entregue através do login bem sucedido e precisa ser enviado pelo header da requisição.
Um middleware faz a autenticação se o token é válido ou não.
Não há persistência de sessão no back-end, tudo é feito pelo token.
Acesse https://jwt.io/introduction para informações detalhadas sobre JWT(JSON Web Token).

## Detalhes da Aplicação

Criar uma API de autenticação com: Node.js, #Express, #MongoDB (Mongoose) e que gerencia tokens por #JWT

Criar rotas públicas e privadas, para que possa validar a presença da autorização do token

Que vai impedir quem não possui de acessar recursos privados, porém pode acessar endpoints públicos

Além disso, inserir os usuários no banco de dados MongoDB, com auxílio da ODM Mongoose

A API será feita com base no Node.js, utilizando o framework Express

As senhas dos usuários serão criptografadas com bcrypt para realizar validações dos dados enviados para API pelas requisições

Postman utilizado para testes da API e MongoDB Atlas para Banco de dados

Instalados alguns pacotes do npm durante o desenvolvimento
