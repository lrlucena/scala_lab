# Funções

## Funções como um valor

```scala
val numeros = List(1, 2, 3, 4, 5, 6, 7, 8)

def par(x: Int) = x % 2 == 0

val pares = numeros.filter(par)

val pares2 = numeros.filter(x => x % 2 == 0)

val p = (x: Int) => x % 2 == 0

@main def main() =
  println(s"Números pares: ${pares}")
  println(s"Números pares: ${pares2}")

// Filtre os números ímpares
// Filtre os números maiores do que 4
```

## Recursão

```scala
def somar(a: Int, b: Int): Int =
  if a < b then
    a + somar(a + 1, b)
  else
    a

def somar2(a: Int, b: Int, total: Int = 0): Int =
  if a < b then
    somar2(a + 1, b, total + a)
  else
    total


@main def main() =
  println(somar(1, 10))
  println(somar(1, 10))
```

## Exemplo usando Potigol

```portugol
numeros = [1, 2, 3, 4, 5, 6, 7, 8]

par(x: Inteiro) = x mod 2 == 0

pares = numeros.selecione(par)

pares2 = numeros.selecione(x => x mod 2 == 0)

p = (x: Inteiro) => x mod 2 == 0

pares3 = numeros.selecione(p)


escreva "Números pares: {pares}"
escreva "Números pares: {pares2}"
escreva "Números pares: {pares3}"


// Filtre os números ímpares
// Filtre os números maiores do que 4
```

