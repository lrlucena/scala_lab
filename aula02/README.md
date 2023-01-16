# Criando um programa em Scala

## Ola mundo!

Usando a sintaxe tradicional de Scala

```scala
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Olá, mundo!")
  }
}
```

Usando a nova sintaxe de Scala (>= 3.0)

```scala
object HelloWorld:
  def main(args: Array[String]): Unit =
    println("Olá, mundo!")
```

Ou de forma mais simples

```scala
@main def main() =
  println("Ola Mundo!")
```

## Execução

Para executar

```shell
$> scala olamundo.scala
```

É possível executar e gerar um '.jar' para evitar compilar novamente na próxima execução.

```shell
$> scala -save olamundo.scala
```

## Variáveis

```scala
val nome = "João"   // 'val' (valores) não podem ser alterados
var idade = 19

// Hoje é meu aniversário
idade = idade + 1
```

## Entrada e saída

```scala
import io.StdIn._

printn("Qual o seu nome? ")
nome = readLine();
println(s"Ola ${nome}!")
```

## Exercício

1. Copie o código do programa "Ola Mundo" no seu computador e execute.
2. Crie uma nova versão do Ola Mundo que pergunta o nome do usuário e mostra uma mensagem com o nome do usuário.
3. 
