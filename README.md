```markdown
<div align="center">

# 💳 AtomPay - Core Bancário & Gestor Financeiro

> Uma API robusta e plataforma de gestão financeira focada em integridade de dados, transações atômicas seguras (ACID) e análise inteligente de despesas.

![Status](https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-yellow?style=for-the-badge)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

</div>

<p align="center">
  <img src="https://images.unsplash.com/photo-1559526324-4b87b5e36e44?q=80&w=1000&auto=format&fit=crop" alt="AtomPay Banner" width="700px">
</p>

## 📌 Sobre o Projeto

O **AtomPay** é um projeto desenvolvido por estudantes de Ciência da Computação da **FECAP** durante o período de férias acadêmicas. O objetivo central é construir a infraestrutura e o núcleo transacional de uma carteira digital (fintech), abordando e solucionando desafios práticos de engenharia de software:

- **Consistência Numérica:** Armazenamento preciso de valores monetários evitando problemas de arredondamento de ponto flutuante.
- **Transações Atômicas (ACID):** Garantia de que movimentações e transferências entre contas sejam executadas de ponta a ponta sem perda de dados em caso de falha.
- **Inteligência de Gastos:** Consultas e agregações SQL para geração de relatórios de fluxo de caixa e agrupamento por categoria.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem Backend:** [Node.js](https://nodejs.org/) com [TypeScript](https://www.typescriptlang.org/)
- **Banco de Dados:** [PostgreSQL](https://www.postgresql.org/) (Hospedado via Supabase / Neon)
- **ORM / Migrações:** [Prisma ORM](https://www.prisma.io/)
- **Segurança & Validação:** JWT (JSON Web Tokens), Bcrypt e Zod
- **Documentação de Endpoints:** Swagger UI
- **Frontend (Painel Visual):** React + Vite com TailwindCSS e componentes Shadcn UI

---

## 🚀 Funcionalidades do Sistema

- [ ] **Autenticação:** Cadastro e autenticação segura com senhas criptografadas.
- [ ] **Carteira Digital:** Vinculação automática de conta com saldo inicial ao cadastrar um usuário.
- [ ] **Depósitos e Saques:** Operações de débito e crédito com validações de regra de negócio.
- [ ] **Transferências Entre Contas:** Simulação transacional segura entre usuários internos da plataforma.
- [ ] **Extrato Detalhado:** Histórico de movimentações com filtros por tipo e período.
- [ ] **Relatórios Mensais:** Métricas agregadas por categorias (alimentação, transporte, lazer, etc.).

---

## 💻 Pré-requisitos

Antes de iniciar, certifique-se de possuir em seu ambiente:
* [Node.js](https://nodejs.org/) (Versão 18.x ou superior recomendada)
* [Git](https://git-scm.com/)
* Uma instância ativa de [PostgreSQL](https://www.postgresql.org/) local ou conexão em nuvem via [Supabase](https://supabase.com/) / [Neon.tech](https://neon.tech/)

---

## ⚙️ Instalação e Execução

### 1. Clonando o Repositório
```bash
git clone https://github.com/SEU-USUARIO/atompay.git
cd atompay
```

### 2. Configuração do Backend
```bash
# Navegue até o diretório do backend
cd backend

# Instale os pacotes de dependências
npm install

# Copie o arquivo de exemplo para as variáveis de ambiente
cp .env.example .env
```
> Edite o arquivo `.env` gerado e insira sua string de conexão com o PostgreSQL na chave `DATABASE_URL`.

### 3. Execução das Migrações
```bash
npx prisma migrate dev
```

### 4. Executando o Servidor
```bash
npm run dev
```
O servidor estará acessível em `http://localhost:3333`.  
Acesse a documentação interativa das rotas via Swagger em: `http://localhost:3333/docs`.

---

## 🤝 Colaboradores

Projeto idealizado e desenvolvido em dupla:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/SEU-USUARIO">
        <img src="https://github.com/SEU-USUARIO.png" width="115px;" alt="Foto Kaue Alves"/><br>
        <sub>
          <b>Kaue Alves</b>
        </sub>
      </a>
      <br />
      <small>Modelagem de Dados & Integridade SQL</small>
    </td>
    <td align="center">
      <a href="https://github.com/USUARIO-NICOLAS">
        <img src="https://github.com/USUARIO-NICOLAS.png" width="115px;" alt="Foto Nicolas"/><br>
        <sub>
          <b>Nicolas</b>
        </sub>
      </a>
      <br />
      <small>Arquitetura Backend & Segurança</small>
    </td>
  </tr>
</table>

---

## 🎓 Instituição de Ensino

Projeto desenvolvido como prática de férias por graduandos da:  
**FECAP - Fundação Escola de Comércio Álvares Penteado**  
*Bacharelado em Ciência da Computação*

---

## 📝 Licença

Este projeto está sob os termos da licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.
```
