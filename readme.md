# 🚀 Aplicação Web Full Stack – Entrega 01

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Disciplina:** Programação Avançada para Web  
**Aluno:** Renato Côrtes  
**Período:** 7º – Engenharia de Software  
**Entrega:** 01  

---

## 📖 Descrição do Projeto

Esta aplicação web full stack foi desenvolvida para a disciplina **Programação Avançada para Web**, apresentando:

- **Arquitetura cliente-servidor** com backend em Node.js e Express.  
- **Frontend** utilizando HTML, CSS e JavaScript.  
- **Persistência de dados** via banco SQL.  
- **Ambiente Docker** para configuração local isolada e reproduzível.  

O projeto demonstra boas práticas de integração entre frontend e backend, controle de variáveis de ambiente e manipulação de dados de forma segura.

---

## 🛠 Tecnologias Utilizadas

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express  
- **Banco de Dados:** SQL (via Docker)  
- **Gerenciamento de Ambiente:** Docker & Docker Compose  
- **Configuração de Variáveis de Ambiente:** `.env`

---

## 📁 Estrutura do Projeto

/projeto-web
│
├── backend/ # Código do servidor Node.js e APIs
├── frontend/ # Código da interface do usuário
├── .env # Variáveis de ambiente
├── docker-compose.yml # Configuração do Docker
├── package.json # Dependências do projeto
└── README.md # Documentação do projeto

yaml
Copiar código

---

## ⚙ Pré-requisitos

Para rodar a aplicação localmente, instale:  

- [Node.js](https://nodejs.org/) (v14 ou superior)  
- [Docker](https://www.docker.com/) e [Docker Compose](https://docs.docker.com/compose/)  
- [SQL Server / MySQL / PostgreSQL] conforme configuração do projeto  

---

## 🚀 Instalação e Execução

1. Clone o repositório:

```bash
git clone <URL_DO_REPOSITORIO>
cd projeto-web
Configure as variáveis de ambiente no arquivo .env.

Inicialize os containers Docker:

bash
Copiar código
docker-compose up -d
Instale as dependências do backend:

bash
Copiar código
cd backend
npm install
Execute o servidor Node.js:

bash
Copiar código
npm start
Abra o frontend no navegador:

arduino
Copiar código
http://localhost:<PORTA_DO_FRONTEND>
✅ Funcionalidades
Integração entre frontend e backend via API REST

Persistência de dados em banco SQL

Ambiente isolado e reproduzível com Docker

Configuração de variáveis de ambiente para maior segurança

👨‍💻 Autor
Renato Côrtes
7º período – Engenharia de Software

📝 Observações
Entrega referente à Entrega 01 da disciplina Programação Avançada para Web.
O projeto segue boas práticas de programação, organização de código e manutenibilidade.

