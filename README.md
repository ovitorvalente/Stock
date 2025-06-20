<!-- markdownlint-disable MD040 -->
<!-- markdownlint-disable MD031 -->
<!-- markdownlint-disable MD034 -->

# 🧠 Stock – Fullstack App com Rust + Next.js

Este é o projeto **Stock**, uma aplicação fullstack construída com:

- 🦀 **Rust** no backend (API REST)
- ⚡ **Next.js** no frontend (React + Tailwind)
- 🐘 Banco de dados relacional (PostgreSQL)

---

## 📂 Estrutura do Projeto

```

stock/
├── backend/ # Backend em Rust (API)
├── frontend/ # Frontend em Next.js
├── .gitignore
├── README.md
└── docker-compose.yml

```

---

## 🚀 Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/ovitorvalente/stock.git
cd stock
```

### 2. Rodar o backend (Rust)

```bash
cd backend
cargo run
```

### 3. Rodar o frontend (Next.js)

```bash
cd frontend
npm install
npm run dev
```

---

## 📦 Tecnologias usadas

- **Rust** com [actix-web](https://actix.rs/)
- **Next.js 14** com App Router
- **TailwindCSS** para estilização
- **PostgreSQL**
- **TypeScript** no frontend

---

## 📄 .env.example

Você pode criar os arquivos `.env` em `backend/` e `frontend/` com base no exemplo abaixo:

```env
# backend/.env
DATABASE_URL=postgres://usuario:senha@localhost:5432/stock_db

# frontend/.env.local
NEXT_PUBLIC_API_URL=http://localhost:8000
```

---

## 📌 Licença

Este projeto é proprietário e de uso comercial.
Todos os direitos reservados © Vitor Valente, 2025.
Para uso, distribuição ou parcerias, entre em contato via e-mail: ovitorvalente@gmail.com.

---

## ✨ Autor

Desenvolvido por **Vitor Valente**
📧 contato: [ovitorvalente@gmail.com](mailto:ovitorvalente@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/ovitorvalente) | [GitHub](https://github.com/ovitorvalente)
