# Projeto Base - Cypress

Este é um projeto base para testes automatizados utilizando o **Cypress**.

<img width="1279" height="850" alt="133" src="https://github.com/user-attachments/assets/aead34e3-2091-4e5c-b909-8821aa0bd33## Pipeline de CI (GitHub Actions)

Os testes Cypress rodam automaticamente a cada `push` ou `pull request`.

![Pipeline do Cypress executando na aba Actions](133.JPG)3" />

![Testes Cypress](https://github.com/Li-code1/ebac-cypress-samples/actions/workflows/main.yml/badge.svg)

## 🧩 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (recomenda-se a versão **LTS**)
- [Git](https://git-scm.com/)

## 🚀 Passos para rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/EBAC-QE/ebac-cypress-samples.git
```

### 2. Entrar na pasta do projeto

```bash
cd ebac-cypress-samples
```

### 3. Instalar as dependências

```bash
npm install
```

### 4. Rodar o Cypress (modo interativo)

```bash
npx cypress open
```

### 5. Rodar os testes (modo headless)

```bash
npx cypress run
```
