# Exercícios com funções


# Retorne o total para uma variável e mostre o valor
# da variável.

# Crie uma função que multiplica todos os argumentos não nomeados recebidos
def multiplicador(*args):
    total = 1
    for numero in args:

        total*=numero


    return f" {args} Total = {total}"

# Retorne o total para uma variável e mostre o valor da variável
multiplicacao1_1 = multiplicador(1,2,3,4,5,6,7,8)
print(multiplicacao1_1)
