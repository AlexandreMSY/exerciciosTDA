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

### Senão se (else if)

```
se(condição){
    //código
}senão se(condição){
    //código
}else{
    //código
}
```

```
Algorítimo senão seExemplo
Ìnicio
    Inteiro numero = 1
    se (numero == 1){
        escreva("Número é 1")
    }senão se(numero == 2){
        escreva("Número é 2)
    }else{
        escreva("Numero é qualquer outra coisa")
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

### Escolha / Caso (switch case)
```
escolha (variavel){
    caso valor1:
        //codigo
        pare

    caso valor2:
        //codigo
        pare

    padrão:
        //codigo
}

```

```
Algorítimo switchCase
Inicio
    Inteiro numero = 2
    String diaSemana


    escolha (numero){
        caso 1:
            diaSemana = "domingo"
            pare

        caso 2:
            diaSemana = "segunda"
            pare

        caso 3:
            diaSemana = "terça"
            pare

        caso 4:
            diaSemana = "quarta"
            pare

        caso 5:
            diaSemana = "quinta"
            pare

        caso 6:
            diaSemana = "sexta"
            pare

        caso 7:
            diaSemana = "sabado"
            pare
        
        padrão:
            diaSemana = "não encontrado"
    }

    escreva(diaSemana)

Fim
```

# Estruturas de Repetição

### Para (for loop)
```
para (váriavel, condição, modificador){
    //código
}
```

```
Algorítimo paraExemplo
Início
    para(inteiro numero = 0; numero <= 10; numero++){
        escreva(numero)
    }
Fim
```

### Enquanto (while loop)
```
enquanto(condição){
    //código
}
```

```
Algorítimo enquantoExemplo
Início
    Inteiro numero = 0

    enquanto(numero <= 10){
        escreva(numero)
        numero = numero + 1
    }
Fim
```

### Faça Enquanto (do while loop)
```
faça{
    //código
}enquanto(condição)
```

```
Algorítimo facaEnquanto
Início
    Inteiro numero = 0
    
    faça{
        escreva(numero)
        numero = numero + 1
    }enquanto(numero <= 10)
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
```
    void printarHelloWorld(){
        escreva("Hello World")
    }

    Algoritímo funçãoExemplo
    Ìnicio
        printarHelloWorld()
    Fim
````
