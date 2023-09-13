# Dio-Trilha-Java-Básico - Controle de Fluxo 
Projeto Java Básico.

#### Autores
[Henrique Erinaldo](https://github.com/henriqueerds/dio-trilha-java-basico)

## Desafio <img align="center" alt="Henr-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg">
Neste desafio de projeto, vamos explorar alguns cenários com fluxos condicionais, repetições e excepcionais.
Este é um programa Java simples que demonstra o controle de fluxo usando exceções personalizadas. O programa recebe dois números inteiros como entrada via linha de comando e realiza uma contagem com base nesses números.

## Passos do Programa <img align="center" alt="Henr-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg">

1. **Entrada de Dados**: O programa usa a classe `Scanner` para solicitar ao usuário que digite dois números inteiros, representando os parâmetros.
   ```java
   import java.util.Scanner;
 
   Scanner scanner = New Scanner();
   ```

2. **Validação de Parâmetros**: Ele verifica se o primeiro parâmetro é menor que o segundo. Caso contrário, lança a exceção `ParametrosInvalidosException` com a mensagem "O segundo parâmetro deve ser maior que o primeiro".
    ```java
           public class ParametrosInvalidosException extends Exception {
            public ParametrosInvalidosException(String message) {
                super(message);
            }
        
        }
   ```

3. **Contagem e Impressão**: Se os parâmetros forem válidos, o programa realiza uma contagem e imprime os números incrementados no console.

## Estrutura do Código <img align="center" alt="Henr-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg">

- O código está organizado em duas classes principais:

  - `Contador`: A classe principal que contém o método `main` e a lógica de controle de fluxo.
    
    ```java
    public class Contador {
              public static void main(String[] args) {
              }
    ```
  - `ParametrosInvalidosException`: Uma classe de exceção personalizada para lidar com a validação de parâmetros.

- A lógica de contagem é encapsulada no método `contar`, que realiza a contagem e a impressão dos números incrementados.

## Execução <img align="center" alt="Henr-Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg">

Para executar o programa, siga estas etapas:

1. Compile o código-fonte Java.

2. Execute o programa com dois números inteiros como argumentos da linha de comando. Por exemplo:
   - java Contador 12 30

Isso resultará na contagem de 12 a 30 e na impressão dos números incrementados.

3. Se o segundo parâmetro for menor ou igual ao primeiro, o programa lançará uma exceção personalizada.

Esse é um exemplo simples de como usar controle de fluxo e exceções personalizadas em Java para manipular parâmetros e realizar uma tarefa específica.




