# Examen.2 Del Parcial 1. Codgo Creado Por Ramirez Torres Angel Manuel De 3°W
- Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables: A, B y C respectivamente.
El algoritmo debe imprimir cual es el mayor y cual es el menor. Recuerde constatar que los tres valores introducidos por el teclado sean valores distintos. Presente un mensaje de alerta en caso de que se detecte la introducción de valores iguales.

print(" ")
print("-INSTRUCCIONES-")# Imprime las instrucciones del codigo 
print("Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables: A, B y C respectivamente.")
print("El algoritmo debe imprimir cual es el mayor y cual es el menor. Recuerde constatar que los tres valores introducidos por el teclado")
print("sean valores distintos. Presente un mensaje de alerta en caso de que se detecte la introducción de valores iguales. ")
print(" ")

a = input("Por favor digita el primer valor:    ")#Registra los valores ingresados 
b = input("Por favor digita el segundo valor:   ")#Registra los valores ingresados 
c = input("Por favor digita el tercer valor:    ")#Registra los valores ingresados 

a = float (a) #Convierte las variables en enteros o decimales 
b = float (b) #Convierte las variables en enteros o decimales
c = float (c) #Convierte las variables en enteros o decimales 

if a == b or b == c or a == c: #Si es el mismo numero pasa esto 
    print("Usaste uso dos o mas veces los mismos valores, por favor utiliza otros valores")
else: #De lo contrario encuentra el menor o el mayor 
    menor = min (a, b, c)
    mayor =  max (a, b, c)
    print("El valor mayor es :  ", mayor) #Nos da el numero mayor de los ingresados 
    print("El valor menor es : ", menor) #Nos da el numero menor de los ingresados


![image](https://github.com/user-attachments/assets/22d5e09f-281b-444c-b5ba-fa05cca109a6)
![image](https://github.com/user-attachments/assets/7d30aa7f-e507-4902-afa2-3fb984b965fb)
