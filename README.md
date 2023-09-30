# Variáveis e condicionais!
# AULA 3

# **PRATICANDO**

Em Python, você pode declarar variáveis de forma simples e direta. Não é necessário especificar o tipo de dados ao declarar uma variável, pois Python é uma linguagem de fracamente tipada e dinâmica. Aqui está a sintaxe básica para declarar uma variável em Python:

nome_da_variavel = valor_da_variavel

# #Declarando variáveis

idade = 25
nome = "João"
altura = 1.75

# #Exibindo os valores das variáveis

print("Nome:", nome)
print("Idade:", idade)
print("Altura:", altura)

Neste exemplo, **`idade`**, **`nome`** e **`altura`** são nomes de variáveis, e você atribuiu valores a elas usando o operador de atribuição (**`=`**). Lembre-se de que os nomes de variáveis em Python são sensíveis a maiúsculas e minúsculas, ou seja, **`nome`** e **`Nome`** seriam considerados nomes de variáveis diferentes.

Além disso, é importante escolher nomes de variáveis significativos para tornar seu código mais legível e compreensível. Evite nomes genéricos como **`a`**, **`x`**, etc. em favor de nomes descritivos que indiquem o propósito da variável

**SINAIS DE COMPARAÇÃO** 

Em Python, você pode usar diversos sinais de comparação para comparar valores e criar expressões condicionais. Esses sinais de comparação são frequentemente usados em combinação com os operadores lógicos para tomar decisões com base em condições verdadeiras ou falsas. Aqui estão os principais sinais de comparação em Python:

1. **Igual (==)**: Verifica se dois valores são iguais.

a = 5
b = 5
resultado = a == b  # Resultado será True

**Diferente (!=)**: Verifica se dois valores são diferentes.

a = 5
b = 3
resultado = a != b  # Resultado será True

1. **Maior que (>)**: Verifica se o valor da esquerda é maior que o valor da direita.

a = 7
b = 4
resultado = a > b  # Resultado será True

Menor que (<): Verifica se o valor da esquerda é menor que o valor da direita.

a = 2
b = 6
resultado = a < b  # Resultado será True

Maior ou igual (>=): Verifica se o valor da esquerda é maior ou igual ao valor da direita.

a = 5
b = 5
resultado = a >= b  # Resultado será True

Menor ou igual (<=): Verifica se o valor da esquerda é menor ou igual ao valor da direita.

a = 3
b = 6
resultado = a <= b  # Resultado será True

Esses sinais de comparação podem ser usados em expressões condicionais para comparar valores e tomar decisões com base nas condições estabelecidas.

Exemplo usando sinais de comparação em uma expressão condicional:

nota = 85

if nota >= 70:
print("Aprovado")
else:
print("Reprovado")

Neste exemplo, o sinal de comparação >= é usado para verificar se a nota é maior ou igual a 70, decidindo se o aluno foi aprovado ou reprovado com base nessa condição.

EXEMPLOS: 

```
#comentário
numero =  1
numero2 = 2
numero3 =  3

PÁGINA  18

# == igualdade 
# = atribuição
# < menor que 
# > maior que
# != diferente
# <= menor ou igual
# >= maior ou igual 

if (numero < numero2):
  print('o numero 1 é maior')
else: 
    print('o numero 2 é menor')
```

```
senha =  1234
entrada  = input("Digite sua senha")

if (senha == 1234):
  print('Acesso permitido')
else: 
    print('Acesso negado')
```

```
#pagina  17  -> OPERADORES ARITMÉTICOS

# soma  +
# subtração -
# divisão /
# multiplicação *
```

# Concatenação:

```
mensagem = "ola "
nome = input("Diga seu nome ")
print (mensagem + nome )

mensagem = "ola"
nome = input("Diga seu nome ")
print (mensagem , nome )
```

## **Lista de Exercícios 01**

Tipos de Dados Primitivos. Variáveis.

Operadores e Expressões aritméticos Básicos.

Entrada e Saída.

### 1 - Crie um programa para efetuar a leitura de um número inteiro e apresentar o resultado do quadrado deste número.

### 2 -
Crie duas variáveis para armazenar seu primeiro nome e sobrenome. Em seguida, concatene-as para formar seu nome completo e exiba o resultado.

### 3 -
Peça ao usuário para digitar dois números inteiros e armazene-os em variáveis. Realize a concatenação desses números como strings e exiba o resultado.

### 4 -
Crie uma variável para armazenar a palavra "Python". Em seguida, adicione um número inteiro ao final da palavra usando a concatenação e exiba o resultado.

### 5 -
Declare uma variável contendo uma frase. Em seguida, peça ao usuário para digitar uma palavra e concatene essa palavra no final da frase. Exiba o resultado.

**6 -**

**Crie três variáveis para armazenar a quantidade de horas, minutos e segundos. Concatene esses valores para formar uma mensagem de tempo no formato "hh:mm:ss".**

**7 -
Declare duas variáveis com números de telefone, incluindo um código de área e o número principal. Concatene esses valores para formar um número de telefone completo.**

**8 -
Crie uma lista de ingredientes para uma receita. Use concatenação para formar uma única string que liste os ingredientes separados por vírgulas.**

**9 -
Peça ao usuário para digitar três adjetivos e armazene-os em variáveis. Em seguida, use essas palavras para criar uma frase concatenada que descreve algo interessante.**

[Resolução dos exercícios atividade 3](https://www.notion.so/Resolu-o-dos-exerc-cios-atividade-3-04ad95281e544622b7d3d883da9b8112?pvs=21)

# ATIVIDADE 3 → IF()

**1 - Crie uma condição para comparar idades: 45 e 18 -  QUAL É MENOR E QUAL É MAIOR?**

**2 - Crie um sistema para permitir a verificação de menores em um show**

**3 - Crie um algoritmo que permita a entrada de 3 notas de alunos, utilize o bloco de código if()**

**para verificar se o aluno passou.**

## INDENTAÇÃO:

IDENTAR O CÓDIGO É UM TIPO DE CONVENÇÃO EM ALGUMAS LINGUAGENS, PORÉM PARA PYTHON É ESSENCIAL.

GERA ERRO CASO O CÓDIGO NÃO ESTEJA INDENTADO CORRETAMENTE. 

**INSTALAÇÃO DO PYTHON NO WINDOWS**

https://www.python.org/downloads/windows/ 

https://python.org.br/instalacao-windows/ 

VSCODE

[https://code.visualstudio.com/https://code.visualstudio.com/](https://code.visualstudio.com/)
