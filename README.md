<h1 align="center">PYTHON <i>(Curso em Vídeo)</i></h1>
<p align="center">Resolvendo questões do curso de Python do Canal Curso em Vídeo.</p>

<h3>Desafio 01</h3>
<p>Crie um script python que leia o nome de uma pessoa e mostre uma mensagem de boas vindas de acordo com o valor digitado.</p>

```
nome = input('Qual seu nome? ')
print('Olá {}! Seja Bem vindo!'.format(nome))
```

<h3>Desafio 02</h3>
<p>Crie um script python que leia o dia, o mês e o ano de nascimento de uma pessoa e mostra uma mensagem com a data formatada.</p>

```
print('Informe sua data de nascimento:')
d = int(input('Dia: '))
m = input('Mês: ')
a = int(input('Ano: '))
print('Você nasceu no dia {} de {} de {}. Correto?'.format(d, m, a))
```

<h3>Desafio 03</h3>
<p>Crie um script python que leia dois números e mostra a soma entre eles.</p>

```
n1 = int(input('Digite um número: '))
n2 = int(input('Digite outro número: '))
s = n1 + n2
print('A soma entre esses dois números é: ' , s)
```
<hr>

<h3>Desafio 001</h3>
<p>Crie um programa que escreva "Olá, Mundo!" na tela.</p>

```
print('Olá, Mundo!")
```

<h3>Desafio 002</h3>
<p>Faça um programa que leia o nome de uma pessoa e mostre uma mensagem de boas-vindas.</p>

```
nome = input('Olá! Qual seu nome? ')
print('Seja bem-vindo {}, é um prazer conhecê-lo!' .format(nome))
```

<h3>Desafio 003</h3>
<p>Crie um programa que leia dois números e mostre a soma entre eles.</p>

```
n1 = int(input('Digite um número: '))
n2 = int(input('Digite outro número: '))
s = n1 + n2
print('A soma entre esses dois números é: ' , s)
```

<h3>Desafio 004</h3>
<p>Crie um programa que leia algo pelo teclado e mostre na tela o seu TIPO PRIMITIVO e todas as informações possíveis sobre ela (seus métodos).</p>

```
x = input('Digite algo: ')
print('O tipo primitivo deste valor é:' , type(x))
print('Esse valor é um número?' , x.isnumeric())
print('Esse valor tem somente espaços?' , x.isspace())
print('Esse valor é alfabético?' , x.isalpha())
print('Esse valor é alfanumérico?' , x.isalnum())
print('Esse valor está em MAIÚSCULAS?' , x.isupper())
print('Esse valor está em minúscula?' , x.islower())
print('Esse valor está capitalizado?' , x.istitle())
```

<h3>Desafio 005</h3>
<p>Faça um programa que leia um número inteiro, e mostre na tela seu sucessor e antecessor.</p>

```
x = int(input('Digite um número inteiro: '))
s = x + 1
a = x - 1

print('O número escolhido foi: {}\nSeu antecessor é: {}\n Seu sucessor é: {}' .format(x , a , s))
```

<h3>Desafio 006</h3>
<p>Crie um algoritmo que leia um número e mostre o seu dobro, triplo e raiz quadrada.</p>

```
x = int(input('Digite um número: '))
d = x * 2
t = x * 3
r = x ** (1/2)
print('O número escolhido foi: {}\nO dobro desse número é {}\nO triplo desse número é {}\nA raiz quadrada desse número é {}' .format(x , d , t, r))
```

<h3>Desafio 007</h3>
<p>Desenvolva um programa que leia as duas notas de um aluno, calcule e mostre sua média.</p>

```
n1 = float(input('Qual a nota do primeiro bimestre? '))
n2 = float(input('Qual a nota do segundo bimestre? '))

s = n1 + n2
m = s / 2

print('A soma dessas notas é igual a: ' , s)
print('A média das notas desse aluno é: ' , m)
```

<h3>Desafio 008</h3>
<p>Escreva um programa que leia um valor em metros e o exiba convertido em milímetros e centímetros.</p>

```
x = float(input('Digite um valor em metros: '))

mm = x * 1000
cm = x * 100

print('O valor informado foi: {} metro(s).\nConvertido em milímetros: {}\nConvertido em centímetros: {}' .format(x , mm , cm))
```
