## Subject
```
Expected Files: hidenp.c
Allowed functions: write
--------------------------------------------------------------------------------
Escribe un programa llamado hidenp que reciba dos cadenas y muestre un 1 seguido de un salto
de línea si la primera cadena está oculta en la segunda, de lo contrario muestra un 0 seguido
de un salto de línea. Sea s1 y s2 cadenas. Decimos que s1 está oculta en s2 si es posible
encontrar cada carácter de s1 en s2, en el mismo orden en que aparecen en s1. Además, la cadena
vacía está oculta en cualquier cadena.

Si el número de parámetros no es 2, el programa muestra un salto de línea.

Ejemplos:
$>./hidenp "fgex.;" "tyf34gdgf;'ektufjhgdgex.;.;rtjynur6" | cat -e
1$
$>./hidenp "abc" "2altrb53c.sse" | cat -e
1$
$>./hidenp "abc" "btarc" | cat -e
0$
$>./hidenp | cat -e
$
$>
--------------------------------------------------------------------------------
```



## Subject
```
Expected Files: hidenp.c
Allowed functions: write
--------------------------------------------------------------------------------
Write a program named hidenp that takes two strings and displays 1 followed by a newline if the first
string is hidden in the second one, otherwise displays 0 followed by a newline. Let s1 and s2 be strings.
We say that s1 is hidden in s2 if it's possible to find each character from s1 in s2, in the same order as
they appear in s1. Also, the empty string is hidden in any string. If the number of parameters is not 2,
the program displays a newline.
Examples :
$>./hidenp "fgex.;" "tyf34gdgf;'ektufjhgdgex.;.;rtjynur6" | cat -e
1$
$>./hidenp "abc" "2altrb53c.sse" | cat -e
1$
$>./hidenp "abc" "btarc" | cat -e
0$
$>./hidenp | cat -e
$
$>
--------------------------------------------------------------------------------
```
