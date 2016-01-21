#1.5 Característiques dels llenguatges més difosos
##1.5.1 Característiques de la programació estructurada  
* **Claredat**
* **Teorema de l’estructura**  
**Seqüència**: instruccions executades successivament, una darrere l’altra  
**Selecció**: la instrucció condicional amb doble alternativa, de la forma:“si condició, llavors SentènciaA, sinó SentènciaB”  
**Iteració**: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi
* **Disseny descendent**  
El disseny descendent és una tècnica que es basa en el concepte de “divideix i
venceràs” per tal de resoldre un problema en l’àmbit de la programació.  Es tracta
de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un
nivell més abstracte i finalitzant en un nivell de detall
* **Programació modular**  
La divisió d’un programa en parts més manejables i independents anomenades mòduls  
Els mòduls es divideixen en:  
**Procediments**: són subprogrames que duen a terme una tasca determinada
i retornen 0 o més d’un valor.  
**Funcions**: són subprogrames que duen a terme una determinada tasca i
retornen un únic resultat o valor. 
* **Tipus abstractes de dades (TAD)**  
Els llenguatges de programació assumeixen un nombre determinat de tipus de
dades, que pot variar d’un llenguatge a un altre,aquests tipus de dades són anomenats 
**tipus de dades bàsics** en el context dels llenguatges de programació.
Fins fa uns anys, tota la programació es basava en aquest concepte de tipus i no
eren pocs els problemes que apareixien, lligats molt especialment a la complexitat
de les dades que s’havien de definir. Va aparèixer la possibilitat de poder definir
**tipus abstractes de dades**, on el programador pot definir un nou tipus de dades i
les seves possibles operacions.

##1.5.2 Característiques de la programació orientada a objectes  
L’orientació a objectes és un paradigma de construcció de programes basat en una abstracció del món real  
Un objecte és una combinació de dades (anomenades atributs) i mètodes (funcions i procediments) que ens permeten interactuar amb ell  
* **Abstracció**  
El proces d'abstracció consisteix en definir les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari.  
Es pot definir una classe com una descripció genèrica d’un grup d’objectes que comparteixen característiques comunes, les quals són especificades en els seus atributs i comportaments  
* **Encapsulació**  
Permet als objectes triar quina informació és publicada i quina informació és amagada a la resta dels objectes
Pot ser Public,protegit o privat  
* **Modularitat**  
Permet poder modificar les característiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l’aplicació   
* **Jerarquia**  
Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són l’herència i l’agregació  

* **El polimorfisme**  
És una característica que permet donar diferents formes a un mètode, ja sigui en la definició com en la implementació.  
La sobrecàrrega (overload) de mètodes consisteix a implementar diverses vegades un mateix mètode però amb paràmetres diferents  
