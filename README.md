# ⚽ Champions League API

API REST desenvolvida com Node.js e Express que simula dados da UEFA Champions League. O projeto foi criado com foco em aprendizado de desenvolvimento backend, criação de APIs e organização de código com boas práticas.

---

## 🚀 Tecnologias utilizadas

- Node.js
- Express
- JavaScript (ES6+)
- Nodemon (opcional)
- JSON (dados mockados)

---

## 📌 Funcionalidades

- Listar todos os times da Champions League
- Buscar time por ID
- Estrutura organizada com rotas
- Dados simulados (mock)

---

## 📁 Estrutura do projeto

champions-api/
│
├── src/
│   ├── app.js
│   ├── routes/
│   │   ├── teams.routes.js
│   │   ├── players.routes.js
│   │   └── matches.routes.js
│   ├── controllers/
│   └── data/
│       └── mock.js
│
├── server.js
└── package.json

---

## ⚙️ Como executar o projeto

### 1. Clonar o repositório

git clone https://github.com/seu-usuario/champions-api.git

### 2. Acessar a pasta

cd champions-api

### 3. Instalar dependências

npm install

### 4. Rodar o projeto

node server.js

Ou com nodemon:

npx nodemon server.js

---

## 🌐 Endpoints

### Times

GET /teams → Lista todos os times  
GET /teams/:id → Busca um time por ID

---

## 📦 Exemplo de resposta

{
  "id": 1,
  "name": "Real Madrid",
  "country": "Spain"
}

---

## 🔥 Melhorias futuras

- Integração com banco de dados (MongoDB)
- CRUD completo
- Filtros por país e jogadores
- Autenticação com JWT
- Documentação com Swagger
- Deploy da API

---

## 🧠 Aprendizados

- Criação de API com Express
- Estruturação de projeto Node.js
- Organização de rotas
- Uso de dados mockados
- Boas práticas de backend

## ⭐ Observação

Este projeto pode ser evoluído para uma API completa em nível profissional com banco de dados, autenticação e deploy.
