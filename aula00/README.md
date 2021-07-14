# Instruções

## Instalação de Scala usando o SDKMAN

````bash
sdk i scala 3.0.0
````

## Testando a instalação

````bash
$ scala -version
$ scala

scala> val nome = "Mundo"
val nome: String = Mundo

scala> println("Olá " + nome +"!")
Olá Mundo!

scala> :quit
$
````

## Ambiente REPL

````bash
$ scala -version
$ scala

scala> val nome = "Mundo"
val nome: String = Mundo

scala> println("Olá " + nome +"!")
Olá Mundo!

scala> :quit
$
````

## Executando um programa como um script (sem compilar)

````bash
$ scala olamundo.scala
````

## Executando e gerando um .jar

````bash
$ scala -jar olamundo.scala
$ scala -jar olamundo.scala

$ scala -jar olamundo.jar
$ java -jar olamundo.jar
````

## Compilando

````bash
$ scalac -d ola.jar olamundo.scala
$ scala -jar ola.jar
````