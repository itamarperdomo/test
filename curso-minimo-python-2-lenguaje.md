# curso de como programar con python MOD 2

- [Lexico y sintaxis](#lexico-y-sintaxis)
  - [Ejemplo implicito de lexico en OOP o POP](#ejemplo-implicito-de-lexico-en-oop-o-pop)
- [Sentencias](#sentencias)
- [Secuencia](#secuencia)
- [Variables y Valores](#variables-y-valores)
    - [Sintaxis y lexico de python](#sintaxis-y-lexico-de-python)
      - [Lexico en python y la sangria](#lexico-en-python-y-la-sangria)
      - [Palabras reservadas para el lexico](#palabras-reservadas-para-el-lexico)
      - [Simbolos para Operadores del lexico](#simbolos-para-operadores-del-lexico)
      - [Reglas de la Sintasix de python](#reglas-de-la-sintasix-de-python)
      - [Reglas de Nombres de variables](#reglas-de-nombres-de-variables)
      - [Usando el operador "#" y creacion de comentarios](#usando-el-operador-"#"-y-creacion-de-comentarios)
- [esto es una sentencia de comentario](#esto-es-una-sentencia-de-comentario)
- [estas lineas seran ignoradadas por el interperete python](#estas-lineas-seran-ignoradadas-por-el-interperete-python)
    - [Expresiones de la sintaxis python](#expresiones-de-la-sintaxis-python)
      - [Reglas de precedencia de los operadores](#reglas-de-precedencia-de-los-operadores)
      - [Usando el operador "=" y asignacion de variables](#usando-el-operador-"="-y-asignacion-de-variables)
      - [Usando "+" y concatenacion de variables](#usando-"+"-y-concatenacion-de-variables)
      - [usar "def" y "return" para funciones asi como definir funciones](#usar-"def"-y-"return"-para-funciones-asi-como-definir-funciones)
        - [Usar "def" y "return" en Funciones de orden superior](#usar-"def"-y-"return"-en-funciones-de-orden-superior)
        - [Usar "lambda" o funciones anonimas de una linea](#usar-"lambda"-o-funciones-anonimas-de-una-linea)
        - [Funciones internas de python](#funciones-internas-de-python)
      - [Usando "print" y como Imprimir una variable](#usando-"print"-y-como-imprimir-una-variable)
      - [Usando "type" y Como saber el tipo de variable](#usando-"type"-y-como-saber-el-tipo-de-variable)
      - [Usando "True" y "False" y expresiones booleanas](#usando-"true"-y-"false"-y-expresiones-booleanas)
      - [Usando "if/elif/else" condicionales "==" y comparaciones ">" o "<"](#usando-"if/elif/else"-condicionales-"=="-y-comparaciones-">"-o-"<")
      - [Usar el "while" y el uso de "break" en bucles](#usar-el-"while"-y-el-uso-de-"break"-en-bucles)
      - [Usar el "for" y el "continue" y los bucles](#usar-el-"for"-y-el-"continue"-y-los-bucles)
      - [Usar "[]" y "()" con SECUENCIAS y COLLECCIONES](#usar-"[]"-y-"()"-con-secuencias-y-collecciones)
      - [Usar "{}" y "](#"-con-diccionarios)
      - [Usar "for" en listas y diccionarios](#usar-"for"-en-listas-y-diccionarios)
      - [Cadenas de caracteres como listas](#cadenas-de-caracteres-como-listas)
      - [Usar "{}" y "format" para variables dinamicas y formato de cadenas de texto](#usar-"{}"-y-"format"-para-variables-dinamicas-y-formato-de-cadenas-de-texto)
      - [Conversion de tipos usando funciones de tipos de variables](#conversion-de-tipos-usando-funciones-de-tipos-de-variables)
      - [Cohersion de tipos usando funciones de tipos de variables](#cohersion-de-tipos-usando-funciones-de-tipos-de-variables)
      - [Funciones matemáticas](#funciones-matemáticas)
      - [Composición](#composición)
      - [Uso de operador "%" modulo y la division "/"](#uso-de-operador-"%"-modulo-y-la-division-"/")
      - [Uso de "and" y "or" y "not" y operaciones logicas](#uso-de-"and"-y-"or"-y-"not"-y-operaciones-logicas)

## Lexico y sintaxis

En programación, se usa(n) lenguaje(s), y este usa un léxico, este es el 
que es el vocabulario.

Son las palabras, números y símbolos (como +, =, if, where) que el lenguaje 
usa para realizar y traducir a la maquina para crear un programa.

Si escribes una palabra que no está en su "diccionario", o no sigue una 
forma de ser reconocida (variables, texto, etc) el lenguaje se confunde 
porque no reconoce la pieza/lexico.

#### Ejemplo implicito de lexico en OOP o POP

En POP (programacion orientada a procesos) esto seria como se aplica:

* Idea: Mostrar un saludo. (hola)
* Léxico: Eliges como se mostrara (en papel escrito)
* Sintaxis: El idioma y como escribirlo (saber escribir espanol)
* Existencia: Necesitas papel y lapiz y escribirlo

En OOP (programacion orientada a objetos)  ¿Cómo se conectan con una "Idea"?:

Para que tu "Idea" (la Clase) se convierta en una "Existencia" (la Instancia), 
tienes que realizarla usando una forma o via (Léxico) y siguiendo una manera o 
un proceso (el orden, o la Sintaxis). Si fallas en alguna de las dos, la idea 
se queda atrapada y nunca llega a existir.

### Sentencias

Una sentencia es una instrucción o regla de programación.

Las reglas son las que puede ejecutar el intérprete de Python.

La sentencia mas famosa y que hemos visto es `print`

```python
print()
```

- Sentencias de asignacion: `input()`
- Sentencias de uso/valor: `print()`

El resultado de una sentencia de uso/valor es un valor.
Las sentencias de asignación no entregan ningún resultado.

### Secuencia

Normalmente un guión/script contiene una secuencia de sentencias.
Si hay más de una sentencia, los resultados aparecen de uno en uno
tal como se van ejecutando las sentencias.

Ejemplo esta es una sentencia pero no es una secuencia:

```
print()
```

Este ejemplo es una secuencia:

```
print()
print()
```

En la secuencia hay dos "print" y se ejecuta uno despues del otro!

### Variables y Valores

Variable es la unidad de transporte de informacion.

Creamos una variable para guardar y después ver esta informacion,
la informacion se coloca "dentro" de la variable.

Valor es la forma en que manejamos dentro del programa las variables

Lo que se "guarda adentro" de la variable es el valor.

## Sintaxis y lexico de python

La sintaxis se clasifica generalmente en tres niveles:

* Palabras que determinan cómo los caracteres forman tokens;
* Frases que surgen al agrupar las palabras para llegar a funciones
* Contexto si las palabras usadas son o no variables y su validez

El problema y fortaleza de python es el principio de: 
***"solo haber una -y sólo una- forma obvia de hacerlo"***

Este mantra se opone deliberadamente a la Perl y Rubí mantra:
donde "Hay más de una forma de hacerlo".

### Lexico en python y la sangria

El estilo de sangría se utiliza en python principalmente para reconocer 
los bloques de elementos del código fuente.

En python todo bloque o partes de codigo lleva una sangria, esta debe 
ser equivalente, si usas en una parte solo dos espacios en todo el resto 
debe siempre usar tambien dos espacios.

Esto se le llama **off-side rule**, que define los límites de un bloque 
de código via sangría. Python toma prestada esta característica de su 
predecesor ABC en contraste de la "formato libre" donde se usa llaves 
o palabras clave como "begin/end"

### Palabras reservadas para el lexico

El léxico se refiere a las palabras que el intérprete de Python reconoce, 
asi como los identificadores (variables y asignaciones/valor)

Palabras Clave (Keywords): Son términos reservados con un significado especial 
que no puedes usar como nombres de variables.

| keyword        | 2   | 3   | Resumen |
|----------------|-----|-----|---------|
| `print`        | Si  | No  | Impresion en la salida estandar |
| `exec`         | Si  | No  | Ejecucion en hilo         |
| `if`/`else`    | Si  | Si  | Condiciones Si/entonces   |
| `if`/`elif`    | Si  | Si  | Multicondiciones, Swich/case |
| `for`          | Si  | Si  | Ciclos multicondicional finito |
| `while`        | Si  | Si  | Ciclo/bucle condicional simple |
| `continue`     | Si  | Si  | Continuar siguiente ciclo |
| `break`        | Si  | Si  | Detencion del ciclo/bucle |
| `lambda`       | Si  | Si  | Funcion de una sola linea |
| `def`          | Si  | Si  | Define una funcion multilinea |
| `return`       | Si  | Si  | Ofrece resultado en funcion |
| `yield`        | Si  | Si  | Genera resultado en funcion |
| `pass`         | Si  | Si  | Placeholder, falso codigo |
| `import`       | Si  | Si  | Embuye codigo(modulo) en codigo |
| `from`         | Si  | Si  | Desde que archivo embuye  |
| `as`           | Si  | Si  | Alias de un modulo o variable |
| `with`         | Si  | Si  | Utilizar recursos y flujos |
| `async`        | No  | Si  | Concurrencia de flujos    |
| `await`        | No  | Si  | Pausa la concurrencia de flujos |
| `del`          | Si  | Si  | Eliminar recursos,flujos,variables |
| `class`        | Si  | Si  | Define uan clase/objeto   |
| `True`/`False` | No  | Si  | Desde 3.12: verdad/falso  |
| `and`          | Si  | Si  | Operacion logica "Y"      |
| `or`           | Si  | Si  | Operacion logica "O"      |
| `not`          | Si  | Si  | Operacion logica "negacion" |

### Simbolos para Operadores del lexico

Es cuando siendo o no una secuencia, hay mas de una sentencia
combinada para producir una nueva sentencia.

Python usa un set reducido de simbolos para las operaciones y 
no usa casi ninguno para la sintaxis.

| Categoría   | Símbolo  | Nombre         | Uso  |
| ----------- | -------- | -------------- | ---- |
| Documentar  | `#`      | **Hash**       | Escribir comentarios |
| Documentar  | `'`      | **Apostrofe**  | Comentario multilinea |
| Asignación  | `=`      | **Asignar**    | Asignar una variable |
| Comparación | `==`     | **Igualdad**   | Comparacion exacta   |
| Comparación | `!=`     | **Diferente**  | Comparacion distinta |
| Comparación | `<`/`>`  | **Mayor/Menor** | Comparacion distinta |
| Operador    | `+`/`-`  | **Suma/resta** | Sumar y restar       |
| Operador    | `*`/ `/` | **Mult/Divi**  | multiplicar y dividir |
| Operador    | `**`     | **Exponente**  | Elevar a una potencia |
| Operador    | `%`      | **Módulo**     | Residuo de division |
| Operador    | `//`     | **Dividir**    | Dividir sin decimal |
| Agrupación  | `;`      | **Punto/coma** | Codigo en una linea |
| Agrupación  | `( )`    | **Paréntesis** | Parametro de la funcion |
| Datos       | `[ ]`    | **Corchetes**  | Elementos de listas |
| Datos       | `{ }`    | **Llaves**     | Definir **diccionarios** |
| Datos       | `->`     | **Flecha**     | Asignar tipo de dato |
| Significado | `:`      | **Dos puntos** | Define codigo de funcion |
| Flujo       | `"`,`'`  | **Comillas**   | Definir cadenas de texto |
| Flujo       | `\`      | **Backslash**  | Carácter de escape |
| Flujo       | `@`      | **Arroba**     | Modifican funciones |

### Reglas de la Sintasix de python

* Indentación Obligatoria: recordemos que es de tipo **off-side rule**, 
usando espacios o sangría para definir bloques de código
* Sin punto y coma: No es necesario terminar cada línea con un simbolo 
final. Se usa opcionalmente ";" solo para agrupar multiples lineas.
* Variables Simples: No necesitas declarar el tipo de dato ni definir 
las varaibles con un tipo especifico, solo asignar el valor.
* Funciones: Se definen con la palabra def seguida del nombre y su cuerpo 
empieza despues de los dos puntos ":", con la sangria definiendo el cuerpo.

### Reglas de Nombres de variables

El nombre de una variable debe:

- Comenzar con letra ( `1var` es un nombre invalido)
- Respetar mayúsculas y minúsculas ( `var` es distinto de `vAr`)
- No debe tener símbolos ( `var$` es un nombre invalido)
- No debe ser uan palabra reservada.

Una expresión es una combinación de valores y variables en una
o mas de una sentencia.

### Usando el operador "#" y creacion de comentarios

```python
# esto es una sentencia de comentario
# estas lineas seran ignoradadas por el interperete python

2
```

Las primeras dos lineas son comentarios, el "#" permite que se escriban 
notas en el codigo fuente, para documentar.

La tercera linea es solo un "2" que el compilador vera como una sentencia 
aislada y sin procesamiento. Es una sentencia pero sin resultado alguno.

## Expresiones de la sintaxis python

Es cuando siendo o no una secuencia, hay mas de una sentencia
combinada para producir una nueva sentencia.

Una expresión es una combinación de valores y variables en una
o mas de una sentencia.

* Una sentencia nunca devuelve un resultado, la sentencia es el valor:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> 2
2
```

* Una expresion usa una sentencia o mas con o sin operadores para un resultado:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> 1+1
2
```

* REGLA 1 **una expresion siempre devuelve un resultado**! sea numerico o no!
* REGLA 2 **una sentencia siempre contiene una o mas expresiones.**

### Reglas de precedencia de los operadores

Cuando aparece más de un operador en una expresión, el orden de evaluación 
depende de las reglas de precedencia. Python sigue las mismas reglas de 
precedencia que los propios matemáticos para sus operaciones matemáticas.

> **Warning** aunque con bases matematicas, los operadores y su orden 
  se aplican tambien a cualquier expresion o sentencia en python.

Los ingleses usan el acrónimo PEMDAS como regla parea recordar el orden de 
las operaciones:

Paréntesis: tienen la precedencia más alta y pueden usarse para forzar que 
una expresión se evalúe en el orden que queramos nosotros. Puesto que las 
expresiones entre paréntesis se evalúan primero, 2 * (3-1) es igual a 4, y 
(1+1)**(5-2) es igual a 8. También puede usar paréntesis para que una 
expresión sea más legible; por ejemplo (minuto * 100) / 60, aunque el 
resultado no cambie de todas formas.

Exponenciación tiene la siguiente precedencia más alta; ası́ pues 2**1+1 
es igual a 3 y no a 4, y 3*1**3 es igual a 3 y no a 27.
La Multiplicación y la División tienen la misma precedencia, que es más 
alta que la de la Adición y la Sustracción, que tienen también la misma 
precedencia. Por tanto 2*3-1 devuelve 5 y no 4, y 2/3-1 da -1, y no 1 
(recuerde que en la división de enteros 2/3 da 0).

Los operadores que tienen la misma precedencia se evalúan de izquierda 
a derecha. Ası́, en la expresión minuto*100/60, tiene lugar primero la 
multiplicación, devolviendo tt 5900/60, que a su vez da como resultado 
98. Si las operaciones se hubiesen realizado de derecha a izquierda, el 
resultado habrı́a sido 59/1 que da 59, y que es incorrecto.

### Usando el operador "=" y asignacion de variables

Python define las variables automáticamente al asignarles un valor, 
ya que es un lenguaje de tipado dinámico

``` python

aa = "a" # al asignar ya es tambien de tipo string

bb = 2   # al asignar la hizo de tipo entero

cc = 2.0 # hay que declararla explicitamente

aa = 3   # el tipo de variable cambio
```

> **Warning** Notese que no es lo miso `bb` que `cc`, y `aa` cambio!

Un valor, y también una variable, se considera una expresión por si mismo.

```python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> 17
17
>>> x = 2
>>> x
2
```

Para complicar las cosas, evaluar una expresión no es del todo lo mismo que 
imprimir un valor.

```python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> mensaje = "Que onda?"
>>> mensaje
>>> "Que onda?"
>>> Que onda?
```

### Usando "+" y concatenacion de variables

El operador de "+" permite no solo sumar, sino que 
podemos también juntar dos textos (cadena de caracteres):

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> aa = "valor1"
>>> bb = "valor2"
>>> aa + bb
>>> "valor1valor2"
```

Sin embargo si las variables y su valor no son del mismo tipo 
se generara un error:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> aa = "valor1"
>>> bb = 222
>>> aa + bb )
```

La salida no llegara y solo veremos un error que sera:

```
TypeError: unsupported operand type(s) for +: 'str' and 'int'
```

Para trabajar con las variables tiene estas que ser del mismo 
tipo de contenido, un texto solo se puede unir/trabajar con 
otro texto, un numero solo se puede sumar/operar con otro numero.

### usar "def" y "return" para funciones asi como definir funciones

Python, sin ser un lenguaje puramente funcional incluye varias características 
tomadas de los lenguajes funcionales como son las funciones de orden superior 
o las funciones lambda (funciones anónimas).

La programación funcional es un paradigma en el que la programación se basa 
casi en su totalidad en funciones, entendiendo el concepto de función según 
su definición matemática, y no como los simples subprogramas de los lenguajes 
imperativos que hemos visto hasta ahora.

```
def funcion(parametros)
  codigo = parametros con operacion
  return codigo

resultado = funcion(valorprocesarcomoparametro)
```

La sentencia `return` le permite terminar la ejecución de una función antes 
de alcanzar su final.

> **Warning** El flujo de la ejecución termina y devuelve en "return" a el llamante

#### Usar "def" y "return" en Funciones de orden superior

El concepto de funciones de orden superior se refiere al uso de funciones 
como si de un valor cualquiera se tratara, posibilitando el pasar funciones 
como parámetros de otras funciones o devolver funciones como valor de retorno.

``` python

def sumar(a,b):
    rerurn = a+b

resultado = sumar(1,2)
```

Este codigo es una funcion de orden superior, ya que se define con un nombre, 
este es "vertexto", y por eso es de orden superior.

#### Usar "lambda" o funciones anonimas de una linea

El concepto de funciones anonimas o "rapidas" se refiere al uso de funciones 
que no necesitan una definicion de nombre y esctructura, llamadas funciones 
de una sola linea tambien y que obviamente implican un valor de retorno.

``` python

sumar = lambda a,b: a+b

resutlado = sumar(1,2)
```

Este codigo es una funcion anonima o rapida, ya que se define sin un nombre, 
y se usa "sumar" como una variable equivalente a la fucionalidad.

#### Funciones internas de python

Las mas famosas son `print` y `exec`, que historicamente no eran fuciones, 
desde python 3 estas se hicieron fuciones de orden superior e internas del 
lenguaje de programacion

``` python

codigoaexecutar = "print(1)"

exec(codigoexecutar)
```

Este codigo es igual que este:


``` python

print(1)
```

### Usando "print" y como Imprimir una variable

Podemos imprimir con la funcion interna `print("texto")` y usar variables:

``` python

aa = "texto"

print ( aa )
```

### Usando "type" y Como saber el tipo de variable

Para saber el tipo de variable tenemos la funcion `type`, en el 
interprete solo ahy que escribir `type` + "Variable":

``` python

Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> type ("hola")
<class 'str'>
>>>
```

Sin embargo si lo ejecuta en el precompilador es distinto:

``` python

type ("hola")

type (222)
```

La salida sera nula porque `type` no "imprime" a la salida.
Recordemos que esta es una sentencia de asignación.
Para poder ver la salida debemos tomar todo y enviarlo a impresión:

``` python

print (type ("hola") )

print (type (aa) )
```

La salida sera:

```
<class 'str'>
<class 'int'>
```

### Usando "True" y "False" y expresiones booleanas

Una expresión booleana es una expresión que es cierta o falsa. En Python, 
una expresión que es cierta tiene el valor 1, y una expresión que es falsa 
tiene el valor 0.

> **Warning** las expresiones booleanas son la base de las condiciones!

Solo en Python 3 esta `True` y `False` como representaciones de boleanos.

El operador `==` compara dos valores y entrega una expresión booleana:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> 5 == 5
1
>>> 5 == 6
0
```

En la primera sentencia, los dos operandos son iguales, asi que la 
expresión se evalúa como 1 (verdadero); en la segunda sentencia, 5 no 
es igual a 6, ası́ que obtenemos 0 (falso).

### Usando "if/elif/else" condicionales "==" y comparaciones ">" o "<"

Para evaluar una condicion se realiza una expresion booleana, la 
expresion booleana verifica con la regla de condicion si se cumple 
la situacion deseada.

Para esto, la sintaxis que usa Python es la siguiente:

```
if(condicion):
  lo que pasa si se cumple
elif(condicion)
  lo que pasi si otra condicion
else:
  lo que pasa si no se cumple
```

Donde "condicion" es una **expresion** que usa **operador** de **comparacion**.

El operador `==` es uno de los operadores de comparación; los otros son:

* `!=` Para ver si son distintos, funciona con cadenas o numeros
* `>` Para ver si un operando es mayor que el segundo, solo numeros
* `<` Para ver si un operando es menor que el segundo, solo numeros
* `>=` Para ver si es mayor o tambien es igual al mismo tiempo
* `<=` Para ver si es menor o tambien es igual al mismo tiempo

Aunque probablemente estas operaciones le resulten familiares, los 
sıimbolos en Python son diferentes de los matemáticos. Un error 
que no debe hacerse habitual es utilizar un signo igual sencillo (=) 
en lugar del doble (==). Recuerde que `=` es un operador de asignación 
y `==` es un operador de comparación. Además, no existen `=<` ni `=>`.

EJEMPLO 1 USANDO IGUALDAD

``` python

aa = 5
if(aa == 5)
  print("es 5")
else
  print("otro")
```

OJO IMPRIMIRA "es 5" PORQUE "aa" VALE 5, 
EN EL IF/ELSE EVALUAMOS SI "aa" VALE 5 !

EJEMPLO 2 USANDO DISTINTO

``` python

aa = 5
if(aa =! 5)
  print("no es")
else
  print("otro")
```

OJO IMPRIMIRA "no es" PORQUE USAMOS "=!", 
EN EL IF/ELSE EVALUAMOS SI "aa" ES DISTINTO 5 !

EJEMPLO 3 MULTICONDICIONES

``` python

aa = 5
if(aa > 5)
  print("no es")
elif(aa < 5)
  print("no es")
else
  print("otro")
```

OJO IMPRIMIRA "otro" PORQUE NUNCA ES MAYOR O MENOR, 
EN EL ELSE ES PORQUE "aa" ES EL 5 Y PREGUNTAMOS POR MAYOR O MENOR!

### Usar el "while" y el uso de "break" en bucles

Para evaluar un ciclo condicional realiza una expresion booleana, la 
expresion booleana verifica con la regla de condicion si se cumple 
la situacion deseada mientras se ejecuta el ciclo.

Parecida a la primera parte de la estructura condicional.

```
while(condicion):
  código que se repite
  if (condicion)
    break
  otro codigo que se repite
```

Donde "condicion" es una **expresion** que usa **operador** de **comparacion**.

El operador `==` es uno de los operadores de comparación; los otros son:

* `!=` Para ver si son distintos, funciona con cadenas o numeros
* `>` Para ver si un operando es mayor que el segundo, solo numeros
* `<` Para ver si un operando es menor que el segundo, solo numeros
* `>=` Para ver si es mayor o tambien es igual al mismo tiempo
* `<=` Para ver si es menor o tambien es igual al mismo tiempo

Aunque probablemente estas operaciones le resulten familiares, los 
sıimbolos en Python son diferentes de los matemáticos. Un error 
que no debe hacerse habitual es utilizar un signo igual sencillo (=) 
en lugar del doble (==). Recuerde que `=` es un operador de asignación 
y `==` es un operador de comparación. Además, no existen `=<` ni `=>`.

Por ejemplo, supongamos que queremos contar los números de 1 a 5. El código sería:

``` python

x=0
while(x<5):
  x=x+1
  print(x)
```

En este tenemos

1. Inicializar, un estado inicial, x=0
2. Condicion predestinada inmutable, antes del bucle se detendra al pasar de 5

Este codigo se puede escribir de una forma distinta donde la condicion sea 
implicita, y la finalizacion dependa de detectar EN EL MOMENTO de ejecucion 
de el buble y no predefinido desde antes del bucle (habiamos definido x<5)

``` python

x=0
while(True):
  x=x+1
  print(x)
  if(x==5):
    break
```

En este tenemos

1. Inicializar, un estado inicial, x=0
2. Condicion idefuinida, siempre se ejecutara porque dice "while(true)"
3. Deteccion dinamica de parada, en el momento de ejecucion evalua si llega a 5

> **Warning** En esta forma si la evaluacion es incorrecta nunca se detendra!

Como puede observarse, ambos programas producen el mismo resultado.

### Usar el "for" y el "continue" y los bucles

En python el "for" es un explorador, no un contador, tampoco es iterador.

Si bien llega a funcionar como iterador, es solo un funcionamiento equivalente.
Por tanto para hacer el mismo contador necesitamos usar una funcion, que 
en nuestro caso es `range()` para ayudar a contar:

``` python

for x in range(1,10)
  print(x)
  if(x==5):
    break
```

1. La función `range` ha creado los números del 1 al 10.
2. La variable `i` toma el valor de cada numero en cada ciclo/bucle.
3. Cada ciclo imprime con `print(x)`
4. Son varios ciclos porque hay más valores para el "for" en la "x"
5. Pero en cada ciclo hay uan condicion para ver "si x es 5"
6. Si en tiempo de ejecucion llega x a 5 se ejecuta la detencion del ciclo.

``` python

x=0
while(x<5):
    x=x+1
    if(x==5):
        print("Saltamos el 5... entonces seguira infinitamente?")
        continue
    print(x)
```

En este ejemplo sucede exactametne lo mismo, porque aunque la 
primera condicion predestinada (la del while x<5) se va saltar 
la evaluacion del numero 5, la condicion eliina cualquier otro 
que este mas alla del 5 porque dice "menor que 5"

### Usar "[]" y "()" con SECUENCIAS y COLLECCIONES

Una secuencia es un tipo de datos muy importante en Python. Se trata de colecciones
ordenadas de datos. Los principales tipos son listas, tuplas y cadenas de caracteres, que
ya fueron vistas en el capítulo de variables.

```
listaotupla[indice]

listaotupla[-1]
```

* Una tupla es una "collecion ordenada de solo lectura"
* Una lista es una "collecion ordenada que se puede alterar"
* Un indice negativo accede desde el ultimo valor

``` python

tupla=(1,2,3,4,5,6)
lista=['a','b','c']

print( "el primer elemento de la lista es" , lista[1] )

print( "el ultimo elemento de la lista es" , lista[-1] )

print( "una porcion de la dupla entre 2 y 4" , dupla[2:4] )

print( "secuencia elementos impares de la dupla" , dupla[1::2] )
```

Las duplas no se usan mucho pero si las listas, que son alterables, podemos 
cambiar uno de los valores de la lista asignándolo como si fuera una variable 
poniendo el índice correspondiente. Por ejemplo:

``` python

lista=['a','b','c']

print( "el segundo elemento de la lista es" , lista[2] )

lista[2]="d"

print( "el segundo elemento de la lista cambio" , lista[2] )
```

Podemos, agregar, borrar y ver la cantidad de elementos de la lista:

``` python

lista=['a','b','c']

lista.append("d")

del(lista[2])

len(lista)

print( "la lista cambio y ya el elemento 2 no es b sino es " , lista.index['c'] )
```

En la ultima linea imprimimos la posicon en que se logre encontrar la letra "C".

Podemos usar `lista.remove(nombre)` como equivalente de `del(lista[indice])`, 
pero el primero encuentra/elimina por valor y el segundo por indice.

Para ordenar las listas (pero no las duplas) usamos `lista.sort()`.

Si la lista está compuesta por cadenas de caracteres, éstas se ordenarán 
alfabéticamente. Si está compuesta por números, éstos serán ordenados de menor 
a mayor. Sin embargo, si están mezclados los números y las cadenas de 
caracteres no se puede aplicar esta función porque no existe un criterio 
para ordenar los elementos de esa lista.

### Usar "{}" y ":" con DICCIONARIOS

Los diccionarios son otro tipo de datos en Python. Se dedican a almacenar 
parejas de datos en los que uno es la clave y otro es el valor asociado a esa 
clave. Por ejemplo, un diccionario corriente también se comporta así, ya que 
para cada palabra (clave) existe una definición (valor).

* Son listas de pares definidos, mientras que las listas son pares numerados
* Por eso la clave debe ser un dato mutable (textio o lista) no un numero!
* El valor puede ser cualquier tipo de dato o otra lista

La sintaxis de los diccionarios es la siguiente. Van encerrados entre 
llaves ({ y }) y se escribe la clave, el signo de dos puntos y luego el valor. 
Cada pareja clave-valor es separada de la siguiente por una coma. Por ejemplo:

```
diccionario={"llave1":"valo1","llave2":"valor2" ... }
```

Aquí hemos creado un diccionario con dos datos. Las claves serían cubo y esfera y cada
una de ellas lleva un valor asociado que, en este caso, es una posible definición.

**El diccionario es el equivalente de un arreglo/array en otros lenguajes**

Las operaciones de los diccionarios son iguales que los de las listas. 
Pero usando las llaves nombradas en vez de indices numericos:

```
diccionario['llave1']="valo1"

del(diccionario['llave1'])
```

Pero hay operaciones adicionales exclusivas de los diccionarios

```
diccionario.keys()

diccionario.values()

diccionario.items()
```

* "keys" devueve un nuevo arreglo tipo lista con las llaves
* "values" deveulve un nuevo arreglo tipo lista con los valores de las llaves
* "items" devuelve todo el diccionario pero en duplas llave/valor

### Usar "for" en listas y diccionarios

Se puede interactuar con cualquier lista que haya creado, por ejemplo:

``` python

lista=["verde","rojo","amarillo"]
for i in lista:
  print("El",i,"es un color muy bonito.")
```

Supongamos que queremos hacer un bucle sobre un diccionario. Vamos a crear 
uno con los tres colores de la lista como claves y, como valores, 
insertaremos elementos que tienen esos colores:

``` python

colores={"Verde":"Césped.","Rojo":"Fuego","Amarillo":"Sol."}
for i in colores:
  print(i)
```

Lo único que nos imprime son las claves del diccionario. Si queremos obtener 
los valores debemos utilizar la sintaxis propia para acceder a cada clave. 
Por ejemplo, para ver qué valor tiene la clave "rojo" es `colores["rojo"]`

Por lo tanto, en el bucle debemos hacer lo mismo pero haciendo que la clave 
que nos interese sea la que en ese momento tenga la variable. Un bucle en el 
que combinemos claves y valores podría ser el siguiente:

``` python

for i in colores:
  print(i+":",colores[i])
```

### Cadenas de caracteres como listas

Lo primero será crear la cadena con la que trabajaremos:

``` python

principio="En un lugar de la Mancha, de cuyo nombre no quiero acordarme."
```

Ahora ya estamos listos para aplicar estas funciones.

``` python

principio.lower()

print(principio)
```

Esta función convierte toda la cadena a minúsculas.

Sin embargo, si usted manda a imprimir el contenido de la variable principio 
verá que la cadena sigue siendo la original. Si quiere conservar la 
modificación que realiza tanto la función "lower" como las demás funciones 
que veremos en este apartado deberá almacenar estos resultados en una variable.

``` python

nuevacad = principio.lower()

print(nuevacad)
```

Ahora convertir toda la cadena a mayusculas:

``` python

nuevacad = principio.upper()
```

En este ejemplo se sustituiría la letra "a" por el número "1".

``` python

nuevacad = principio.replace("a","1")
```

Divide la cadena por el punto en el que encuentra un espacio en blanco y 
forma una lista a partir de dicha división.

``` python

nuevacad = principio.split()
```

Esta función acepta dos argumentos. el primero es el caracter por el que se 
debe separar, el segundo es la cantidad de separaciones que se deben realizar.

``` python

nuevacad = principio.split(" ",1)
```

Esta llamada a la función crearía una lista con dos elemenntos. El primero 
sería la primera palabra y el segundo sería el resto de la cadena.

Para la última función necesitamos crear una lista.

``` python

lista=["Una","serie","de","palabras."]
```

Vamos a unir todos esos elementos en una única cadena de caracteres.

Supongamos que, como son palabras, queremos separar cada una de la siguiente 
por un espacio en blanco. En este caso, haríamos lo siguiente:

``` python

lista=["Una","serie","de","palabras."]

" ".join(lista)
```

Como se puede apreciar, estas funciones se pueden aplicar tanto sobre una cadena
concreta de caracteres como sobre la variable que la contenga.
En el caso de esta última función la cadena sobre la que actuará "join" es el grupo de
caracteres que separará cada elemento de la lista del siguiente.

### Usar "{}" y "format" para variables dinamicas y formato de cadenas de texto

En este apartado veremos cómo se formatean las cadenas, es decir, cómo presentarlas de
una forma bonita y amigable al usuario. Veamos un ejemplo:

```
nombre="Pedro"
edad=35
"{0} tiene {1} años.".format(nombre,edad)
```

Esta función, que se llama "format", crea una lista con lo que recibe 
como parámetro y va sustituyendo los elementos en el lugar de la cadena 
en el que encuentre un número encerrado entre llaves. En nuestro ejemplo 
crea la lista con el contenido de las dos variables. Después recorre la 
cadena y encuentra un cero entre llaves. En ese punto imprime lo que hay 
en la posición cero de la lista (el contenido de la variable "nombre"). 
Después sigue recorriendo la cadena y cuando llega al uno entre llaves 
busca la posición uno en su lista, que es el contenido de la variable 
llamada "edad" y realiza la sustitución pertinente.

Lo primero que cabe reseñar es que se puede acceder a un valor concreto 
de una lista, tupla o diccionario:

```
"{0[2]}".format(lista)
```

Esto mostraría únicamente el elemento que ocupa la posición tres de la 
lista.

Después del número del elemento a sustituir se puede escribir el signo de 
dos puntos y una serie de caracteres que afectan a la forma en que se 
imprimirá ese elemento.

El primero de estos caracteres afecta a la alineación:

* Un signo de menor que (<) hará que los caracteres alineen a la izquierda.
* Un signo de mayor que (>) hará que los caracteres alineados a la derecha.
* Un signo de acento circunflejo (^) provocará que sean centrados.

A continuación de la alineación se puede escribir un número que especificará 
el ancho del que se dispone para la alineación.

La última opción está disponible únicamente para los números decimales. A 
continuación del ancho se puede escribir un punto y un número que provocará 
un redondeo a una cierta cantidad de decimales. El número indica la cantidad 
de dígitos que se imprimirán entre la parte entera y la parte decimal

```
from math import pi
  "{0:.5} {1:.5}".format(50.23456789,pi)
```

Se imprimiría: "50.235 3.1416"

### Conversion de tipos usando funciones de tipos de variables

Python proporciona una colección de funciones internas que convierten valores 
de un tipo a otro. La función int toma un valor y lo convierte a un entero, 
si es posible, o da un error si no es posible.


``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> int("32")
32
>>> int("Hola")
ValueError: invalid literal for int(): Hola
```

La funcion int también convierte valores de coma flotante a enteros, pero 
siempre redondea hacia abajo:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> int(3.99999)
3
```

La función float que convierte enteros y cadenas en números en coma flotante:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> float(32)
32.0
>>> float("3.14159")
3.14159
```

Finalmente, está la función str, que convierte a tipo string:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> str(32)
’32’
>>> str(3.14149)
’3.14149’
```

Pudiera parecer extraño que Python distinga entre el valor entero 1 y el 
valor de coma flotante 1.0. Tal vez representen el mismo número, pero 
pertenecen a tipos distintos. El motivo es que se representan de forma 
distinta dentro del computador

### Cohersion de tipos usando funciones de tipos de variables

La reglas de conversion tiene adicionales reglas de conversion automaticas, 
a esto se le denomica cohersion de tipos y es una conversion a consecuencia.

Ejemplo, para los operadores matemáticos, si uno de los operandos matemáticos 
es tipo float, el otro se convierte automáticamente en float.


``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> minuto = 59
>>> minuto / 60.0
0.983333333333
```

La segunda expresion es una sentencia de divicion donde uno de los operandos 
es un `float`, lo que implica que si el primero no se definio explicitamente 
obligara a toda la operacion ser realizada sobre flotantes.

Al usar un denomidador que es float, obligamos a Python a hacer división de 
coma flotante.

### Funciones matemáticas

Es posible que ya haya visto usted en matemáticas funciones como `sin` (seno) 
y `log` (logaritmo), y que haya aprendido a evaluar expresiones como 
`sin(pi/2)` y `log(1/x)`.

Segunlo que explicamos al inicio de este modulo segun la **precedencia** en 
la sintaxis de python:

1. Primero evalúa la expresión entre paréntesis, (el argumento).
Por ejemplo, pi/2 es aproximadamente 1.571, y 1/x es 0.1 (si x es igual a 10.0).
2. Luego evalúa la función en sı́ misma, bien mirándola en una tabla, bien llevando
a cabo diversos cálculos. El sin (seno) de 1.571 es 1, y el log de 0.1 es -1
(suponiendo que log indique el logaritmo de base 10).

Este proceso puede aplicarse repetidamente para evaluar expresiones más com-
plicadas como log(1/sin(pi/2)). Primero evaluamos el argumento de la fun-
ción más interna, luego se evalúa la función, y ası́ sucesivamente.
Python dispone de un módulo matemático que proporciona la mayorı́a de las
funciones matemáticas habituales. Un módulo es un archivo que contiene una
colección de funciones agrupadas juntas.

### Composición

Igual que con las funciones matemáticas, las funciones de Python se pueden
componer; eso quiere decir que se usa una expresión como parte de otra. Por
ejemplo, puede usar cualquier expresión como argumento de una función:

```
x = math.cos(angulo + pi/2)
```

Esta sentencia toma el valor de pi, lo divide entre dos y le añade el resultado
al valor de angulo. La suma se pasa luego como argumento a la función cos.
También puede tomar el resultado de una función y pasárselo como argumento
a otra:

```
x = math.exp(math.log(10.0))
```

Esta sentencia encuentra el logaritmo en base e de 10 y luego eleva e a ese
exponente. El resultado queda asignado a x

### Uso de operador "%" modulo y la division "/"

El operador módulo funciona con enteros (y expresiones enteras), y devuelve 
el resto de dividir el primer operando entre el segundo. En Python, el 
operador de módulo es el signo de tanto por ciento ( %). La sintaxis es la 
misma de los otros operadores:

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> cociente = 7 / 3
>>> print cociente
2
>>> resto = 7 % 3
>>> print resto
1
```

Asi, 7 dividido entre 3 da 2 con 1 de resto. El operador de módulo resulta 
ser soprendentemente útil. Por ejemplo, puede comprobar si un número es 
divisible entre otro: si x % y es cero, entonces x es divisible entre y.

También puede usar el operador módulo para extraer el digito más a la 
derecha de un número. Por ejemplo, x % 10 devuelve el dı́gito más a la 
derecha de x (en base 10). De forma similar, x % 100 devuelve los dos 
últimos digitos.

### Uso de "and" y "or" y "not" y operaciones logicas

Hay tres operadores lógicos: `and`, `or`, y `not`. La semántica del lexico 
de estos operadores es similar a sus significados en inglés.

Por ejemplo, `x >0 and x <10` es verdadero sólo si `x` es mayor que `0` 
y menor que `10`; otro ejemplo, `n %2 == 0 or n %3 == 0` es verdadero 
si cualquiera de las condiciones es verdadera, o sea, si el número es 
divisible por 2 o por 3.

Finalmente, el operador not niega una expresión booleana, de forma que 
`not(x>y)` es cierto si `(x >y)` es falso, o sea, si `x` es menor o igual 
que `y`. Hablando estrictamente, los operandos de los operadores lógicos 
deberian ser expresiones booleanas, pero Python no es muy estricto. 

Cualqueir número que no sea cero se interpreta como "verdadero".

``` python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> x = 5
>>> x and 1
1
>>> y = 0
>>> y and 1
0
```

En general, este tipo de cosas no se considera una practica adecuada y no 
es correcto. Si quiere comparar un valor con cero, debera hacerlo 
explicitamente.

## Mas en

* https://gitlab.com/venenux/latam_programadores-codigos
* https://t.me/latam_programadores

