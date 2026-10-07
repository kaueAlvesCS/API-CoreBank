<div align="center">

# 💳 CoreBank API

> Projeto prático desenvolvido durante as férias para colocar a mão na massa, superar dificuldades com desenvolvimento web e consolidar conhecimentos em Backend e Banco de Dados.

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

O **CoreBank API** nasceu de uma iniciativa própria minha (Kaue) e do meu colega de faculdade (Nicolas) durante as férias do nosso 2º semestre de Ciência da Computação na **FECAP**. 

Como vínhamos de uma base em C# e sentíamos bastante dificuldade com programação web, decidimos aproveitar o período de recesso para criar um projeto do zero em dupla. O objetivo não é criar um sistema comercial pronto, mas sim ter um laboratório real para:

- Entender como funciona a comunicação entre uma API e um banco de dados.
- Praticar a criação de tabelas, chaves e relacionamentos no **PostgreSQL**.
- Aprender a usar o **Node.js com TypeScript** na prática para construir rotas e regras de negócio.
- Perder o receio de ferramentas web e aprender a versionar um projeto em equipe pelo **Git e GitHub**.

A aplicação simula uma carteira digital simples: o usuário pode criar uma conta, registrar seus gastos e ganhos do dia a dia e simular transferências de saldo fictício para outros usuários cadastrados.

---

## 🎯 O que estamos praticando e aprendendo

- [x] Configuração de ambiente e conexão do Node com banco relacional.
- [x] Modelagem de tabelas e relacionamentos usando o **Prisma ORM**.
- [ ] Criação de rotas HTTP (GET, POST, etc.) e retorno de dados em JSON.
- [ ] Lógica para atualizar saldos (somar depósitos, subtrair compras e transferências).
- [ ] Boas práticas de organização de pastas no backend.
- [ ] Noções de front-end com React para consumir essa API no final do projeto.

---

## 🛠️ Tecnologias Escolhidas

- **Backend:** Node.js com TypeScript
- **Banco de Dados:** PostgreSQL
- **Ferramenta de Banco (ORM):** Prisma
- **Documentação de Rotas:** Swagger
- **Interface (Futura):** React (apenas para testar as rotas de forma visual)

---

## 🚀 Funcionalidades Previstas

- [ ] **Cadastro e Login:** Criação de conta simples para o usuário acessar o sistema.
- [ ] **Carteira:** Cada usuário cadastrado inicia com uma conta com saldo zerado.
- [ ] **Movimentações Básicas:** Registrar entradas (dinheiro que entrou) e saídas (gastos).
- [ ] **Transferência Fictícia:** Poder enviar um valor da sua conta para a conta de outro usuário cadastrado.
- [ ] **Extrato:** Listagem simples de todas as entradas e saídas que o usuário realizou.

---

## 💻 Pré-requisitos

Para rodar o projeto localmente quando estiver concluído, é necessário ter instalado:
* [Node.js](https://nodejs.org/)
* [Git](https://git-scm.com/)
* Acesso a uma instância de [PostgreSQL](https://www.postgresql.org/) (local ou na nuvem)

---

## ⚙️ Como Rodar o Projeto

```bash
# 1. Clone o repositório
git clone https://github.com/kaueAlvesCS/api-corebank.git
cd api-corebank

# 2. Acesse a pasta do backend e instale as dependências
cd backend
npm install

# 3. Configure a conexão do seu banco no arquivo .env
cp .env.example .env

# 4. Rode as migrações para criar as tabelas no seu PostgreSQL
npx prisma migrate dev

# 5. Inicie o servidor em modo de desenvolvimento
npm run dev
```

---

## 🤝 Quem Está Desenvolvendo

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/kaueAlvesCS">
        <img src="https://github.com/kaueAlvesCS.png" width="110px" alt="Foto Kaue Alves"/>
      </a>
      <br />
      <b>Kaue Alves</b>
      <br />
      <small>Foco: Banco de Dados (PostgreSQL & Prisma)</small>
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
      <small>Foco: Backend & Rotas da API (Node.js & TS)</small>
      <br />
      <a href="https://github.com/nicolasccampos">
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Perfil GitHub Nicolas"/>
      </a>
    </td>
  </tr>
</table>

---

## 🎓 Faculdade

Projeto desenvolvido para fins de estudo e prática por alunos de Ciência da Computação da:  
**FECAP - Fundação Escola de Comércio Álvares Penteado**

---

## 📝 Licença
