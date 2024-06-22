# DesafioControleFluxo Dio Santander - Java

Este repositório contém a implementação de um desafio de controle de fluxo em Java, onde o objetivo é criar um programa que recebe dois números inteiros como parâmetros e realiza uma contagem com base nesses números. O projeto inclui a criação de uma exceção personalizada para validar as entradas do usuário.

## Funcionalidades

- **Entrada de Dados:**
  - O programa solicita dois números inteiros ao usuário via terminal.
  
- **Validação de Parâmetros:**
  - Se o primeiro número for maior ou igual ao segundo, o programa lança uma exceção personalizada chamada `ParametrosInvalidosException`.
  - A mensagem da exceção será: "O segundo parâmetro deve ser maior que o primeiro".

- **Contagem e Impressão:**
  - Se os parâmetros forem válidos, o programa imprime uma sequência de números incrementados, desde 1 até a diferença entre os dois números fornecidos.
  - Exemplo de saída: "Imprimindo o número 1", "Imprimindo o número 2", ..., "Imprimindo o número N".

## Estrutura do Projeto

- **ParametrosInvalidosException.java**
  - Define uma exceção personalizada que é lançada quando o primeiro parâmetro é maior ou igual ao segundo.
  
- **Contador.java**
  - Contém a lógica principal do programa:
    - Recebe e valida os parâmetros de entrada.
    - Lança a exceção personalizada se a validação falhar.
    - Realiza a contagem e imprime os números se a validação for bem-sucedida.

## Como Executar

1. Clone o repositório para sua máquina local.
2. Compile as classes Java:
   ```sh
   javac Contador.java ParametrosInvalidosException.java
