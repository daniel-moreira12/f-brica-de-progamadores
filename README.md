29\04

1- ANDROID
1-Symbian

2- GOOGLE PLAY STORES É UM DE APLICATIVO QUE GERENCIA OUTROS SOFTWARE
2- GITHUB
2- SAP
----------------------------------------------------------------
30\04

1- como a alteração na ordem das instruções de um algoritmo pode afetar o seu resultado final
R: Porque para conseguimos um resultado precisamos seguir uma sequência lógica, caso esquece de algo você
não iria conseguir chegar no resultado final.
 
2- Como podemos aplicar o conceito de sequência lógica na resolução de problemas cotidianos ou na automação de tarefas?
R: Bom vou citar um exemplo do Excel para você utilizar o Excel ele precisa de algoritmo para funcionar primeiro você precisa criar a planilha, segundo você precisa colocar a fórmula, terceiro selecionar as colunas e apertar enter.


3- passo a passo de como a ir a escola

primeiro você acorda 

segundo você toma café

terceiro você escova os dentes

quarto você toma banho

quinto você escolhe a roupa

sexto você coloca roupa

sétimo você sai de casa e tranca a porta

oitavo você faz o caminho para a escola

nono você entra na escola

décimo você senta no seu lugar e presta atenção na aula.
----------------------------------------------------------------
07/05

 O que é lógica de programação e por que ela é essencial para resolver problemas?
Lógica de programação é a habilidade de organizar sequências de instruções de forma que um computador possa executar tarefas específicas. Ela envolve raciocínio lógico, identificação de padrões e criação de passos (algoritmos) para resolver problemas.

💡 Por que é essencial?
Porque permite:

Analisar problemas com clareza;

Planejar soluções passo a passo;

Criar programas eficientes e sem erros.

2. O que são variáveis e qual a sua importância em um programa?
Variáveis são espaços na memória do computador usados para armazenar dados temporariamente durante a execução de um programa. Elas têm um nome e um valor que pode mudar (por isso o nome "variável").

💡 Importância:

Permitem armazenar e manipular dados;

Facilitam a reutilização de informações;

Tornam o código mais flexível e dinâmico.

3. Quais são as diferenças entre os tipos de variáveis (cadeia, inteiro, real e lógico)?
Aqui está um resumo dos principais tipos de variáveis e suas diferenças:

Tipo	Armazena	Exemplo	Usado para...
Inteiro (int)	Números inteiros	10, -5, 0	Contagem, índices, pontuação
Real (float ou double)	Números com casas decimais	3.14, -0.5	Cálculos com precisão decimal
Cadeia (string)	Texto (sequência de caracteres)	"Olá", "123"	Nomes, mensagens, senhas
Lógico (bool)	Verdadeiro ou falso	true, false	Condições, verificações, testes

-------------------------------------------------------------------------------------------

print(" Qual o nome do aluno:")
nome = input ()

print(" Qual a nota do aluno em português: ")
nota1 = input ()

print(" Qual a nota do aluno em Matemática: ")
nota2 = input ()

print(" Qual a nota do aluno em Filosofia: ")
nota3 = input ()

nota1 = int(nota1)

nota2 = int(nota2)
nota3 = int(nota3)

soma = nota1 + nota2 + nota3 
media = soma /3

print(" a nota do aluno é;" ,media)

------------------------------------------------------------------
08/05/2025

print ("Digite o primeiro Número: ")
valor1= input ()
print("Digite o segundo Número: ")
valor2= input ()

valor1=int (valor1)
valor2=int (valor2)
 
divisao = valor1 / valor2
multiplicacao = valor1 * valor2
subtracao = valor1 - valor2
 
print("A Divisão do seu cálculo é :" ,divisao)
print("A Multiplicação do seu cálculo é :" ,multiplicacao)
print("A Subtração do seu cálculo é;" ,subtracao)
------------------------------------------------------------------
Atividade 2

print (" Digite o valor total: ")
valor_total = input ()
valor_total = int (valor_total)

print (" Digite o valor da porcentagem: ")
porcentagem = input ()
porcentagem = int (porcentagem)

porcentagem = porcentagem / 100


valor_da_parte = valor_total * porcentagem

print(valor_da_parte)

----------------------------------------------------------------------------
09/05/2025

print (" Digite o valor da variável A: ")
a = int ( input () )
print(" Digite o valor da variável B:")
b = int ( input () )
print(" Digite o valor para a variável C: ")
c = int ( input () )

print("Comparações: ")
print("a > b and c == b =", a > b and c == b)
print("a < b or c > b =", a < b or c > b)
print("not a != b =", not a != b)

https://ler.amazon.com.br/kp/embed?linkCode=kpd&asin=B076H87LBW&tag=livrariapubli-20&reshareId=W3BTS10CKXMR95R3GTZG&reshareChannel=system

--------------------------------------------------------------------------------------------------------------------------------------------

13/05/2025

nome = input("Qual é o seu nome? ")
idade = int(input("Qual é a sua idade?"))
possui_carteira = input ("Possui carteira de motorista? \n (1-Sim \ 2-Não) ")

if idade>= 18:
    if possui_carteira == "1":
        print("Pode dirigir")
    else:
        print("Não pode dirigir")

else:
    print("Menor de idade")
--------------------------------------------------------------------------------------------------------------------------------------------------
19/05/2025

cotacao_dolar = 5

def real_dolar(real):
    return real / cotacao_dolar 

def dolar_real (dolar):
    return dolar * cotacao_dolar

opcao_usuario = input("Digite a opção que deseja:\n1) Conversor Dólar -> Real\n2) Conversor Real -> Dólar\n3) Sair do Programa\n")

if opcao_usuario == "1":
     dolares_usuario = float (input("Digite a quantidade de reais:"))
     print ("Sua resposta é:", dolar_real(dolares_usuario))
elif opcao_usuario == "2": 
    reais_usuario = float (input("Digite a quantidade de dolares:"))
    print ("Sua resposta é:", real_dolar(reais_usuario))
elif opcao_usuario == "3":
    print ("Saindo...")

else:
    print("Opção inválida.")
-----------------------------------------------------------------------------------------------------
senha, contador:
DANIEL
senha = 0
contador = 0
while senha != 12345:
    senha = int(input("Digite a sua senha "))
    if senha == 12345:
        print("Sua senha está correta")
   
    else:
        print("Sua senha está incorreta")
        contador = contador +1 
    if contador >= 2:
        print("Dica, Sua senha começa com 1,2...")

  ------------------------------------------------------------------------------------

 DANIEL 
 20/05/2025

 def somar (n1,n2):
    return n1 + n2

def multiplicacao (n3,n4):
    return n3 * n4
   
def divisao (n5,n6):
    return n5 / n6

def subtrair (n7, n8):
    return n7 - n8

numero1 = int(input("Digite o primeiro número:"))
numero2 = int(input("Digite o segundo número:"))

opcao_usuario = input("Digite a opção que deseja:\n1) Adição:\n2) Multiplicação:\n3) Divisão:\n4) Subtração:\n5) Sair do programa:\n")

if opcao_usuario == "1":
    print(somar(numero1,numero2))

elif opcao_usuario == "2":
    print(multiplicacao(numero1,numero2))

elif opcao_usuario == "3":
    print(divisao(numero1,numero2))

elif opcao_usuario == "4":
    print(subtrair(numero1, numero2))

else:
    print("Saindo...")
-----------------------------------------------------------------------=

stefane

def somar (n1,n2):
    return n1 + n2

def multiplicar (n1,n2):
    return n1 * n2

def subtrair (n1,n2):
    return n1 - n2

def dividir (n1,n2):
    return n1 / n2

numero1 =int(input("Digite o primeiro número:"))
numero2 =int(input("Digite o segundo número:"))

print ("Digite a opção que deseja:\n1)somar\n2)multiplicar\n3)subtrair\n4 dividir")
opcao = input()

if opcao== "1":
    print(somar(numero1 ,numero2))
elif opcao == "2":
     print(multiplicar(numero1 ,numero2))
elif opcao == "3":
    print(subtrair(numero1,numero2))
elif opcao == "4":
    print(dividir(numero1,numero2))










        


