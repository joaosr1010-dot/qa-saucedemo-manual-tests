# Projeto de Testes Manuais - SauceDemo

Este projeto foi desenvolvido como parte dos meus estudos para atuar como QA (Quality Assurance).

O objetivo é demonstrar conhecimentos em planejamento, criação e execução de testes manuais.

## Ferramentas utilizadas

- Qase
- GitHub

## Metodologia

Os cenários de teste foram escritos utilizando a linguagem Gherkin.

Estrutura utilizada:

Dado  
E  
Quando  
Então

## Funcionalidades testadas

### Login
- Login com credenciais válidas
- Login com credenciais inválidas
- Validação de campos obrigatórios

### Checkout
- Adição de produtos ao carrinho
- Acesso ao carrinho de compras
- Início do processo de checkout

## Estrutura das suites de testes

![Estrutura das suites](evidences/test-suites-structure.png)

## Evidências da execução dos testes

### Execução da suite de testes de Login

![Execução login](evidences/qase-login-tests.png)

### Execução da suite de testes de Checkout

![Execução checkout](evidences/qase-checkout-tests.png)

## Bug report

Foi documentado um bug relacionado à validação de campos de login.

Localização:


/bug-report/bug-report-login.md
