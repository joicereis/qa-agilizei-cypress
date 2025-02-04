# QA Agilizei - Cypress

Este repositório contém atividades relacionadas ao projeto de automação de testes da ferramenta **DevFinance**.

## 📌 Sobre o Projeto
A ferramenta **DevFinance** foi disponibilizada pelo instrutor **Samuel Borges Lucas** na plataforma **Agilizei**. Seu propósito é auxiliar no controle de finanças, permitindo:
- Adicionar transações de entrada e saída com seus respectivos valores;
- Excluir transações registradas.

## 🛠️ Tecnologias Utilizadas
- **Cypress** – Framework para automação de testes end-to-end
- **JavaScript** – Linguagem utilizada nos testes
- **Node.js** – Runtime para execução do Cypress
- **Git/GitHub** – Controle de versão

## 🎯 Escopo dos Testes
Este projeto foi construído durante o curso **Cypress Direto ao Ponto** e, até a versão atual, abrange os seguintes cenários:

✅ Inclusão de transações de crédito e débito;
✅ Exclusão de transações registradas.

## ⚙️ Como Executar os Testes

### 1️⃣ Clonar o Repositório
```sh
 git clone https://github.com/joicereis/qa-agilizei-cypress.git
```

### 2️⃣ Instalar Dependências
```sh
 npm install
```

### 3️⃣ Executar os Testes
Rodar todos os testes automatizados:
```sh
 npx cypress open
```
Rodar os testes no modo headless:
```sh
 npx cypress run
```

## 📂 Estrutura do Projeto
```
qa-agilizei-cypress/
│── cypress/
│   ├── integration/       # Casos de teste
│   ├── fixtures/          # Massa de dados
│   ├── plugins/           # Configuração de plugins
│── cypress.json           # Configuração do Cypress
│── package.json           # Dependências do projeto
│── README.md              # Documentação
```

## 📢 Contato
Caso tenha dúvidas ou sugestões, fique à vontade para entrar em contato! 😊

📧 [Entre em contato por e-mail](joice.jdosreis@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/joice-meriele-reis/)