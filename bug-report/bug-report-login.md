# Bug Report

## ID
BUG-001

## Título
Validação inadequada de campos no login ao inserir espaços em branco

## Sistema
SauceDemo

## URL
https://www.saucedemo.com

## Ambiente
Browser: Chrome

## Passos para reproduzir

1. Acessar a página de login
2. Inserir um espaço no campo Username
3. Inserir um espaço no campo Password
4. Clicar em Login

## Resultado esperado

O sistema deve validar os campos e informar que são obrigatórios.

## Resultado obtido

O sistema retorna mensagem informando que usuário ou senha são inválidos.

## Severidade

Baixa

## Prioridade

Baixa