# 📌 Projeto Final – Capacitação Cypress: O Superpoder dos Testadores Modernos!

## 🎯 Objetivo
Este projeto foi desenvolvido como desafio final da capacitação **Cypress: O Superpoder dos Testadores Modernos**, com o intuito de aplicar na prática os conceitos aprendidos durante as aulas.

O objetivo principal é **automatizar cenários de teste** utilizando o framework Cypress, adotando boas práticas e garantindo organização, clareza e independência dos testes.

---

## 📅 Prazo de Entrega
**Início:** 06/08  
**Fim:** 20/08

---

## 🔗 URL do Sistema para Testes
[https://www.automationexercise.com/](https://www.automationexercise.com/)

---

## 📋 Escopo do Desafio
Automatizar **no mínimo 5 cenários de teste**, priorizando os fluxos principais e de exceção. Exemplos sugeridos:

- Cadastro com sucesso  
- Cadastro com email/usuário já existente  
- Login com sucesso  
- Login com falha  
- Fluxo completo de compra de uma categoria específica (Women, Men ou Kids), incluindo pagamento  

---

## 🛠 Requisitos Técnicos
- Utilizar o **padrão Page Object** para manter uma arquitetura de testes organizada  
- Realizar **validações com `should()`**  
- Criar **massas de teste** utilizando:
  - **Fixtures**  
  - **Faker.js** (fábrica de dados)  
- Gerar **relatório final** com **Allure Report**  

---

## ✅ Critérios de Avaliação
1. **Boas práticas na arquitetura dos testes**
   - Uso do padrão Page Object  
   - Configuração de `before` e `baseUrl`
2. **Fluxos de testes**
3. **Boas práticas no mapeamento de elementos**
4. **Independência entre casos de teste**
5. **Nomenclatura clara dos casos de teste**

---

## 📦 Estrutura Sugerida do Projeto
```plaintext
📁 cypress
 ├── 📁 e2e
 │   └── 📁 tests
 │       ├── cadastro.cy.js
 │       ├── login.cy.js
 │       └── compra.cy.js
 ├── 📁 fixtures
 │   └── usuario.json
 ├── 📁 support
 │   ├── commands.js
 │   └── 📁 pages
 │       ├── CadastroPage.js
 │       ├── LoginPage.js
 │       └── CompraPage.js
📁 reports
 └── allure-report
cypress.config.js
package.json
README.md
```

---

## 🚀 Como Executar o Projeto

### 1️⃣ Clonar o repositório
```bash
git clone <url-do-repositorio>
cd <nome-do-projeto>
```

### 2️⃣ Instalar as dependências
```bash
npm install
```

### 3️⃣ Executar os testes
```bash
npx cypress open
```
ou em modo headless:
```bash
npx cypress run
```

### 4️⃣ Gerar o relatório Allure
```bash
npx allure generate allure-results --clean
npx allure open
```

---

## 📚 Tecnologias Utilizadas
- [Cypress](https://www.cypress.io/)
- [Faker.js](https://fakerjs.dev/)
- [Allure Report](https://docs.qameta.io/allure/)
- JavaScript (Node.js)

---

## ✍️ Autor
Desenvolvido por **Bruna Amaral** como parte do desafio final da capacitação *Cypress: O Superpoder dos Testadores Modernos*.
