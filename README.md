def main():
    # Leia as entradas do usuário
    ativo1 = input("Qual o nome do ativo 1? ")
    quantidade1 = float(input("Quantas unidades do ativo 1 você possui? "))
    preço1 = float(input("Qual o preço de compra do ativo 1? "))
    ativo2 = input("Qual o nome do ativo 2? ")
    quantidade2 = float(input("Quantas unidades do ativo 2 você possui? "))
    preço2 = float(input("Qual o preço de compra do ativo 2? "))

    # Calcule o preço médio
    preço_médio = (quantidade1 * preço1 + quantidade2 * preço2) / (quantidade1 + quantidade2)

    # Exiba o preço médio
    print("Preço médio:", preço_médio)

if __name__ == "__main__":
    main()
