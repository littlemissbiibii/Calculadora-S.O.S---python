# Calculadora-S.O.S---python
★ Projeto introdutório em Python.

print('Bem-vindo(a) à calculadora S.O.S!')

print('Por favor, escolha a operação que deseja:')
print('1 = Soma')
print('2 = Subtração')
print('3 = Divisão')
print('4 = Multiplicação')

operacao = input('Digite o número da operação desejada: ')

num1 = float(input('Digite o primeiro número: '))
num2 = float(input('Digite o segundo número: '))

if operacao == "1":
    resultado = num1 + num2
    print("Resultado:", resultado)

elif operacao == "2":
    resultado = num1 - num2
    print("Resultado:", resultado)

elif operacao == "3":
    if num2 != 0:
        resultado = num1 / num2
        print("Resultado:", resultado)
    else:
        print("Não é possível dividir por zero.")

elif operacao == "4":
    resultado = num1 * num2
    print("Resultado:", resultado)

else:
    print("Operação inválida :(")
