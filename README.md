# CoreBank API

## Projeto Prático de Desenvolvimento Backend e Banco de Dados

## Integrantes: <a href="https://github.com/kaueAlvesCS">Kauê Alves Andrade</a>, <a href="https://github.com/nicolasccampos">Nicolas Coimbra de Campos</a>

## Descrição
<br>

<p align="center">
  <img src="imagens/logo.png" alt="CoreBank API" border="0">
</p>

<br>
CoreBank API é uma aplicação backend desenvolvida para simular as operações básicas de uma carteira digital e gestão financeira. O projeto tem como objetivo principal a aplicação prática de conceitos de banco de dados relacional e desenvolvimento de APIs em dupla durante o período de férias.
<br><br>
Atualmente o projeto está em fase inicial de desenvolvimento, com foco na estruturação do banco de dados, definição das tabelas de usuários, contas e lógica de transações.
<br><br>
Outras informações:
<ul>
  <li>API REST desenvolvida em Node.js com TypeScript</li>
  <li>Banco de dados relacional PostgreSQL</li>
  <li>Mapeamento objeto-relacional utilizando Prisma ORM</li>
  <li>Foco nas regras de negócio de saldo, extrato e persistência correta de dados</li>
</ul>
<br><br>

## 🛠 Estrutura de Pastas

-Raiz<br>
|<br>
|-->documentos<br>
&emsp;|-->diagramas_banco<br>
<br>
|-->imagens<br>
<br>
|-->backend<br>
&emsp;|-->prisma<br>
&emsp;&emsp;|-->schema.prisma<br>
&emsp;|-->src<br>
&emsp;&emsp;|-->controllers<br>
&emsp;&emsp;|-->services<br>
&emsp;&emsp;|-->routes<br>
<br>
|readme.md<br>
|.gitignore<br>

<br>

## 💻 Configuração para Desenvolvimento

Para abrir e rodar este projeto localmente, são necessárias as seguintes ferramentas:

- <a href="https://nodejs.org/">Node.js (v18 ou superior)</a>
- <a href="https://git-scm.com/">Git</a>
- Acesso a um banco <a href="https://www.postgresql.org/">PostgreSQL</a> (local ou hospedado em nuvem)

```sh
# Passos para rodar o projeto

1. Clone o repositório oficial no GitHub
git clone https://github.com/kaueAlvesCS/api-corebank.git

2. Acesse a pasta do backend
cd api-corebank/backend

3. Instale as dependências necessárias
npm install

4. Configure as variáveis de ambiente com a URL do seu banco no arquivo .env
cp .env.example .env

5. Execute as migrações para criar as tabelas no banco de dados
npx prisma migrate dev

6. Inicie o servidor em modo de desenvolvimento
npm run dev
```

<br>

## 📋 Licença/License

<a href="https://github.com/kaueAlvesCS/api-corebank">CoreBank API</a> © 2026 by <a href="https://github.com/kaueAlvesCS">Kauê Alves</a> e <a href="https://github.com/nicolasccampos">Nicolas Coimbra</a>. Licenciado sob os termos da Licença MIT.

<br>

## 🎓 Referências

Documentações e materiais utilizados para o desenvolvimento da API:

1. <https://www.prisma.io/docs>
2. <https://www.typescriptlang.org/docs/>
3. <https://nodejs.org/docs/latest/api/>
4. <https://www.postgresql.org/docs/>
