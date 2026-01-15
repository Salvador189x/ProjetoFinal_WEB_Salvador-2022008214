# Sistema de Agendamentos – Projeto Fullstack

Projeto desenvolvido para a disciplina de Arquitetura Web, com o objetivo de aplicar conceitos de desenvolvimento fullstack, integração entre frontend e backend, autenticação e persistência de dados.

---

## Objetivo do Projeto

Desenvolver uma aplicação web completa que permita:
- Autenticação de usuários
- Gerenciamento de agendamentos
- Comunicação entre frontend e backend por meio de API REST

---

## Tecnologias Utilizadas

### Backend
- Node.js
- Express
- MongoDB
- Mongoose
- JWT
- Joi
- Cors

### Frontend
- React
- Vite
- JavaScript
- CSS
- Fetch API

---

## Estrutura do Projeto

```
projeto-fullstack/
├── client/
├── server/
└── README.md
```

---

## Funcionalidades

- Login de usuários
- Autenticação com JWT
- Proteção de rotas
- CRUD de agendamentos
- Interface web em React

---

## Como Executar o Projeto

### Pré-requisitos
- Node.js
- MongoDB
- NPM ou Yarn

---

### Backend

```
cd server
npm install
npm run dev
```

Crie um arquivo `.env` na pasta `server` com:

```
PORT=3001
MONGO_URI=mongodb://localhost:27017/agendamentos
JWT_SECRET=chave_secreta
```

---

### Frontend

```
cd client
npm install
npm run dev
```

A aplicação estará disponível em:

```
http://localhost:5173
```

---

## Rotas da API

### Autenticação
- POST /auth/login
- POST /auth/register

### Agendamentos
- GET /appointments
- POST /appointments
- PUT /appointments/:id
- DELETE /appointments/:id

---

## Autor

Projeto desenvolvido para fins acadêmicos.
Salvador de Jesus Malavé Campos
2022008214

---

## Status

Projeto finalizado e funcional.
