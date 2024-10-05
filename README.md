# Calculadora
Edgar Gael Garcia Camacho 3-W

#Las opciones a elegir.

while True:

 print("0-salir del programa.")  
 
 print(" ") 
 
 print("1-Suma.")
 
 print(" ")
 
 print("2-Resta.")
 
 print(" ")
 
 print("3-Multiplicación.")
 
 print(" ")
 
 print("4-División.")
 
 print(" ")
 
 print("5-Elevado al cuadrado.")
 
 print(" ")
 
 print("6-Elevado al cubo.")
 
 print(" ")
 
 print("7-Raíz cuadrada.")
 
 print(" ")
 
 print("8-Factorial.")
 
 print(" ")
 
 print("9-Raices cubicas.")
 
 print(" ")
 
 print("10-seno.")
 
 print(" ")
 
 print("11-Coseno.")
 
 print(" ")
 
 print("12-Promedio.")
 
 print(" ")
 
 print("13-Porcentaje.")
 
 print(" ")
 
 print("14-Indice de masa corporal.")
 
 print(" ")

 import math

 opcion=int(input("Ingresa la opcion que deseas :"))#Te indica que introduscas una opcion.

 if opcion == 1:#"if" indica cual de las opciones de las que elegite se realizara.
 
 print(" ")
 
  num1=int(input("Ingrese el primer numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
   
  num2=int(input("Ingrese el segundo numero :"))#Te pide ingresar un numero para realizar la operacion.
    
  print(" ")
    
  r = num1 + num2 #La operacion realizandose.
    
  print(("El resultado es :"), r)#El mensaje que te arroja el resultado.
    
  print(" ")
 
elif opcion == 2:#"if" indica cual de las  opciones de las que elegite se realizara.

  print(" ")
  
  num1=int(input("Ingrese el primer numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
  
  num2=int(input("Ingrese el segundo numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
  
  r = num1 - num2 #La operacion realizandose.
  
  print(("El resultado es :"), r)#El mensaje que te arroja el resultado.
  
  print(" ")
 
 elif opcion == 3:#"if" indica cual de las  opciones de las que elegite se realizara.
 
  print(" ")
  
  num1=int(input("Ingrese el primer numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
  
  num2=int(input("Ingrese el segundo numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
  
  r = num1 * num2 #La operacion realizandose.
  
  print(("El resultado es :"), r)#El mensaje que te arroja el resultado.
  
  print(" ")
 
elif opcion == 4:#"if" indica cual de las  opciones de las que elegite se realizara.

  print(" ")
  
  num1=int(input("Ingrese el primer numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
  
  num2=int(input("Ingrese el segundo numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  print(" ")
  
  r = num1 / num2 #La operacion realizandose.
  
  print(("El resultado es :"), r)#El mensaje que te arroja el resultado.
  
  print(" ")
 
 elif opcion == 5:#"if" indica cual de las  opciones de las que elegite se realizara.
 
  print(" ")
  
  num1=int(input("Ingrese el primer numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  r = num1 * num1#La operacion realizandose.
  
  print("el resultado es :", r )#El mensaje que te arroja el resultado.
  
  print(" ")
 
 elif opcion == 6:#"if" indica cual de las  opciones de las que elegite se realizara.
 
  print(" ")
  
  num1=int(input("Ingrese el primer numero :"))#Te pide ingresar un numero para realizar la operacion.
  
  r = num1 * num1 * num1#La operacion realizandose.
  
  print("el resultado es :", r )#El mensaje que te arroja el resultado.
  
  print(" ")
 
 elif opcion == 7:#"if" indica cual de las  opciones de las que elegite se realizara.

  num1=int(input("Selecciona un numero :"))#Te pide ingresar un numero para realizar la operacion.
  
   print(" ")
   
   from math import sqrt
   
   r = sqrt(num1)#La operacion realizandose.
   
   print(" ")
   
   print("El resulatdo es :", r) #El mensaje que te arroja el resultado. 
   
   print(" ")
 
 elif opcion == 8:#"if" indica cual de las  opciones de las que elegite se realizara.
 
   num1 =int(input("Ingresa un numero :"))#Te pide ingresar un numero para realizar la operacion.
   
   print(" ")

  r=math.factorial(num1)#La operacion realizandose.

   print(" ")
   
   print("El resultad es :", r)#El mensaje que te arroja el resultado.
  
   print(" ")
 
 elif opcion == 9:#"if" indica cual de las  opciones de las que elegite se realizara.

  print(" ")
 
   num1=int(input("Ingresa un numero :"))
   
   r = math.pow(num1 ,1/3) #La operacion realizandose.
   
   print(" ")
   
   print("El resultado es :", r)#El mensaje que te arroja el resultado.
   
   print(" ")
 
 elif opcion == 10:#"if" indica cual de las  opciones de las que elegite se realizara.
   
   num1 = float(input("Ingresa el angulo de grados :"))
 
   print(" ")
   
   r = math.sin(math.radians(num1))#La operacion realizandose.
   
   print("El seno es :", r)#El mensaje que te arroja el resultado.
   
   print(" ")
 
 elif opcion == 11:#"if" indica cual de las  opciones de las que elegite se realizara.
 
   print(" ")
   
   num1 = float(input("Ingresa el angulo de grados :"))
   
   print(" ")
   
   r = math.cos(math.radians(num1))#La operacion realizandose.
   
   print("El seno es :", r)#El mensaje que te arroja el resultado.
   
   print(" ")
 
 elif opcion==12:#"if" indica cual de las  opciones de las que elegite se realizara.

   print("Promedio") 
   
   num1 =float(input("Ingresa la primer calificación :"))
   
   num2 =float(input("Ingresa la segunda calificación :"))
   
   num3 =float(input("Ingresa la tercer calificación :"))
   
   r = (num1 + num2 + num3 / 3)#La operacion realizandose.
   
   print("Tu promedio es :", r)#El mensaje que te arroja el resultado.
   
   print(" ")  
 elif opcion==13:#"if" indica cual de las  opciones de las que elegite se realizara.

   print("Porcentaje")
   
   num1=float(input("Escriba el porcentaje: "))
  
   num2=float(input("Escriba la cantidad de la que quiere que se saque ese porcentaje: "))
   
   r=num1/100#La operacion realizandose.
   
   p=r*num2
   
   print("El porcentaje de esa cantidad es de:", p)#El mensaje que te arroja el resultado.
   
   print(" ")
 
 elif opcion==14:#"if" indica cual de las  opciones de las que elegite se realizara.
 
   print("IMC")
   
   num1=float(input("Ingrese su altura (metros ejemplo 1.72): "))
   
   num2=float(input("Ingrese su peso (kg): "))
   
   r=num1*num1#La operacion realizandose.
   
   IMC=num2/r
   
   print("Su indice de masa corporal es: ", IMC)
   
   print(" ")
   
   print("Bajo peso: IMC < 18.5")
   
   print("Peso normal: IMC 18.5 - 24.9")
   
   print("Sobrepeso: IMC 25 - 29.9")
   
   print("Obesidad: IMC ≥ 30")
   
   print(" ")
 
 elif opcion==0:
 
   print("Saliste excitantemente......")
   
   break

 else:#"Else"te indicara cuando un valor no sea correcto y te arrojara el mensaje de abajo.
   
   print(" ")
   
   print("Ese no es un valor aceptable :( ")
