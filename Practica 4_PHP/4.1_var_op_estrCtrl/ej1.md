# Ejercicio 1: identificar

## Variables y su tipo:
  - *$a*: es booleana
  - *$b*: es string
  - *$c*: es string
  - *$d*: es number
  - *$f*: es number


## Operadores:
  - *=*: asignacion

  - *: multiplicacion

  - *+=*: al valor inicial de la variable le suma una determinada cantidad

  - *?*: es un operador unario el cual equivale a una sentencia "if" (ej: **$a?**) (el cual pregunta si la var a es verdadera)

  -*:*: es un operador binario el cual equivale a un else (ej: **$d : $d.3**) (si la condicion anterior es verdadera, entonces se ejecuta la sentencia de la izquierda ($d), y sino se ejecuta la de la der ($d.3))


  ## Funciones y parametros:
  - *doble($i)*: tiene como parametro a i, el cual es un number, y devuelve el doble del parametro. Es una funcion definida por el usuario.

  - *echo*: esta funcion muestra en consola lo que tiene a la derecha. Es una funcion del lenguaje. Ej: echo $a (muestra en consola el valor de la var a, el cual es true)

  - *gettype()*: esta funcion obtiene el tipo de dato de la variable que le enviemos por parametro. Es propia del lenguaje. Ej: gettype($a) devuelve boolean

  - *is_string()*: determina si el parametro enviado es un string o no, devolviendo true o false. Es propia del lenguaje.

  - *is_string()*: determina si el parametro enviado es un entero o no, devolviendo true o false. Es propia del lenguaje.


 ## Estructuras de control:
  - *if (is_int($d))*: se evalua si la variable d es un entero

  - *if (is_string($a))*: se evalua si la variable a es un string

  - *$d = $a ? ++$d : $d.3*: se evalua si a es verdadero, y dependiendo de eso a d se le asigna su valor mas uno (en el caso de true) o su valor multiplicado por 3 (en el caso de false)

  ## Salida por pantalla:
  *boolean* --> echo gettype($a);
  *string* --> echo gettype($b);
  *string* --> echo gettype($c);
  *integer* --> echo gettype($d);
  *1* --> echo $a;
  *xyz* --> echo$b;
  *xyz* --> echo $c;
  *18* --> echo $d;
  *44* --> echo $f;
  *44* --> echo $g;
