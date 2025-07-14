# 📝 Blog Pessoal API


Este projeto foi desenvolvido como parte do programa de formação da Generation Brasil, com o objetivo de aplicar na prática os conhecimentos adquiridos em desenvolvimento backend, segurança, testes e deploy.

A aplicação simula o backend de uma plataforma de blog, permitindo que usuários se cadastrem, realizem login e publiquem postagens com temas específicos. Ela possui um sistema completo de autenticação, documentação da API com Swagger, testes automatizados e está publicada na nuvem via Render.


## ⚙️ Tecnologias
NestJS (Framework principal)

TypeORM (Conexão com banco de dados)

JWT + Bcrypt (Autenticação segura)

Swagger (Documentação automática)

Jest (Testes)

Render (Deploy da API)


## 🧩 Entidades (Models)
👤 Usuário
id

nome 

usuario (email)

senha (criptografada)

foto

Relacionamento: 1 usuário → várias postagens

## 🏷️ Tema
id

descricao

Relacionamento: 1 tema → várias postagens

## 📝 Postagem
id

titulo

texto

data

Relacionamento: pertence a 1 tema e 1 usuário


## 🔐 Segurança
Login com JWT

Rotas protegidas por Guards

Criptografia de senha com bcrypt

Após iniciar a aplicação, acesse:
👉 [(http://localhost:4000/)

Você verá uma interface interativa onde pode testar os endpoints como POST /auth/login, GET /postagens, etc.

# Clonar o repositório
git clone https://github.com/seu-usuario/blog-pessoal-backend.git

# Acessar a pasta
cd blog-pessoal-backend

# Instalar as dependências
npm install

# Rodar o projeto
npm run start:dev

☁️ Deploy
O projeto está hospedado na plataforma Render.

## 📌 Status
✅ Projeto funcionando com:

CRUD de usuários, temas e postagens

Login com autenticação JWT

Documentação Swagger

Testes com Jest

Deploy na nuvem

👩‍💻 Desenvolvido por
Giulia Barreto
Desenvolvedora Full Stack | Generation Brasil
