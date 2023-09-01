# Conta-Banco

# Projeto ContaBanco - Desafio Java Básico

Este projeto faz parte da trilha de Java Básico da [Digital Innovation One (DIO)](http://www.dio.me) e tem como objetivo exercitar os conceitos apresentados no módulo de Sintaxe Java. O desafio propõe a criação de um programa chamado `ContaBanco` que permite aos usuários inserir informações sobre uma conta bancária via terminal e, em seguida, exibir uma mensagem de boas-vindas com base nessas informações.

## Autores

- Autor: Natanael Amaral de Barros

## Descrição do Desafio

O desafio consiste em criar um programa Java que realiza as seguintes tarefas:

1. Recebe dados via terminal contendo as características de uma conta bancária, conforme os atributos abaixo:

    - **Número**: Inteiro (Exemplo: 1021)
    - **Agência**: Texto (Exemplo: 067-8)
    - **Nome do Cliente**: Texto (Exemplo: MARIO ANDRADE)
    - **Saldo**: Decimal (Exemplo: 237.48)

2. Utiliza a classe `Scanner` para permitir que os dados sejam inseridos via terminal, seguindo as instruções fornecidas aos usuários.

3. Após a entrada de todas as informações, o programa concatena essas informações e exibe a seguinte mensagem de boas-vindas:

   ```plaintext
   "Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque".

