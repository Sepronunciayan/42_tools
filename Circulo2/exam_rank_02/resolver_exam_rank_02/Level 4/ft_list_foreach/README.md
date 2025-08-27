## Subject
```
Expected Files: ft_list_foreach.c, ft_list.h
Allowed functions:
--------------------------------------------------------------------------------
Escribe una función que reciba una lista y un puntero a función, y aplique esta función a cada elemento de la lista. Debe declararse de la siguiente forma:
void ft_list_foreach(t_list *begin_list, void (*f)(void *));
La función apuntada por f se usará de la siguiente manera:
(*f)(list_ptr->data);
Debes usar la siguiente estructura y entregarla en un archivo llamado ft_list.h:
typedef struct s_list
{
struct s_list *next;
void *data;
} t_list;
--------------------------------------------------------------------------------
```

## Subject
```
Expected Files: ft_list_foreach.c, ft_list.h
Allowed functions:
--------------------------------------------------------------------------------
Write a function that takes a list and a function pointer, and applies this function to each element of the list. It must be declared as follows:
void ft_list_foreach(t_list *begin_list, void (*f)(void *));
The function pointed to by f will be used as follows:
(*f)(list_ptr->data);
You must use the following structure, and turn it in as a file called ft_list.h:
typedef struct s_list
{
struct s_list *next;
void *data;
} t_list;
--------------------------------------------------------------------------------
```
