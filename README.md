# PrimeDirective Project

Este projeto em Java foi desenvolvido para praticar a identificação de números primos dentro de uma lista de inteiros, utilizando conceitos básicos de programação como laços, condicionais, métodos e estruturas de dados (`ArrayList`).

O programa percorre uma lista (`array`) de números inteiros, verifica quais são primos usando um método próprio e retorna uma lista contendo apenas esses números primos.

---

## 🚀 Funcionalidades

- Verificar se um número inteiro é primo (`isPrime`).
- Percorrer uma lista de inteiros e filtrar apenas os números primos (`onlyPrimes`).
- Imprimir os números primos encontrados na lista.

---

## 🏗️ Estrutura do Código

- **PrimeDirective.java**
    - Classe principal com os métodos:
        - `isPrime(int number)`: retorna `true` se o número for primo.
        - `onlyPrimes(int[] numbers)`: retorna uma lista (`ArrayList`) apenas com os primos.
    - `main()`: cria uma instância da classe, define a lista de entrada e exibe os resultados.

---

## 🖥️ Como executar

1. Compile o código:
    ```bash
    javac PrimeDirective.java
    ```

2. Execute o programa:
    ```bash
    java PrimeDirective
    ```

---

## 🌱 Possíveis melhorias

- Permitir entrada personalizada de números pelo usuário.
- Otimizar o método de verificação de primalidade (checagem até a raiz quadrada).
- Adicionar testes unitários para verificar os métodos `isPrime` e `onlyPrimes`.

---

## 📚 Aprendizado

Este projeto foi criado como um exercício prático para reforçar:
- Uso de métodos em Java.
- Estruturas de repetição e decisão.
- Manipulação de arrays e `ArrayList`.
- Organização de código orientado a objetos.

