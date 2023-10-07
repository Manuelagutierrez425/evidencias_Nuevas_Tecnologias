<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

lista = [1,2,3,4,5,6,7,8,9,10]
print(lista)
lista.sort()
print(lista)
lista.reverse()
print(lista)
print(lista[9])
print(lista[0])
print(lista.count(5))
lista.remove(5)
print(lista)
lista.append(11)
print(lista)

Tuplas:

tupla = ("Hola", "Mundo", "Python")
print(tupla)
#no se puede ordenar
print(tupla[0])
print(tupla[2])
len(tupla)
print(len(tupla))
lista = list(tupla)
lista[1] = ' '
print(lista)
lista[1] = 'Hola'
tupla = tuple(lista)
print(tupla)

Conjuntos:

conjunto = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
print(conjunto)
conjunto.add(11)
print(conjunto)
conjunto.remove(5)
print(conjunto)
len(conjunto)
print(5 in conjunto)
print(11 in conjunto)
conjunto2 = {"Hola", "Mundo", "Python"}
print(conjunto2)
print("Hola" in conjunto2)
print("Mundo" in conjunto2)

Diccionarios:

diccionario = {
    'Lunes': 1,
    'Martes': 2,
    'Miercoles': 3,
    'Jueves': 4,
    'Viernes': 5,
    'Sabado': 6,
    'Domingo': 7}
print(diccionario)
print(diccionario.get('Lunes'))
del diccionario['Lunes']
print(diccionario)




