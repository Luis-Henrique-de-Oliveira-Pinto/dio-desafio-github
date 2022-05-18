# Repositório do Desafio de Projeto sobre Git/GitHub da Dio
Desafio do Projeto sobre GitHub Bootcamp do Carrefour / Dio - Minha calculadora em Python

endereço calculadora criada por Luis Henrique de Oliveira Pinto
https://colab.research.google.com/drive/1c4gbZ_LekZHbAXFiB7zC0dLHWudESm7_?hl=pt_BR#scrollTo=qnYFdxfJB3IV&uniqifier=1


# P5#
#Projeto Calculadora - Projeto 100% criado por mim


operacao = "continuar"

while(operacao == "continuar"):
operacao = input("Qual operação você deseja realizar? soma, subtrair, multiplicar, dividir, potencia (de dois), raiz (quadrada), continuar ou sair? ")

#if(operacao == "continuar"):
   


  if (operacao == "soma"):
      somaValor1 = input("qual o primeiro número da soma? ")
      somaValor1 = float(somaValor1)
      somaValor2 = input("Qual o segundo número da soma? ")
      somaValor2 = float(somaValor2)
      TotalSoma = (somaValor1) + (somaValor2)
      print("O total da soma é: ", TotalSoma)

  elif(operacao == "subtrair"):
      subValor1 = input("qual o primeiro número da subtração? ")
      subValor1 = float(subValor1)
      subValor2 = input("Qual o segundo número da subtração? ")
      subValor2 = float(subValor2)
      TotalSubtracao = (subValor1) - (subValor2)
      print("O resultado da subtração é: ", TotalSubtracao)

  elif(operacao == "multiplicar"):
      MultiValor1 = input("qual o primeiro número da multiplicação? ")
      MultiValor1 = float(MultiValor1)
      MultiValor2 = input("Qual o segundo número da multiplicação? ")
      MultiValor2 = float(MultiValor2)
      Total_Multiplicacao = (MultiValor1) * (MultiValor2)
      print("O resultado da multiplicação é: ", Total_Multiplicacao)

  elif(operacao == "dividir"):
      Div_Valor1 = input("qual o primeiro número da divisão? ")
      Div_Valor1 = float(Div_Valor1)
      Div_Valor2 = input("Qual o segundo número da divisão? ")
      Div_Valor2 = float(Div_Valor2)
      Total_Divisao = (Div_Valor1) / (Div_Valor2)
      print("O valor da divisão é: ", Total_Divisao)

  elif(operacao == "potencia"):
      Potenciacao = input("Entre com o número que você deseja saber o quadrado ")
      Potenciacao = float(Potenciacao)
      Potenciacao = Potenciacao **2
      print("O resultado da potênciação é: ", Potenciacao)

  elif(operacao == "raiz"):
      Raiz = input("Informe o número que você deseja saber a raiz quadrada ")
      Raiz = float(Raiz)
      Raiz = math.sqrt(Raiz)
      print("o resultado da raiz quadrada é: ", Raiz)

   #elif(operacao == "continuar"):
    #  continuar = input("Escolha uma opção: continuar ou sair")
    #  continuar == str("continuar")
    #  continuar == continuar

  elif(operacao == "sair"):
      print("Obrigado por utilizar nossos serviços. Até a próxima!")

  elif(operacao == "continuar"):
      operacao = "continuar"
   


  else:
      print("Operação não reconhecida!") 


