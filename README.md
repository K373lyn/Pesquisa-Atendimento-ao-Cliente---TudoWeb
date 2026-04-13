# Pesquisa-Atendimento-ao-Cliente---TudoWeb
Pesquisa Atendimento ao Cliente - TudoWeb

´´
qtd_excelente = 0
qtd_ruim = 0

for i in range(1, 51):
    print(f"\nEntrevistado {i}")
    
    nome = input("Digite o nome: ")
    idade = int(input("Digite a idade: "))
    
    print("Opinião sobre o atendimento:")
    print("1 - EXCELENTE")
    print("2 - BOM")
    print("3 - RUIM")
    
    opiniao = int(input("Digite a opção (1/2/3): "))
    
    if opiniao == 1:
        qtd_excelente += 1
    elif opiniao == 3:
        qtd_ruim += 1
    elif opiniao == 2:
        pass 
    else:
        print("Opção inválida!")


print("\n===== RESULTADO DA PESQUISA =====")
print(f"Quantidade de respostas EXCELENTE: {qtd_excelente}")
print(f"Quantidade de respostas RUIM: {qtd_ruim}")
´´
