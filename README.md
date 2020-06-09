# Lista de exercicios Python

[Lista De Exercicios - Python Brasil][1]

## Praticando com Python

Neste portifólio contém a resolução de uma lista exercicios utilizando a linguagem Python, os arquivos que contém a palavra **"extra"** são melhorias que desenvolvi com base na necessidade que encontrei com base no exercicio proposto.

## Exemplo: 
 Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês. 
### Resolução do exercicio:
 ```python
valor_hora = int(input('Quanto você ganha por hora trabalhada? '))
hora_trabalho_mes = int(input('Quantas horas você trabalha por mês? '))
dias_trabalho_mes = int(input('Quantos dias trabalhou durante o mês? '))
hora_salario = valor_hora * hora_trabalho_mes
salario = hora_salario * dias_trabalho_mes

print('Seu salário em um mês é de:', salario)
```
### Melhoria:
Descobrir o valor da hora trabalhada com base no salário:
```python
salario = float(input('Informe seu salario: '))
hora_trabalho = int(input('Informe as horas trabalhadas durante o mês: '))
dias_trabalho = int(input('Informe a quantidade de dias trabalhados no mês:'))


valor_hora = salario / dias_trabalho / hora_trabalho

print('Seu valor por hora trabalhada é:', valor_hora)
```

