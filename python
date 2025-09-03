# Desafio de Programação: Calculadora de Desafios

def desafio1():
    print("Desafio 1: Descubra se um número é par ou ímpar")
    numero = int(input("Digite um número: "))
    if numero % 2 == 0:
        print("✅ O número é par!")
    else:
        print("❌ O número é ímpar.")

def desafio2():
    print("\nDesafio 2: Calcule a média de 3 números")
    numeros = []
    for i in range(1, 4):
        n = float(input(f"Digite o número {i}: "))
        numeros.append(n)
    media = sum(numeros)/3
    print(f"✅ A média dos números é {media}")

def desafio3():
    print("\nDesafio 3: Transforme temperatura Celsius para Fahrenheit")
    celsius = float(input("Digite a temperatura em °C: "))
    fahrenheit = (celsius * 9/5) + 32
    print(f"✅ {celsius}°C equivalem a {fahrenheit}°F")

def menu():
    while True:
        print("\n--- Menu de Desafios ---")
        print("1 - Par ou Ímpar")
        print("2 - Média de 3 números")
        print("3 - Celsius para Fahrenheit")
        print("0 - Sair")
        escolha = input("Escolha um desafio: ")

        if escolha == "1":
            desafio1()
        elif escolha == "2":
            desafio2()
        elif escolha == "3":
            desafio3()
        elif escolha == "0":
            print("Saindo do programa. Até mais!")
            break
        else:
            print("Opção inválida. Tente novamente.")

# Executa o menu principal
menu()
