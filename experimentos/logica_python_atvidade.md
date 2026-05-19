# Solução Atividade de fixação de lógica com Python
1. Solicite ao usuário dois números inteiros. O programa deve comparar os dois valores e exibir qual deles é o maior.

```Python
num1 = int(input("Digite o primeiro número: "))
num2 = int(input("Digite o segundo número: "))

if num1 > num2:
    print(f"O maior número é: {num1}")
else:
    print(f"O maior número é: {num2}")
```

---


2. Solicite ao usuário 1 número e informe se este é par ou ímpar.

```Python
num = float(input("Insira um número: "))
   
if num % 2 == 0:
	print("Número PAR")
else:
    print("Número IMPAR")
```

---


3. Solicite ao usuário o nome do estudante e 3 notas, retorne a média ponderada das notas (com pesos 1,1 e 2), o nome do estudante e se reprovado (media 6 aprovado).

```python
nome = input("Nome do estudante: ")
nota1= float(input("Nota 1: "))
nota2= float(input("Nota 2: "))
nota3= float(input("Nota 3: "))

#pesos
p1=1
p2=1
p3=2

#media ponderada
media = (nota1*p1 + nota2*p2 + nota3*p3) / (p1+p2+p3)

print(f"\nEstudante: {nome}")
print(f"Média: {media:.2f}")

if (media < 6):
  print("Situação: Reprovado")
else:
  print("Situação: Aprovado")
```

---


4. Leia o ano de nascimento de uma pessoa e o ano atual. Com base nisso, calcule a idade da pessoa e informe se ela é maior de idade (18 anos ou mais) ou menor de idade.

```Python
ano_nascimento = int(input("Ano de nascimento: "))
ano_atual = int(input("Ano atual: "))

idade = ano_atual - ano_nascimento
print(f"Esta pessoa tem ou completará: {idade} anos")

if idade < 18:
    print("Situação: Menor de idade")
else:
    print("Situação: Maior de idade")
```

---


5. Leia o salário atual de um funcionário e o percentual de reajuste. Calcule e exiba o valor do aumento e o novo salário após o reajuste.

```Python
salario = float(input("Salário atual: "))
percentual = float(input("Percentual de reajuste %: "))

percentual = percentual / 100
reajuste = salario * percentual
salario_atualizado = salario + reajuste

print(f"\n\nReajuste: R$ {reajuste:.2f}")
print(f"Salário atualizado: R$ {salario_atualizado:.2f}")
```

----


6. Leia a idade de duas pessoas e calcule a diferença absoluta de idade entre elas (sem exibir valores negativos).

```Python
idade1 = int(input("Idade 1: "))
idade2 = int(input("Idade 2: "))

diferenca = idade1 - idade2

if diferenca < 0:
    diferenca = diferenca * -1

print(f"Diferença: {diferenca} anos")
```

----


7. Leia o valor de um produto. Se o valor for maior que R$ 100,00, aplique um desconto de 10%. Caso contrário, aplique um desconto de apenas 5%. Exiba o valor do desconto calculado e o preço final que o cliente irá pagar.

```Python
valor_produto = float(input("Digite o valor do produto R$: "))

if valor_produto > 100:
    percentual = 0.10
else:
    percentual = 0.05

desconto = valor_produto * percentual
valor_final = valor_produto - desconto

print(f"Desconto aplicado: R$ {desconto:.2f}")
print(f"Valor final a pagar: R$ {valor_final:.2f}")
```

----


8. Solicite ao usuário que digite um nome de usuário e uma senha. O sistema deve verificar se o usuário é exatamente "admin" e se a senha é "1234". Se ambos estiverem corretos, exiba "Acesso liberado". Caso contrário, exiba "Acesso negado".

```Python
usuario = input("Digite o usuário: ")
senha = input("Digite a senha: ")

if usuario == "admin" and senha == "1234":
    print("Acesso liberado")
else:
    print("Acesso negado. Usuário ou senha incorretos.")
```

----


9. Solicite a distância total percorrida por um carro (em km) e o total de combustível gasto (em litros). Calcule o consumo médio do veículo (km/l). Se o consumo for menor que 10 km/l, exiba a mensagem "Situação: Consumo alto". Caso contrário, exiba "Situação: Consumo dentro do esperado".

```Python
distancia = float(input("Distância percorrida (em km): "))
litros = float(input("Combustível gasto (em litros): "))

consumo_medio = distancia / litros
print(f"Consumo médio: {consumo_medio:.2f} km/l")

if consumo_medio < 10:
    print("Situação: Consumo alto")
else:
    print("Situação: Consumo dentro do esperado")
```

---


10. Escreva um programa que receba do usuário uma distância em quilômetros (km). O programa deve calcular e exibir essa mesma distância convertida para duas unidades do sistema americano: jardas (yd) e milhas (mi).Utilize as seguintes fórmulas para o cálculo:
* Jardas (yd): $Jardas = Quilômetros \times 1093.61$
* Milhas (mi): $Milhas = \frac{Quilômetros}{1.60934}$

Exiba os dois resultados na tela com duas casas decimais.

```Python
# Solicitando a entrada do valor em quilômetros
km = float(input("Digite a distância em quilômetros (km): "))

# Realizando os cálculos de conversão
jardas = km * 1093.61
milhas = km / 1.60934

# Exibindo os resultados formatados
print(f"\n--- Resultado da Conversão para {km:.2f} km ---")
print(f"Distância em Jardas: {jardas:.2f} yd")
print(f"Distância em Milhas: {milhas:.2f} mi")
```
