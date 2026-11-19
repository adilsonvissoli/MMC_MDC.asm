# MMC e MDC em Assembly MIPS

Este projeto foi desenvolvido em Assembly MIPS com o objetivo de calcular o **MMC (Mínimo Múltiplo Comum)** e o **MDC (Máximo Divisor Comum)** entre dois números inteiros positivos.

O programa solicita dois valores ao usuário, realiza os cálculos e apresenta os resultados na tela. Caso algum dos valores informados seja menor ou igual a zero, o programa exibe uma mensagem de erro.

## Como funciona?

O programa utiliza duas funções principais:

- **MDC:** calcula o máximo divisor comum entre os dois números utilizando o algoritmo de Euclides.
- **MMC:** calcula o mínimo múltiplo comum utilizando os valores informados e o resultado do MDC.

A fórmula utilizada para calcular o MMC é:

\[
MMC(a,b) = \frac{a \times b}{MDC(a,b)}
\]

## Como executar?

Para executar o programa, é necessário utilizar um simulador que ofereça suporte à linguagem Assembly MIPS, como o **MARS** ou o **QtSPIM**.

1. Abra o simulador escolhido.
2. Carregue o arquivo `TP`.
3. Execute o programa.
4. Informe os dois números inteiros positivos quando solicitado.
5. Confira os resultados apresentados na tela.

## Tecnologias utilizadas

- Assembly MIPS
- MARS / QtSPIM

## Objetivo do projeto

O projeto tem como finalidade praticar conceitos de programação em Assembly MIPS, trabalhando com operações aritméticas, desvios condicionais, estruturas de repetição, registradores e chamadas de funções.

---
