# 🔊 Chamador de Senhas - Sistema Full Stack

**Chamador** é um sistema completo (frontend + backend) para gerenciamento de senhas, ideal para uso em ambientes de atendimento como clínicas, órgãos públicos, bancos e recepções. O sistema permite criar, listar e chamar senhas de forma simples e prática.

---

## 🧱 Estrutura do Projeto

CHAMADOR/<br>
├── Back-end/ # API com Node.js<br>
│ ├── routes/ # Arquivos de rotas organizadas<br>
│ ├── index.mjs # Ponto de entrada da aplicação<br>
│ ├── .env # Variáveis de ambiente<br>
│ └── ...<br>
│<br>
├── Front-end/ # SPA com React + Vite<br>
│ ├── src/<br>
│ │ ├── pages/ # Páginas como Painel, Cadastro etc.<br>
│ │ ├── routes/ # React Router (AppRoutes.jsx)<br>
│ │ └── ...<br>
│ ├── index.html<br>
│ └── vite.config.js<br>
│<br>
└── README.md # Documentação<br>


---

## 🚀 Tecnologias Utilizadas

### Backend:
- Node.js
- Express.js
- dotenv
- Estrutura modular com rotas

### Frontend:
- React.js
- Vite
- React Router DOM
- CSS Global
- Modularização por páginas e rotas

---

## ⚙️ Como Executar o Projeto

```bash
cd Front-end
npm install
npm run dev

### 🔙 Backend

```bash
cd Back-end
npm install
npm run dev
