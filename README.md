#1
'''mercadoria = float(input())
compra = float(input())
total = (mercadoria*compra)
desconto = total*(0.9-(compra*0.01))
print(f'{total:.2f}')
print(f'{desconto:.2f}')'''

#2
'''emprego1 = float(input())
emprego2 = float(input())
casa = float(input())
total = emprego1 + emprego2 + casa
print(f'{total:.0f} minutos')'''

#3
'''polegadas = float(input())
centimetros = polegadas * 2.54
print(f'{centimetros:.3f}')'''
#4
'''natural = int(input())
if (natural%2)== 0: 
   impar = natural-1
   par = natural+2
   print(f'{impar:.0f} {par:.0f}')
else:
   impar = natural-2
   par = natural+1
   print(f'{impar:.0f} {par:.0f}')'''
#5
'''nota1 = float(input())
nota2 = float(input())
if  (nota1>=2) and ((nota1+nota2)/2)>= 6:
     print('aprovado')
elif (nota1>=2) and (nota1+nota2)>=2:
        print('talvez com a sub')
else:
 print('reprovado')'''
#6
'''dia_da_semana = str(input())
prazo_de_entrega = int(input())

if (dia_da_semana == 'domingo' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'domingo' and prazo_de_entrega == 1):
     print('sera entregue segunda')
elif(dia_da_semana == 'domingo' and prazo_de_entrega == 2):
     print('sera entregue terca')
elif(dia_da_semana == 'domingo' and prazo_de_entrega == 3):
     print('sera entregue quarta')
elif(dia_da_semana == 'domingo' and prazo_de_entrega == 4):
     print('sera entregue quinta')
elif(dia_da_semana == 'domingo' and prazo_de_entrega == 5):
     print('sera entregue sexta')
elif(dia_da_semana == 'domingo' and prazo_de_entrega == 6):
     print('sera entregue sabado')

if (dia_da_semana == 'segunda' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'segunda' and prazo_de_entrega == 1):
     print('sera entregue terca')
elif(dia_da_semana == 'segunda' and prazo_de_entrega == 2):
     print('sera entregue quarta')
elif(dia_da_semana == 'segunda' and prazo_de_entrega == 3):
     print('sera entregue quinta')
elif(dia_da_semana == 'segunda' and prazo_de_entrega == 4):
     print('sera entregue sexta')
elif(dia_da_semana == 'segunda' and prazo_de_entrega == 5):
     print('sera entregue sabado')
elif(dia_da_semana == 'segunda' and prazo_de_entrega == 6):
     print('sera domingo')


if (dia_da_semana == 'terca' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'terca' and prazo_de_entrega == 1):
     print('sera entregue quarta')
elif(dia_da_semana == 'terca' and prazo_de_entrega == 2):
     print('sera entregue quinta')
elif(dia_da_semana == 'terca' and prazo_de_entrega == 3):
     print('sera entregue sexta')
elif(dia_da_semana == 'terca' and prazo_de_entrega == 4):
     print('sera entregue sabado')
elif(dia_da_semana == 'terca' and prazo_de_entrega == 5):
     print('sera entregue domingo')
elif(dia_da_semana == 'terca' and prazo_de_entrega == 6):
     print('sera entregue segunda')


if (dia_da_semana == 'quarta' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'quarta' and prazo_de_entrega == 1):
     print('sera entregue quinta')
elif(dia_da_semana == 'quarta' and prazo_de_entrega == 2):
     print('sera entregue sexta')
elif(dia_da_semana == 'quarta' and prazo_de_entrega == 3):
     print('sera entregue sabado')
elif(dia_da_semana == 'quarta' and prazo_de_entrega == 4):
     print('sera entregue domingo')
elif(dia_da_semana == 'quarta' and prazo_de_entrega == 5):
     print('sera entregue segunda')
elif(dia_da_semana == 'quarta' and prazo_de_entrega == 6):
     print('sera entregue terca')

if (dia_da_semana == 'quinta' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'quinta' and prazo_de_entrega == 1):
     print('sera entregue sexta')
elif(dia_da_semana == 'quinta' and prazo_de_entrega == 2):
     print('sera entregue sabado')
elif(dia_da_semana == 'quinta' and prazo_de_entrega == 3):
     print('sera entregue domingo')
elif(dia_da_semana == 'quinta' and prazo_de_entrega == 4):
     print('sera entregue segunda')
elif(dia_da_semana == 'quinta' and prazo_de_entrega == 5):
     print('sera entregue terca')
elif(dia_da_semana == 'quinta' and prazo_de_entrega == 6):
     print('sera entregue quarta')


if (dia_da_semana == 'sexta' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'sexta' and prazo_de_entrega == 1):
     print('sera entregue sabado')
elif(dia_da_semana == 'sexta' and prazo_de_entrega == 2):
     print('sera entregue domingo')
elif(dia_da_semana == 'sexta' and prazo_de_entrega == 3):
     print('sera entregue segunda')
elif(dia_da_semana == 'sexta' and prazo_de_entrega == 4):
     print('sera entregue terca')
elif(dia_da_semana == 'sexta' and prazo_de_entrega == 5):
     print('sera entregue quarta')
elif(dia_da_semana == 'sexta' and prazo_de_entrega == 6):
     print('sera entregue quinta')


if (dia_da_semana == 'sabado' and prazo_de_entrega == 0):
    print('chega hoje!')
elif (dia_da_semana == 'sabado' and prazo_de_entrega == 1):
     print('sera entregue domingo')
elif(dia_da_semana == 'sabado' and prazo_de_entrega == 2):
     print('sera entregue segunda')
elif(dia_da_semana == 'sabado' and prazo_de_entrega == 3):
     print('sera entregue terca')
elif(dia_da_semana == 'sabado' and prazo_de_entrega == 4):
     print('sera entregue quarta')
elif(dia_da_semana == 'sabado' and prazo_de_entrega == 5):
     print('sera entregue quinta')
elif(dia_da_semana == 'sabado' and prazo_de_entrega == 6):
     print('sera entregue sexta')'''

