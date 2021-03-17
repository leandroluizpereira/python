
# :books: Anotaçôes sobre a linguagem Python

## Ir direto a determinado assunto :

* :star: Básico
  * [Sobre a linguagem Python](#sobre)
  * [Declaraçâo de variável](#declaracaovariavel)
  * [Concatenação de variável](#concatenacaodevariavel)
  * [Operadores Aritméticos](#operadoresaritmeticos)
  * [Operadores lógicos](#operadoreslogicos)
  * [Input funçâo](#funcaoinput)
  * [Edentaçâo Python](#edentacaopython)
  * [If encadeado](#ifencadeado)
  * [Desvio condicional if ternário](#condicionalifternario)
  * [Estrutura for](#estruturafor)
  * [Leitura array com for](#Leituraarraycomfor)
* :star::star: Intermediario

<div id ='sobre'/>

<br>

#  Sobre a linguagem Python 

## Criação da linguagem 
A linguagem python foi lançado em 1991 por Guido van Rossum 

## Sintaxe da linguagem: "simples" 
 * não é obrigatório colocar ponto e vírgula.
 * as aspas são opicional pode ser dupla ou simples.
 * edentaçâo é obrigatório 


## Programas ou sites prediletos


| Programas | Site | sobre |     Classificaçâo            |
|--|--|--|--|
|✖️|[Colab](https://colab.research.google.com)| |:star::star::star::star::star:|
|  |  |  |:star::star::star:                                         |





 <div id='basico'/>
 
 
 
 # :star: Básico
 

 
 
  <div id='declaracaovariavel'/>
 
 ## Declaraçâo de variável
 
  não e necessário colocar o tipo de dados para a variável, a indentificação e automática .
  ```python
  #Exemplo
  x = 30; # int
  frase = 'Leandro está estudando os conceitos da linguagem python'  # String
  ligarCpu = 'true'   # bool
  a = 3.4  # float
  x = 3 # int
  ```
  <div id='concatenacaodevariavel'/>
  
  ## Concatenaçâo da variável
  ```python 
  #Exemplo 
  nome = 'Leandro Luiz Pereira'
  linguagem ='Python'
  print(' '+nome+', acha a linguagem ',linguagem,' muito relevante')
  ```
  nota-se que pode ser usado tando vírgula quanto o sinal de + para concatenaçâo.
  
  
  <div id='operadoresaritmeticos'/>
  
  ## Operadores Aritméticos 
  ```Python
  #Exemplos:
  #para converter e somar as variável 
  a = 3.4
  x = 3
  y = float(x) + float(a)
  print(y)
  #método sum()
  b =[2,4,3,5,6]
  sum(b) 
  ```
 <div id='operadoreslogicos'/>
 
  ## Operadores lógicos 
  ```Python
  a = 20
  b = 30
  x = 40
  y = 39
  #Exemplo: AND :
  if(a<b and x<y):
    print('As duas expressôes são verdadeiro')
  else:
    print('As duas expressões são  falsa')
  #exemplo: OR
  if(a<b or x<y):
     print('Uma das expressões são verdadeiro')
  else:
     print('As duas expressôes são falsa')
    #Exemplo: com AND e NOT
  if(a>b and  not x<y):
    print('as duas expressâo são verdadeiro')
  else:
    print('as duas expresões são falso')
  ```
     
  <div id='funcaoinput'/>
  
 ## Funçâo input 
   O input ele pega as informações digitada do teclado e retorna o tipo para String, se caso queira pegar dígitos de números, tem 
   que fazer a conversão da variável para o tipo inteiro, e bem simples fazer esta conversão no python,exemplo:
   ```python
   print('Digite um valor:')
   n = int(input())
   ```
  <div id='edentacaopython'/>
  
## Edentaçâo Python
```python 
   
#Exemplo de edentaçâo com if 
a=2
if (a==2):
  # Espaço tab para estar dentro do if a==2
  print('a == 2 é verdadeiro')
  a=3
  #este if está dentro do if (a==2)
  if (a==3):
    #Espaço tab para estar dentro da instrução if a==3
    print(' a == 3 é verdadeiro')
    a=4
    b=3
    #este if está dentro do if (a==3)
    if (b == 3 and a == 4):
      print('    b == 3 and a == 4 que está dentro do if a == 3 e verdadeiro')
    else :
      print('   o valor b == 3 and a == 4 é falso')
  else:
    print(' a == 3 é falso')
  #este if está dentro do if (a==2)
  if (a==4):
    # Espaço tab para estar dentro comando de decisão if a==4
    print(' a == 4 é verdadeiro')
  else :
    print(' a == 4 é falso')
else:
  print(' O valor a == 2 é falso')
```

<div id='ifencadeado'/>

## if encadeado

```python 
# if composto: 
print('Digite um número de 1 a 4 ou número qualquer!')
a = int(input())
if (a == 2 ):
  print('if a == 2 true')
elif (a == 3):
  print('elif a == 3 true')
elif (a == 4):
  print('elif a == 4 é true')
else :
  print('if a == 2 e elif a == 3 e elif a == 4 são false')
```
<div id='condicionalifternario'/>

 ## Desvio condicional if ternário 
 
 ```python
 #exemplo:
 f = ( "Criança" if (idade < 12) else ("adolescente"  if (idade < 18) else ("adulto" if (idade < 60) else "Experiente")))
 print(f)
 ```
<div id='estruturafor'/>

 ## Estrutura for 
 
 o laço de repetiçâo for no python o incremento é interno, ou seja não é preciso declarar  o i++ , e para iniciar a contagem basta usar o método range(), exemplo:
 
 ```python 
 for i in range(0,10):
    print(i)
 ```
 e para mexer no incremento:
 
 ```python
 for i in range(10,0,-1):
      print(i)
 ```
<strong>Teste de mesa:</strong> ele vai fazer a contagem de 10 até 1

<div id='Leituraarraycomfor'/>

## Leitura array com for 
```python
array = ['0','1','2','3']
for x in array :
  print('indice:',x)
```


 
   
