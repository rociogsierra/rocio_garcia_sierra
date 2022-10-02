# rocio_garcia_sierra

https://github.com/rociogsierra/rocio_garcia_sierra.git

# ejercicio 1

def tenercadena(cadena_de_texto):
#definimos la función
#según el enunciado, para voltear una cadena usamos [::-1]
voltearcadena = cadena_de_texto[::-1]
voltear_cadena_de_texto = voltearcadena.split(",")
Nota = split_cadena_de_texto[0]
NombreApellido = split_cadena_de_texto[1]
#esto debería de resetear y voltear la cadena
print ("{} ha sacado un {} de nota".format(NombreApellido,Nota))
cadena_de_texto = "zeréP nauJ,01"
tenercadena(cadena_de_texto)
    
    
# ejercicio 2    

def escribe_numero(numero):
numero = int(input())
print numero
#creamos una función para devolver un número
def algoritmo():
numero_magico = 12345679
numero_usuario = escribe_numero(numero = "Debe ser entre 1 y 9")
numero_usuario = 9 * numero_usuario 
numero_magico = numero_usuario * numero_magico
return numero_magico
algoritmo()


# ejercicio 3

def elementos_repetidos(lista_1, lista_2):
lista_1 = ['h','o','l','a',' ', 'm','u','n','d','o']
lista_2 = ['h','o','l','a',' ', 'l','u','n','a']
#definimos la tercera lista
lista_3 = [1]
for letra in lista_1:
for letra_repetida in lista_2:
if (letra = letra_repetida) and (letra_repetida not in lista_3)
return lista_3
print (elementos_repetidos(lista_1,lista_2))


# ejericio 4

#he tratado de realizar el ejercicio de la forma en que lo he comprendido, por otra parte, no sé si lo he comprendido de forma correcta y tampoco sabía muy bien qué datos usar ya que el enunciado del ejercicio no menciona las tareas que son ni cuantas tareas son. 

def tareas_por_prioridad(tareas, número_de_orden):
def por_orden(número_de_orden):
return número_de_orden[1]
lista_de_tareas = []
lista_de_tareas = sorted(número_de_orden, key = por_orden, prioridaddeorden = True)

lista_de_tareas.sort(tareas, número_de_orden)
#no sé si estoy usando bien la funcion .sort() propuesta en el enunciado
print(tarea)

tareas = ["tarea_1", "tarea_2", "tarea_3", "tarea_4", "tarea_5", "tarea_6"]
número_de_orden = ["1", "2", "3", "4", "5", "6"]

tareas_por_prioridad(tareas, número_de_orden)



# ejercicio 5

import matplotlib
import sys

def descomposicion(number):
#definiremos lo que son las unidades, decenas, centenas y miles
unidades = number % 10
decenas = number % 100 // 10
centenas = number % 10000 // 1000
miles = number % 1000
print ("000" + str(unidades))
print("0" + str(decenas))
print("00" + str(centenas))
print (str(miles))
tareas = sys.tareas

if len(sys.tareas)> 1:
number = int (sys.tareas [1])
return descomposicion(number)
else:
break


# ejercicio 6

def separar(lista):
pares = []
impares = []
for num in lista:
if num (num % 2) == 0:
pares.append(num)
else:
impares.append(num)
pares.sort
impares.sort
return pares
return impares

#definimos la lista 
lista = [6,5,2,1,7]
impares, pares = separar(lista)
print(impares)
print(pares)


# ejercicio 7

def agregar_una_vez(lista,el):
if el in lista:
try:
print ValueError
except ValueError as err:
print ("el elemento está duplicado y no puede añadirse" + str(el))
else:
lista.append(el)
return lista

lista = [10, -2]
el = "Hola"

agregar_una_vez(lista, el)
