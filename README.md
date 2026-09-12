

# hands-on
arquivos
atividades 
1-programa {
  funcao inicio() {
    inteiro numero, antecessor, sucessor

    escreva("Digite um numero inteiro: ")
    leia(numero)
  
   escreva(" Antecessor: ", numero - 1,"\n")

   escreva(" Sucessor: " , numero + 1,"\n")


  }
}

2-programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um numero: ")
    leia(numero)
  
   escreva("Mostre o dobro: ", numero * 2, "\n")

   escreva("Mostre o triplo: " , numero * 3, "\n")


  }
}

3-programa {
  funcao inicio() {
    inteiro n1, n2, n3

    escreva("primeira nota: ", "\n")
     leia(n1)

    escreva("segunda nota: ","\n")
    leia(n2)

    escreva("terceira nota: ","\n")
    leia(n3)

    escreva("O resultado da media: ",(n1 + n2 + n3) / 3,"\n")
  
  }
}

4-programa {
  funcao inicio() {
  real n1, n2
  escreva("Digite o primeiro numero: ")
  leia(n1)

    escreva("Digite o segundo numero: ")
    leia(n2)
   
    escreva("Soma: ",(n1 + n2),"\n")

    escreva("Subtracao: ",(n1 - n2),"\n")

    escreva("Multiplicacao: ",(n1 * n2),"\n")
   
    escreva("Divisao: ",(n1 / n2),"\n")
  }
}

5-programa {
  funcao inicio() {
  real c
  escreva("Digite a temperatura em Celsius: ","\n")
  leia(c)
  
    escreva("Fahrenheit: ",(c * 9 / 5) + 32,"\n")
  
  }
}

6-programa {
  funcao inicio() {
  real raio
  escreva("Digite um raio: ")
  leia(raio)

    escreva("Area: ", 3.14 * raio * raio)
  
  }
}

7-programa {
  funcao inicio() {
    real km, litros
    escreva("Digite a distancia em km: ")
    leia(km)
    
    escreva("Digite a quantidade de litros: ")
    
    leia(litros)

    escreva("Consumo: ", (km / litros),"\n")
  }
}

8-programa {
  funcao inicio() {
    real conta, valorDaTaxa, total, valorPorPessoa
    escreva("Digite um valor: ")
    leia(conta)

    escreva("O valor da taxa sera: ", valorDaTaxa = conta * 10 / 100 ,"\n")

    total = conta + valorDaTaxa

    valorPorPessoa = total / 3

    escreva("Cada pessoa devera pagar: ", valorPorPessoa,"\n")
    
    escreva("O valor total com a taxa: ", total,"\n")

  }
}

9-programa {
  funcao inicio() {
    real compra, percentual, desconto, valorFinal
    escreva("Digite o valor da compra: ") 
    leia(compra)

    escreva("Digite o percentual de desconto: ","\n")
    leia(percentual)

    desconto = compra * percentual / 100

    valorFinal = compra - desconto
    escreva("O valor do desconto sera: ", desconto,"\n")

    escreva("O valor final sera: ", valorFinal,"\n")

  }
}

10-programa {
  funcao inicio() {
    inteiro idade
    logico maiorDeIdade
    escreva("Digite sua idade: ")
    leia(idade)

    maiorDeIdade = idade >= 18

    escreva("Maior de idade: ", maiorDeIdade,"\n")
    
  }
}

11-programa {
  funcao inicio() {
   real numero
   logico positivo
   escreva("Digite um numero: ")
   leia(numero)

    positivo = numero > 0
   
    escreva("O numero e: ", positivo,"\n")

  }
}

12-programa {
  funcao inicio() {
  real numero, x, y
  logico estaEntre
  escreva("Digite um numero: ")
  leia(numero)
  
  escreva("Digite o valor de x: ","\n")
  leia(x)

    escreva("Digite o valor de y: ","\n")
    leia(y)

    estaEntre = numero >= x e numero <= y

    escreva("Esta entre: ", estaEntre,"\n")

  }
}

13-programa {
  funcao inicio() {
   logico a, b
   escreva("O valor e: ")
   leia(a)

    escreva("O valor e: ")
    leia(b)

    escreva("Resultado: ", a e b)

  }
}

14-programa {
  funcao inicio() {
   logico a, b
   escreva("O valor de A: ")
   leia(a)

    escreva("O valor de B: ")
    leia(b)

    escreva("Resultado: ", a ou b)

  }
}

15-programa {
  funcao inicio() {
   logico valor 
   escreva("O valor e: ")
   leia(valor)
   
    escreva("Resultado: ",nao valor,"\n")

  }
}

16-programa {
  funcao inicio() {
   logico a, b, c
   escreva("Valores: ")
   leia(a, b, c)

    escreva("Resultado: ", (a e b) ou c,"\n")
   
  }
}

17-programa {
  funcao inicio() {
   logico a, b
   escreva("Valores ")
  
    a = verdadeiro
    b = verdadeiro
   
    escreva("E: ", a e b, "\n")

    escreva("OU: ", a ou b, "\n")

    a = verdadeiro
    b = falso

    escreva("E: ", a e b, "\n")

    escreva("OU: ", a ou b, "\n")

    a = falso
    b = falso
   
    escreva("E: ", a e b, "\n")

    escreva("OU: ", a ou b, "\n")
   
    a = falso
    b = verdadeiro
   
    escreva("E: ", a e b, "\n")

    escreva("OU: ", a ou b, "\n")

  }
}

18-






















































