# Examen.2 Del Parcial 1. Codgo Creado Por Ramirez Torres Angel Manuel De 3°W
- Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables: A, B y C respectivamente.
El algoritmo debe imprimir cual es el mayor y cual es el menor. Recuerde constatar que los tres valores introducidos por el teclado sean valores distintos. Presente un mensaje de alerta en caso de que se detecte la introducción de valores iguales.

print(" ")
print("-INSTRUCCIONES-")# Imprime las instrucciones del codigo 
print("Desarrolle un algoritmo que permita leer tres valores y almacenarlos en las variables: A, B y C respectivamente.")
print("El algoritmo debe imprimir cual es el mayor y cual es el menor. Recuerde constatar que los tres valores introducidos por el teclado")
print("sean valores distintos. Presente un mensaje de alerta en caso de que se detecte la introducción de valores iguales. ")
print(" ")

print(" ")
d = "Examen del primer parcial:" #Se declara la variable 'd'
a = "/ Alumno: Ramirez Torres Angel Manuel"#Se declara la variable 'a'
b = "/ Grado y Grupo: 3°W"#Se declara la variable 'b'
c = "/ Mi numero de contro es: 1206"#Se declara la variable 'c'
espacio = (" ")#Se declara la variable 'espacio'

info = d +espacio + a + espacio + b + espacio + c #Aqui se juntan los valores (d, a, b, c, espacio) para crear una sola variable 
print (info)#Muestra el contenido de la variable 'info'
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


![image](https://github.com/user-attachments/assets/9be8f47d-f95f-4b75-8215-f81cebc6bcbf)
![image](https://github.com/user-attachments/assets/22f35e95-a487-4308-af1e-9eed9119f969)


