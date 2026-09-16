# 💡 MindCash — "Do gasto ao significado"

> **Trabalho de Conclusão de Curso (TCC)**  
> **ETEC de Hortolândia** — Curso Técnico em Desenvolvimento de Sistemas  
> **Disciplina:** Programação Web III (PW3)  

---

## 📌 Sobre o Projeto

O **MindCash** não é apenas um gerenciador financeiro convencional. O objetivo central da aplicação é **dar significado aos gastos**, ajudando o usuário a entender sua relação emocional e prática com o dinheiro. 

A plataforma auxilia no controle financeiro pessoal integrando a **análise emocional das despesas** e convertendo valores em **horas de vida trabalhadas**, promovendo autoconhecimento financeiro e comportamental.

---

## 🎯 Objetivos e Funcionalidades Principais

- **Análise Emocional de Gastos:** Registro de despesas associadas ao estado emocional/percepção de valor no momento da compra.
- **Conversão em Horas de Vida:** Cálculo automático de quanto tempo de trabalho cada despesa representa com base na renda do usuário.
- **Gestão Financeira:** Controle de receitas, despesas e orçamentos de forma simples e visual.
- **Autenticação Segura:** Login, cadastro e proteção de rotas/sessões.
- **Sobre o Projeto / Equipe:** Página dedicada contendo informações do projeto e apresentação dos integrantes.

---

## 🛠 Stack Tecnológica

### Frontend Web
- **Framework:** React 19 (TypeScript)
- **Build Tool:** Vite
- **Roteamento:** `react-router-dom`
- **Validação de Formulários:** `react-hook-form` + `zod`
- **Estilização:** CSS Modules (`*.module.css`) + Variáveis Globais de CSS (`global.css`)
- **Identidade Visual:** Paleta *Blue Marine* (`--dark-charcoal`, `--dark-navy`, `--true-blue`, `--alice-blue-light`) e tipografia Inter.

### Back-end & Banco de Dados
- **Plataforma Back-end:** Supabase / PostgreSQL
- **Autenticação & Banco:** Gestão de usuários, rotas protegidas e armazenamento relacional seguro.
- **Variáveis de Ambiente:** Proteção de credenciais de acesso via arquivos `.env`.

---

## 👥 Integrantes do Grupo

- **Victor Furlan**
- **Pérola Evellyn**
- **Klayton Mendes**

---

## 🚀 Como Executar o Projeto Web

### Pré-requisitos
- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- Gerenciador de pacotes (`npm` ou `yarn`)

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/mindcash-web.git
   cd mindcash
   ```

2. **Instalar as dependências:**
   ```bash
   npm install
   ```

3. **Configurar as variáveis de ambiente:**
   Crie um arquivo `.env` na raiz do projeto com as credenciais do Supabase:
   ```env
   VITE_SUPABASE_URL=sua_url_aqui
   VITE_SUPABASE_ANON_KEY=sua_chave_aqui
   ```

4. **Executar em modo de desenvolvimento:**
   ```bash
   npm run dev
   ```

5. Acesse no navegador: `http://localhost:5173`

---

## 📄 Licença e Considerações
Projeto desenvolvido estritamente para fins acadêmicos como parte do Trabalho de Conclusão de Curso (TCC) na Etec de Hortolândia.
