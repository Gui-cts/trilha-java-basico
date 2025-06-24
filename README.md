# 📘 Desafio: Contador - Santander Bootcamp Backend Java 2025

Este é o segundo desafio prático do **Bootcamp Santander Backend Java 2025**, oferecido pela [DIO (Digital Innovation One)](https://www.dio.me/). O objetivo é implementar um programa Java que realiza uma contagem entre dois números fornecidos pelo usuário, com tratamento de exceções.

## 🧾 Descrição

O programa solicita dois números inteiros:

- O primeiro parâmetro (`parametroUm`)
- O segundo parâmetro (`parametroDois`)

O sistema realiza uma contagem do número 1 até a diferença entre os dois números, **apenas se o segundo for maior que o primeiro**. Caso contrário, uma **exceção personalizada** é lançada informando o erro.

### 🧪 Exemplo de execução:
```
Digite o primeiro parâmetro
2
Digite o segundo parâmetro
5
Imprimindo o numero: 1
Imprimindo o numero: 2
Imprimindo o numero: 3
```
### ⚠️ Caso o segundo número seja menor que o primeiro:
```
Digite o primeiro parâmetro
10
Digite o segundo parâmetro
3
O segundo parâmetro deve ser maior que o primeiro
```
## 📌 Conceitos aplicados

- Leitura de dados com `Scanner`
- Tratamento de exceções com `try/catch`
- Criação e uso de exceção personalizada (`ParametrosInvalidosException`)
- Estrutura de controle `for` para laços de repetição
- Validação de entrada

## 🛠 Tecnologias utilizadas

- Java 21 (ou compatível)
- Execução via terminal ou IDE (Netbeans)
