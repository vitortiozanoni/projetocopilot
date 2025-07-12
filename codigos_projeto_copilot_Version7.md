# Códigos do Projeto Copilot

Este arquivo reúne os principais códigos desenvolvidos durante o projeto apresentado na DIO. 

Abaixo você pode adicionar, organizar e documentar seus scripts, funções e exemplos práticos.

---

## Exemplo 1

```python
# Exemplo simples de concatenação de informações recebidas via input

# Solicita a primeira informação ao usuário
info1 = input("Digite a informação 1: ")

# Solicita a segunda informação ao usuário
info2 = input("Digite a informação 2: ")

# Concatena as duas informações
resultado = info1 + " " + info2

# Exibe o resultado na tela
print("Você digitou:", resultado)
```

---

## Exemplo 2

```python
# Solicita uma string e um número inteiro como entrada
texto = input("Digite uma string: ")
quantidade = int(input("Digite um número inteiro: "))

# Retorna a string repetida pelo número informado
resultado_repetido = texto * quantidade

# Exibe o resultado na tela
print("Resultado:", resultado_repetido)
```

---

## Exemplo 3

```python
# Solicita duas entradas de números inteiros
num1 = int(input("Digite o primeiro número inteiro: "))
num2 = int(input("Digite o segundo número inteiro: "))

# Realiza operações matemáticas simples
soma = num1 + num2
subtracao = num1 - num2
multiplicacao = num1 * num2

# Para evitar divisão por zero
if num2 != 0:
    divisao = num1 / num2
else:
    divisao = "Indefinida (divisão por zero)"

# Exibe todos os resultados
print("Soma:", soma)
print("Subtração:", subtracao)
print("Multiplicação:", multiplicacao)
print("Divisão:", divisao)
```

#FIM