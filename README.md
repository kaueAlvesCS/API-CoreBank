# Proibido IA !!!



<div align="center">

# 💳 CoreBank API

> Projeto prático desenvolvido por dois amigos com o objetivo de aprofundar e consolidar conhecimentos em desenvolvimento backend e banco de dados.

![Status](https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-yellow?style=for-the-badge)
[![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

</div>

<p align="center">
  <img src="https://images.unsplash.com/photo-1559526324-4b87b5e36e44?q=80&w=1000&auto=format&fit=crop" alt="CoreBank API Banner" width="700px">
</p>

## 📌 Sobre o Projeto

O **CoreBank API** é um projeto criado para fins puramente práticos e de estudo. A ideia principal é construir uma API do zero em dupla, superando as dificuldades com ecossistema web e praticando a integração real entre código e banco de dados.

O sistema simula as operações básicas de uma carteira digital simples:
- Cadastro e controle de contas de usuários.
- Registro de entradas (depósitos) e saídas (despesas).
- Simulação de transferências de saldo entre usuários cadastrados.
- Consulta de extrato das movimentações realizadas.

---

## 🎯 Objetivos de Aprendizado

- Modelagem e manipulação de banco de dados relacional com **PostgreSQL**.
- Utilização do **Prisma ORM** para migrações e consultas.
- Construção de rotas, regras de negócio e validações com **Node.js** e **TypeScript**.
- Prática de versionamento e colaboração em equipe através do **Git e GitHub**.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Node.js com TypeScript
- **Banco de Dados:** PostgreSQL
- **ORM:** Prisma
- **Documentação:** Swagger

---

## 🚀 Funcionalidades Previstas

- [ ] Cadastro e login de usuários.
- [ ] Criação automática de carteira para cada usuário.
- [ ] Registro de despesas e depósitos.
- [ ] Transferência de saldo fictício entre contas.
- [ ] Consulta de histórico e extrato de transações.

---

## 💻 Pré-requisitos

Para testar o projeto localmente:
* [Node.js](https://nodejs.org/)
* [Git](https://git-scm.com/)
* Banco de dados [PostgreSQL](https://www.postgresql.org/) rodando localmente ou na nuvem.

---

## ⚙️ Instalação e Execução

```bash
# Clone o repositório
git clone https://github.com/kaueAlvesCS/api-corebank.git
cd api-corebank

# Acesse o backend e instale as dependências
cd backend
npm install

# Configure as variáveis de ambiente com os dados do seu banco
cp .env.example .env

# Execute as migrações do banco de dados
npx prisma migrate dev

# Inicie o servidor
npm run dev
```

---

## 🤝 Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/kaueAlvesCS">
        <img src="https://github.com/kaueAlvesCS.png" width="110px" alt="Foto Kaue Alves"/>
      </a>
      <br />
      <b>Kaue Alves</b>
      <br />
      <a href="https://github.com/kaueAlvesCS">
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Perfil GitHub Kaue"/>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/nicolasccampos">
        <img src="https://github.com/nicolasccampos.png" width="110px" alt="Foto Nicolas"/>
      </a>
      <br />
      <b>Nicolas Campos</b>
      <br />
      <a href="https://github.com/nicolasccampos">
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Perfil GitHub Nicolas"/>
      </a>
    </td>
  </tr>
</table>

---

## 📝 Licença

Este projeto está sob os termos da licença **MIT**.
