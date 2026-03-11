
# Test Cases - SauceDemo

Este arquivo contém exemplos de cenários de teste escritos em Gherkin utilizados neste projeto.

Os cenários foram organizados de acordo com as suites criadas na ferramenta Qase.

---

# Suite: Testes de Login

## Cenário: Login com credenciais válidas

Dado que o usuário acessa a página de login
E possui credenciais válidas  
Quando ele insere username e password corretos  
Então o sistema deve redirecionar para a página de produtos

---

## Cenário: Login com senha incorreta

Dado que o usuário acessa a página de login  
E possui um usuário válido 
Quando ele insere a senha incorreta 
Então o sistema deve exibir mensagem de erro

---

# Suite: Testes de Finalização de Compra

## Cenário: Adicionar produto ao carrinho

Dado que o usuário está logado no sistema  
E visualiza uma lista de produtos  
Quando ele clica em adicionar produto ao carrinho  
Então o sistema deve atualizar o carrinho com o item selecionado  

---

## Cenário: Iniciar processo de checkout

Dado que o usuário possui produtos no carrinho  
E está na página do carrinho  
Quando ele clica no botão checkout  
Então o sistema deve redirecionar para a página de informações do cliente  
