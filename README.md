Este es mi primer programa un poco avanzado soy un novato en python con algo de esfuerzo se pudo lograr terminar el proyecto [t-cryptography].
A continuacion les dejare informacion del funcionamiento de cada cifrado...

BlackCode:
"Este script fue creado el dia 10/09/20 principalmente fue"
creado por la necesidad del anonimato al compartir algun 
mensaje se baso principalmente de la clave murcielago y 
fue modificado a mis necesidades y gustos, a continuación
mostrare la tabla que define graficamente el codifo BlackCode

-   b    |   ,   <   °   &   4   .   2   $   +   3   %    *   ¬   =   ~   /   ¿   1   (   5   )   9   7      

A   B   C    D   E   F   G   H   I   J   K   L   M   N    O   P   Q   R   S   T   U   V   W   X   Y    Z  


Base64:
Su informacion es un poco extensa, dejare una pagina web que 
detalla el funcionamiento de Base64. https://cutt.ly/XfJ8rRS
El algoritmo de codificación Base64 no es un algoritmo de cifrado, se decodifica fácilmente y, por lo tanto, no debe utilizarse como un método de cifrado seguro. No utilice esta técnica para proteger los datos confidenciales, por lo que debe utilizar métodos de cifrado seguros.

Binario:
Bien la mayoria conoce el codigo binario el de los "0" y "1".
al igual que Base64 este no es un cifrado, por lo cual este se decodifica facilmente,
pero al igual que base64 puede utilizarse de mil maneras sin problema alguno.
Para mas informacion dejo esta pagina web. https://cutt.ly/HfJ8gr3

ROT:
En terminos de criptografia este algoritmo es uno de los mas utilizados al igual que Base64 y Binario,
algo en contra de ROT es que es un cifrado un poco debil por asi decirlo, a continuacion mostrare el funcionamiento
de este: La palabra "ROT" significa rotar lo cual el abecedario se compone de de 26 letras, este cifrado funciona de
esta manera en el programa que cree hay una opcion que te dice ¿Que ROT necesita?, ahi tienes la opcion de poner un
numero del 1 al 25 un ejemplo seria. La letra "a" y selecciono el ROT "3" este daria como resultado la letra [d] por que 
roto 3 lugares despues de la "a" que fue la letra que seleccionamos..

Fernet:
Fernet o tambien conocido como Cifrado simetrico.
Fernet garantiza que un mensaje cifrado no puede ser manipulado o leído sin la clave. 
Fernet es una implementación de criptografía autenticada simétrica (también conocida como "clave secreta").
Fernet también tiene soporte para implementar la rotación clave a través de MultiFernet.
En mi opinion Fernet es el cifrado mas seguro ya que este encripta texto y el receptor no podra saber que es lo
que dice a menos que este cuente con la clave o (key). Sin duda este se lleva el lugar al mejor cifrado por ser el mas 
seguro y practico.


[NOTA EXTRA]
se que el script puede tener algunos fallos que no note, o tal vez pudo ser mejor pero me esforce y espero
les guste para poder mejorarlo e implementar mas a futuro.
