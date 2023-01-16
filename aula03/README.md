# Instruções

## If

Sintaxe antiga

```scala
import io.StdIn._

val a = readInt()
if a > 100 then {
  println("Valor Maior do que 100!")
} else {
  println("Valor menor ou igual que 100!")
}
```

Sintaxe nova (>= 3.0)

Note que a identação pode ser usada para definir blocos. A palavra `then` pode ser omitida mas nesse caso a condição precisa ficar entre parênteses: `if (a > 100) ...`

```scala
import io.StdIn._

val a = readInt()
if a > 100 then
  println("Valor Maior do que 100!")
else
  println("Valor menor ou igual que 100!")
```

Note que a identação pode ser usada para definir blocos. A palavra `then` pode ser omitida mas nesse caso a condição precisa ficar entre parênteses: `if (a > 100) ...`


# For

```scala
for a <- 1 to 3
    b <- 1 to 4 do
  println(s"${a} x ${b} = ${a*b}")
```
