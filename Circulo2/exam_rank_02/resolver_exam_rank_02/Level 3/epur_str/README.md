## Subject
```
Expected Files: epur_str.c
Allowed functions: write
--------------------------------------------------------------------------------
Escribe un programa que reciba una cadena y la muestre con exactamente un espacio entre
las palabras, sin espacios ni tabulaciones al principio o al final, seguido de un \n.
Una "palabra" se define como una parte de la cadena delimitada por espacios/tabulaciones, o por
el inicio/final de la cadena. Si el número de argumentos no es 1, o si no hay palabras
para mostrar, el programa muestra \n.

Ejemplo:
$> ./epur_str "vous voyez c'est facile d'afficher la meme chose" | cat -e
vous voyez c'est facile d'afficher la meme chose$
$> ./epur_str " seulement la c'est plus dur " | cat -e
seulement la c'est plus dur$
$> ./epur_str "comme c'est cocasse" "vous avez entendu, Mathilde ?" | cat -e
$
$> ./epur_str "" | cat -e
$
--------------------------------------------------------------------------------
```


## Subject
```
Expected Files: epur_str.c
Allowed functions: write
--------------------------------------------------------------------------------
Write a program that takes a string, and displays this string with exactly one space between
words, with no spaces or tabs either at the beginning or the end, followed by a \n.
A "word" is defined as a part of a string delimited either by spaces/tabs, or by the start/end
of the string. If the number of arguments is not 1, or if there are no words to
display, the program displays \n.

Example:
$> ./epur_str "vous voyez c'est facile d'afficher la meme chose" | cat -e
vous voyez c'est facile d'afficher la meme chose$
$> ./epur_str " seulement la c'est plus dur " | cat -e
seulement la c'est plus dur$
$> ./epur_str "comme c'est cocasse" "vous avez entendu, Mathilde ?" | cat -e
$
$> ./epur_str "" | cat -e
$
--------------------------------------------------------------------------------
```
