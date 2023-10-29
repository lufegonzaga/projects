# projects/testcalculator

print("0. Soma")
print("1. Subtração")
print("2. Multiplicação")
print("3. Divisão")

print("Escolha uma operação:")
resp = input()

if resp == "0": 
    print("Você escolheu a operação de soma.")
    print("=================================")
    print("Qual o primeiro valor?")
    x = float(input())
    print("Qual o segundo valor?")
    y = float(input())
    print("CALCULANDO...")
    import time
    time.sleep(1)
    print("O resultado da sua soma é {}".format(x + y))
elif resp == "1":
    print("Você escolheu a operação de subtração.")
    print("=================================")
    print("Qual o primeiro valor?")
    x = float(input())
    print("Qual o segundo valor?")
    y = float(input())
    print("CALCULANDO...")
    import time
    time.sleep(1)
    print("O resultado da sua subtração é {}".format(x - y))
elif resp == "2":
    print("Você escolheu a operação de multiplicação.")
    print("=================================")
    print("Qual o primeiro valor?")
    x = float(input())
    print("Qual o segundo valor?")
    y = float(input())
    print("CALCULANDO...")
    import time
    time.sleep(1)
    print("O resultado da sua multiplicação é {}".format(x * y))
elif resp == "3":
    print("Você escolheu a operação de divisão.")
    print("=================================")
    print("Qual o primeiro valor?")
    x = float(input())
    print("Qual o segundo valor?")
    y = float(input())
    print("CALCULANDO...")
    import time
    time.sleep(1)
    print("O resultado da sua divisão é {}".format(x / y))
else:
    print("Você não escolheu uma operação válida.")
