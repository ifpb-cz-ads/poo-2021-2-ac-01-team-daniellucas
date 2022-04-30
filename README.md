## 1) Explique qual a função da Máquina Virtual Java(JVM).

A JVM tem como função fazer com que a aplicação tenha portabilidade com os diferentes sistemas operacionais, assim, escrevendo apenas uma aplicação na qual irá ser compatível com os sistemas operacionais.

## 2) Qual a diferença entre JRE e JDK?

O JRE executa um programa Java e da suporte a bibliotecas padrões do Java, ou seja, ele tem o necessário para rodar o código, enquanto que o JDK tem por funcionalidade o desenvolvimento.

## 5) Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?

Ocorreu o erro:
Error: Main method not found in class Questao3, please define the main method as:
  public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application

Esse erro se deve ao fato de que todo programa em java precisa ter o método main como ponto de partida, método esse que foi transformado em start nessa questão.

## 7) Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?

Ocorreu o erro:
QUESTAO6.java:1: error: class, interface, enum, or record expected
PUBLIC CLASS QUESTAO6
^
QUESTAO6.java:5: error: class, interface, enum, or record expected
        SYSTEM.OUT.PRINTLN("Sem time");
        ^
QUESTAO6.java:6: error: class, interface, enum, or record expected
    }
    ^
3 errors

Esse erro ocorre devido ao fato de java ser uma linguagem case sensitive o que quer dizer que letras maiúsculas são diferenciadas das minúsculas.

## 8) Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?

Ocorreu o erro:
Questao6ComNomeDiferente.java:1: error: class Questao6 is public, should be declared in a file named Questao6.java
public class Questao6
       ^
1 error

Erro esse ocorrido porque todos os arquivos java precisam ter o seu nome igual ao nome da classe a qual está neles.
