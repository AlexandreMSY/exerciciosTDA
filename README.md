<h1 align="center">Sintaxe do psuedo-código</h1>

# Entrada e Saida
### Saída

<h3> <strong> escreva(output)</strong> </h3>

```
Algorítimo saídaExemplo
Ìnicio

    escreva("Hello World!")
    //escreve Hello World!

Fim
```
### Entrada

<h3> <strong>leia(variavel)</strong> </h3>

```
Algorítimo entradaExemplo
Início

    Literal palavra

    escreva("Entre com uma palavra: ")
    leia(palvara)

    escreva("Palavra: " + palavra)

Fim

```

# Tipos de dados
* Inteiro
    - Usado para atribuir numeros inteiros.
    - Equivalente ao Int.

* Real 
    - Usado para atribuir numeros com casa decimal.
    - Equivalente ao Float e o Double.

* Literal
    - Usado para atribuir sequencias de caracteres.
    - Equivalente a String.

* Lógico
    - Usado para atribuir verdadeiro ou falso.
    - Equivalente ao Bool.

# Estrutura de Decisão

### Se (if)
```
se(condição){
    //código
}
```

```
Algorítimo seExemplo
Ìnicio
    Inteiro numero = 5
    se (numero != 6){
        escreva("Número não é 6")
    }
Fim
```

### Senão (else)

```
se (condição){
    //codigo
}senão{
    //codigo
}
```

```
Algorítimo senaoExemplo
Ìnicio
    Inteiro media = 6
    se(numero >= 6){
        escreva("Aprovado!")
    }senão{
        escreva("Reprovado!")
    }
Fim
```

# Funções
```
tipoDeRetorno nomeDaFunção(parametros){
    //código
}
```

```
    Inteiro dobro(Inteiro numero){
        retorna numero * 2
    }

    Algoritímo funçãoExemplo
    Ìnicio
        Inteiro numero

        escreva("Entre com um número: ")
        leia(numero)

        numero = dobro(numero)

        escreva(numero)
````

### void são funções sem retorno
```
    void printarHelloWorld(){
        escreva("Hello World")
    }

    Algoritímo funçãoExemplo
    Ìnicio
        printarHelloWorld()
    Fim
````
