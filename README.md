# reto_11
## 1). Consulte que hacen los siguientes métodos de strings en python: endswith, startswith, isalpha, isalnum, isdigit, isspace, istitle, islower, isupper. 
### *`endswith()`* 
- Es utilizado como un metodo de verificacion de contenido, su funcion es comprobar si el string terminac con un termino especificado 

Ejemplo: 

`"hola a todos mis amigos".endswith("amigos")` 
 devuelve un `True`

### *`startswith()`*
- Este es utilizado con el fin de verificar si la cadena comienza con un termino especificado (es como el endswith solo que con el comiezo jeje).

##### Ejemplo: 
`"voy a sacar 5 en el reto".startswith("voy")` 

devuelve un `True`.

### *`isalpha()`*
- Es utilizado con el fin de comprobar que todos los carceres de una cadena sean letras.

#### Ejemplo: 
`"tomate".isalpha()` 

devuelve `True`

por otro lado `"1013113112".isalpha()` 

devuelve `False`

### *`isalnum()`*
- Verifica si todos los caracteres de la cadena son letras o números.

#### Ejemplo: 
`"coco2017".isalnum()` devuelve `True`

mientras que `"pantera 1725".isalnum()` devuelve `False`

### *`isdigit()`*
- Este es el contrario a isalpha ya que este nos verific que todos los caracteres del string sean numeros, unicamente.

#### Ejemplo:
`"123".isdigit()` devuelve `True`, 

mientras que `"123a".isdigit()` devuelve `False`

### *`isspace()`*
- Este revisa que los caracteres de la cadena sen espacios en blanaco.

#### Ejemplo: 
`"    ".isspace()` nos devuelve `True`

### *`istitle()`*
- Verifica si la cadena está en formato de título, es decir, si la primera letra de cada palabra es mayuscula y el resto de letras son minusculas.

#### Ejemplo:
`"Hola Mundo".istitle()` regresa un `True`

### *`islower()`*
- Este comprueba que todos ls caracteres de la cadena sena minusculas.

#### Ejemplo: 
`"tubbiepapilla".islower()` devuelve `True`

### *`isupper()`*
- Este es el opuesto al anterior (islower) ya que este verifica si todos los caracteres de la cadena estan en mayusculas.

#### Ejemplo: `
"AAAAAAAAA".isupper()` devuelve `True`

mientras que `"oioioioioi".isupper()` devuelve `False`.
