
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


## Cenário: Login com campos vazios

Dado que o usuário acessa a página de login

E não preenche usuário e senha  

Quando ele tenta realizar login  

Então o sistema deve informar que os campos são obrigatórios


---


# Suite: Testes de Finalização de Compra


## Cenário: Adicionar produto ao carrinho

Dado que o usuário está logado no sistema  

E visualiza a lista de produtos  

Quando ele clica no botão "Adicionar ao carrinho"

Então o sistema deve atualizar o ícone do carrinho com o item adicionado

---


## Cenário: Visualizar produtos no carrinho

Dado qque o usuário está logado no sistema

E possui um produto adicionado ao carrinho

Quando ele clica no ícone do carrinho

Então o sistema deve exibir a página com os produtos adicionados


---


## Cenário: Iniciar processo de checkout

Dado que o usuário está na página do carrinho

E possui pelo menos um produto adicionado 

Quando ele clica no botão checkout  

Então o sistema deve redirecionar para a página de informações do cliente  
