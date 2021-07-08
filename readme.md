## Probando repositorio en GitGub
1
2
3
4
5
6
7
8
Gracias amigos :)
``` py
# Online Python compiler (interpreter) to run Python online.
# Write Python 3 code in this online editor and run it.
#********List of elements in pyton*********** Se sa la Frase quiero mas cervezas para la banda
def break_words(sentence):
    words = sentence.split(" ")
    return words
 
oracion = input("\nIntroduce una oracion: ")
palabras = break_words(oracion)
 
print("\n\nSe imprime las variables antes de ser modificadas\n")
print(oracion)
print(palabras)
 
#count retun the numers od elements with the especific value appear in the list
cantidad = palabras.count("la")
print("\nCantidad de veces que aparece 'la'en la lista: {}:", cantidad)
```