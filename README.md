# Backend-Development - Docker + Python
### Codes that we reproduce on the 1a class of backend development 

Cadastro</p> 

````
print('Cadastro de veículos\n')
input('Digite o nome do veículo que deseja cadastrar: ')
input ('Digite o ano desde veículo: ')
nome_do_veiculo = input('Digite o nome do veículo: ')
ano_do_veiculo = input('Digite o ano deste veículo:' )
print(f'nome_do_veiculo,ano_do_veiculo')
````

Funções
````
#funcoes para validar cpf, funcoes para a compra ser finalizada,
#funcoes para ver se o parcelamento pode ser realizado 
#return é a resposta 

def soma_com_argumentos_e_retorno(a, b):
    print (a > b)

resposta = soma_com_argumentos_e_retorno(40, 2)
print(resposta)
````


Habilitação 
````
#instruções para o código, use o terminal para interagir 
print ('Verifica quem pode dirigir\n') #Esse valor \n representa uma quebra de linha

idade = int(input('Digite uma idade: ')) #quando colocamos um input, ele espera numeros, não letras
#não se usa input('Digite a idade: ') 

if idade >= 18:
    print('pode dirigir')
else:
    print('Não pode dirigir')

#a indentaçao do código é importante 
#sempre que se executa a função input se espera uma string
#em alguns momentos será possíve
#para numeros decimais se usa o ponto. exemplo: 1.75
#uma das conversão
````


Imc
````
print('IMC\n')
peso = float(input('Digite o peso: '))
altura = float(input('Digita a altura: '))
imc =  (peso / altura ** 2) #acrescentando o round para arredondar os valores 
imc = round(imc, 2)
print(f'\n0 IMC é {imc}') # o f' é para colocar uma variável dentro de um texto, são as f'strings
````


Número aleatório
````
import random 
random.seed(42)
print(random.random())
print(random.randint(1, 10))
print(random.randint(1, 10))
print(random.randint(1, 10))
print(random.randint(1, 10))
````

Número secreto
````
#escolha um número aleatório
#entre 1 e 5
#recebe um chute
#se for igual ao numero aleatório = acertou
#senão, quase, o numero secreto era {numero_secreto}

print('Boas vindas ao jogo do número secreto\n')
numero_secreto = random.randint(1, 5)
chute = input ('Escolha um número entre 1 e 5')
if chute == numero_secreto:
    print(Acertou)
else: 
    print(f'Quase... o número era {numero_secreto}')
````


Número secreto

````
#escolha um número aleatório
#entre 1 e 5
#recebe um chute
#se for igual ao numero aleatório = acertou
#senão, quase, o numero secreto era {numero_secreto}

print('Boas vindas ao jogo do número secreto\n')
numero_secreto = random.randint(1, 5)
chute = input ('Escolha um número entre 1 e 5')
if chute == numero_secreto:
    print(Acertou)
else: 
    print(f'Quase... o número era {numero_secreto}')
````

Operadores matemáticos
````
#operadores matemáticos
#essa primeira parte entre aspas é o texto e a segunda é o cálculo
#sempre que quisermos executar u
print("A operação de soma é 1+1=",1+1)

#Subtração
#Essa conta entre aspas não tem um valor    

print('1-1=', 3-2)

#Multiplicação
print(7*8)

#divisão
print('30 dividido por 5 =''', 30/5)

#módulo é o resto da divisão 
print('10/3=1', 10%4)

#Exponenciação
print('2 ao cubo', 2**3)

#comparação
print('Comparação (igual) 5==5', 5==5)
print('comparação (diferente) 3!=5', 3!=5)
print('comparação(maior que)42 > 5', 42 > 5)
print('comparação (maior ou igual) 3>=3', 3>=3)
print('comparação (menor ou igual) 5 <=3', 5<=3 )
````

Sol na praia
````
sol_na_praia = True
chovendo = False
print((sol_na_praia and chovendo)) or (not sol_na_praia or not chovendo) 
````


Tipos booleanos
````
#e ou ou 

print(True and True)
print(True and False) #tudo vai ser falso
print(False and False)

#or só vi funcionar se uma das expressões seja verdadeira 
print(True or False)
print(True or True)
print(False or True)
````

Tipos de dados 
````
# em json é sempre uma chave um valor 
print(type('hello world')) #string
print(type(True)) #booleana
print(type(3)) #inteiro
print(type(10/3)) #float #sempre tem um ponto
print(type({'nome': 'nadja pereira'})) #chave:valor #usado para verificar se a idade é correpsondente, por example
````

