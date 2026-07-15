<div align="center">

# 🚗 Predict My Ride API

### API desenvolvida para previsão e gerenciamento de corridas utilizando arquitetura REST.

<p align="center">

<img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js"/>
<img src="https://img.shields.io/badge/API-REST-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge"/>

</p>

### 🔗 Links do Projeto

🌐 **Deploy:** https://predict-my-ride-api.lovable.app

📂 **Repositório:** https://github.com/miguelsgomess19/Projeto_final_noite

</div>

---

# 📖 Sobre o Projeto

O **Predict My Ride API** é uma API REST desenvolvida para gerenciar e disponibilizar informações relacionadas ao sistema de previsão de corridas.

O projeto foi desenvolvido seguindo boas práticas de desenvolvimento Backend, organização em camadas e arquitetura escalável, permitindo integração com aplicações Front-end e outros serviços.

Seu principal objetivo é disponibilizar uma estrutura robusta para operações de cadastro, consulta, atualização e gerenciamento de dados relacionados às corridas.

---

# 🎯 Objetivos

- Construir uma API REST moderna
- Aplicar boas práticas de desenvolvimento
- Implementar arquitetura escalável
- Facilitar integração com Front-end
- Disponibilizar documentação organizada
- Servir como projeto de portfólio

---

# 🚀 Funcionalidades

✔ Cadastro de usuários

✔ Login e autenticação

✔ Cadastro de corridas

✔ Consulta de dados

✔ Atualização de informações

✔ Exclusão de registros

✔ Integração com Front-end

✔ API RESTful

✔ Tratamento de erros

✔ Organização em camadas

✔ Validação de dados

✔ Respostas padronizadas

---

# 🛠 Tecnologias Utilizadas

## Backend

- Node.js
- Express
- JavaScript
- REST API

## Banco de Dados

- (Adicionar banco utilizado)

Exemplo:

- PostgreSQL
- MySQL
- MongoDB
- SQLite

## Ferramentas

- Git
- GitHub
- Insomnia
- Postman
- VS Code

---

# 📁 Estrutura do Projeto

```
src/
│
├── controllers/
├── routes/
├── services/
├── models/
├── middlewares/
├── config/
├── database/
├── utils/
└── app.js
```

---

# ⚙️ Instalação

Clone o projeto

```bash
git clone https://github.com/miguelsgomess19/Projeto_final_noite.git
```

Entre na pasta

```bash
cd Projeto_final_noite
```

Instale as dependências

```bash
npm install
```

Configure as variáveis de ambiente

```env
PORT=3000

DATABASE_URL=

JWT_SECRET=
```

Execute o projeto

```bash
npm run dev
```

ou

```bash
npm start
```

---

# 🌐 Endpoints

## Usuários

| Método | Endpoint | Descrição |
|---------|----------|-----------|
| POST | /users | Criar usuário |
| GET | /users | Listar usuários |
| GET | /users/:id | Buscar usuário |
| PUT | /users/:id | Atualizar usuário |
| DELETE | /users/:id | Remover usuário |

---

## Corridas

| Método | Endpoint | Descrição |
|---------|----------|-----------|
| POST | /rides | Criar corrida |
| GET | /rides | Listar corridas |
| GET | /rides/:id | Buscar corrida |
| PUT | /rides/:id | Atualizar corrida |
| DELETE | /rides/:id | Excluir corrida |

---

# 🔐 Autenticação

Caso a API utilize JWT:

```
Authorization

Bearer SEU_TOKEN
```

---

# 📦 Exemplo de Requisição

```json
POST /rides

{
   "origin":"São Paulo",
   "destination":"Campinas",
   "distance":95,
   "duration":75
}
```

---

# 📤 Exemplo de Resposta

```json
{
   "id":1,
   "origin":"São Paulo",
   "destination":"Campinas",
   "distance":95,
   "duration":75,
   "createdAt":"2026-07-15"
}
```

---

# 📊 Arquitetura

```
Cliente

     │

     ▼

Rotas

     │

     ▼

Controllers

     │

     ▼

Services

     │

     ▼

Models

     │

     ▼

Banco de Dados
```

---

# 🧪 Testes

Para executar os testes:

```bash
npm test
```

---

# 📚 Boas práticas utilizadas

- REST API
- Clean Code
- Organização em Camadas
- Separação de Responsabilidades
- Tratamento Global de Erros
- Validação de Dados
- Padronização de Respostas
- Código Modular
- Versionamento com Git

---

# 📈 Melhorias Futuras

- Docker
- Swagger
- Testes Automatizados
- Deploy em Cloud
- Cache
- Logs
- Monitoramento
- CI/CD
- Rate Limit
- Upload de arquivos

---

# 🤝 Contribuindo

1. Faça um Fork

2. Crie uma Branch

```
git checkout -b feature/minha-feature
```

3. Commit

```
git commit -m "Minha nova feature"
```

4. Push

```
git push origin feature/minha-feature
```

5. Abra um Pull Request

---

# 👨‍💻 Desenvolvedor

## Miguel Gomes

Backend Developer

GitHub

https://github.com/miguelsgomess19

---

# ⭐ Apoie o Projeto

Se este projeto foi útil para você:

⭐ Deixe uma Star

🍴 Faça um Fork

📢 Compartilhe

---

<div align="center">

### Obrigado pela visita!

🚀 Desenvolvido com dedicação e muito café ☕

</div>