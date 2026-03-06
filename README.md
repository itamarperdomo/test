# curso de como programar con python MOD 1

Python es creado por Guido van Rossum en los 90 cuyo nombre está 
inspirado en los cómicos ingleses “Monty Python” por eso su sintaxis exagerada.

Los programas elaborados en Python parecen pseudocódigo, (que son faciles 
de seguir como si fuera contar una historia).

Pero Python no es adecuado sin embargo para la programación de bajo
nivel o para aplicaciones en las que el rendimiento sea crítico.
Esto lo mencionan libros como "Python Para Todos" (Raul G Duque), 

Su exito se debe a que lo empezo usar Google y la NASA cuando cambiaron 
todos los sistemas a Linux, python era el unico lenguaje que tenia las 
mismas ventajas de Java pero que no requeria tanta preparacion para usarlo.

### Caracteristicas de python

TEXTO PARA LOS QUE NO TIENEN VIDA SOCIAL:
Se trata de un lenguaje interpretado o de script de programacion:
1. con tipado dinámico, fuertemente tipado
2. multiplataforma
3. orientado a objetos.

TRADUCCION PARA TONTOS O GENTE CON FAMILIA FELIZ:
Idioma para crear programas que exagera la forma en que se escribe:
1. fuertemente correctivo, si te falta un espacio esta malo.
2. multiplataforma, salvo a los usuarios de sistemas operativos ineficientes.
3. deja representar cosas y situaciones de la vida real.

## PORQUE PYTHON

Era menos complicado que C y aun mas facil que Java.

## Porque la comparacion con C o Java

Cuando se impelmento tecnologia en institutos como la NASA o 
en las universidades, los profesores e investigadores no 
tenian ni podian perder tiempo en complicados conceptos de C o Java.

Al igual que Tanto C como Java requiren de complicaciones para 
que un simple proyecto se pueda portar a otras plataformas.

## Ejemplo de porque tuvo exito.

Porque los sistemas despleagos (Symbian y Windos) tenian que 
en un inicio pagar licencia si se usaba Java, si era C entonces 
el codigo fuente tenia que ser muy especifico segun la biblioteca 
o funciones de cada sistema operativo.

#### Ejemplo en java

```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hola mundo");
    }
```

#### Ejemplo en BASIC

```
PRINT "Hola mundo"
END
```

#### Ejemplo en Python

```
print "Hola, Mundo"
```

#### Si basic es facil porque se usa python

BASIC tiene las siguientes tres inconvenientes terribles

1. Es un lenguaje pobre, secuencial, no hay objetos
2. Solo fucniona en Windos, los sistemas de IA solo funcionan en Linux.
3. Con estas dos, python funciona en ambos.

Significa que los cientificos podian hacer script pequenos en 
el python en sus maquinas windos inestables y despues desplegarlas 
en las supercomputadores Linux sin muchos cambios.

#### Si java es potente porque se usa Python

JAVA tiene dos grandes inconvenientes:

1. Es un lenguaje complejo, abstracto, derivado de C
2. Funciona en todos los sistemas, pero requiere licencias.

Desplegar el codigo java no solo implicaba que cada cientifico y 
cada persona tuviera que estudiar complicados estandares y no 
tenian tiempo para eso.

## Programas y systemas

La palabra implica programacion. Una programacion es coordinar tareas.

Un programa es un conjunto de tareas para lograr una meta.

En las computadores un programa son intrucciones (tareas) que 
logran una funcionalidad (tarea) como mostrar el texto (meta).

Un sistema es muchos programas coordinando muchas funcionalidades.

Hoy dia estos son sistemas tanto web (nube) como locales (escritorio)

### Lenguaje de programacion

El lenguaje es la forma en que se escribe esas reglas del programa.

El lenguaje no es lo importante sino la logica implicita.

Los lenguajes son de alto nivel (Python, BASIC, C++), asi como 
los lenguajes de bajo nivel (C ANSI, assembler).

Codigo fuente es todas las instrucciones para hacer el programa, 
pero usando ese lenguaje de programacion.

### Compilacion interprete o ejecucion

El codigo fuente debe convertirse en otro lenguaje que la maquina entienda.

Un compilador lee el programa y lo traduce todo al mismo tiempo, antes de 
ejecutar cualquiera de las instrucciones. En este caso, al programa de alto 
nivel se le llama el código fuente, y al programa traducido el código de 
objeto o el código ejecutable.

Un interprete hace lo mismo que un compilador pero al mismo momento en que 
se estan escribiendo las lineas de reglas de lenguaje de programacion.

### Tiempo de ejecucion

Es el momento que dura el programa ejecutando.. imprimir hola es tan rapido 
que es instantaneo pero hacer miles de calculos matematicos tomara mcuho mas 
tiempo, este tiempo se le llama "tiempo de ejecucion" o "Runtime".

### Ejecutar o compilar Python

Python se considera como lenguaje interpretado porque los programas 
se ejecutan por medio de un intérprete, JAVA fucniona de manera similar y 
el BASIC tambien funciona similar..

Existen dos maneras de usar el codigo o el lenguaje de programacion

#### modo de comando

En modo de comando el entorno Python esta en ejecucion y ofrece 
al usuario que ingrese reglas de programacion en lenguaje Python 
para que este muestra el resultado.

```
general@devel-venenux$ python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> print (1 + 1)
2
```

En este ejemplo, se ejecuto el interprete (comando `python`) despues 
abrio una nueva interfaz para ingreso de comandos, en esa consola se 
volvio ingresar una regla de programacion en lenguaje python ( se 
escribio la regla `print (1 + 1)` ) y despues le dimos enter para 
que el interprete mostrara el resultado (mostro el numero `2`).

#### modo de lotes

En modo de lotes mal llamado "guion" por los majo esnania, el 
entorno lee las reglas de programacion desde un archivo para ser 
ejecutas de manera automatica.

```
cat > python.py << EOF
print (1 + 1)
EOF
python python.py
2
```

En este ejemplo, se escribio una regla de programacion en lenguaje 
python ( se escribio la regla `print (1 + 1)` ) y despues usando el 
interprete mandamos a interpretar el archivo (comando `python python.py`) 
que el interprete mostrara el resultado (mostro el numero `2`).

### sintaxis

El término sintaxis se refiere a la estructura de cualquier programa 
pues son la forma en que se escriben las reglas que formaran un programa.

Se consideran declaraciones o expresiones correctamente estructuradas en 
un lenguaje (en este caso python). Esto se aplica tanto a los lenguajes 
de programación, donde el documento que tiene estas reglas (sintaxis) 
representa el código fuente, como a los lenguajes de marcado, donde el 
documento que tiene las reglas (en este caso datos) representa los datos.

Para la mayorıa de lectores, unos pocos errores sintácticos no son 
significatvos, y por eso pueden leer la poesı́a de e. e. cummings sin 
anunciar errores de sintaxis.

## depuracion

El proceso para corregir el programa. En python debido a ser de 
"alto nivel" es muy facil que se produzcan errores.

La ironia es que en Python es mas facil cometer un error que en los 
otros lenguajes, y por eso las herramientas de depuracion en python 
son muy amplias e incluso mucho mas desarrolladas.

### tipos de errores

Hay tres tipos de errores que pueden ocurrir en un programa:

1. **Error de sintaxis** el mas famoso y comun que ocurre en python, 
porque es un lenguaje fuertemente typado, su sintaxis cuida incluso 
los espacios y lugares en que esta ubicado una palabra. Lo que representa 
una ironia respecto otros lengaujes de programacion.
2. **Error de ejecucion** el programa compila pero la regla que se 
va ejecutar es imposible de obtener un resultado en el Runtime. Este tipo 
de errores aparece solo cuando el programa esta ejecutandose.
3. **Error de semantica** cuando compila y ejecuta pero resutlado incorrecto 
significa que no hay errores pero tampoco el resultado esperado, el 
programa ejecuta pero no muestra nada por ejemplo.

## Instalacion de python y herramientas

Instalarlo depende de que se realizara.

En sistemas Linux siempre esta instalado el CPython hoy el estandar Python.

En los otros sistemas hay que instalarlo a mano, es realmente tan facil 
como descargar el instalador y realizar el proceso en el OS respectivo.

### Herramientas obligatorias

En los inicios con solo instalar Python y llevar los archivos en un 
dispositivos de almacenaje externo era todo.

Hoy todo es en la nube casi que obligatoriamente y se debe usar un IDE.

* **Entorno y lenguaje** Este es el **Python** (todos los linux lo tienen) 
pero para otros sistemas ir a https://www.python.org/downloads/
* **IDE para codificar** Aqui habra un unico estandar y es **VSCode** ir 
a https://vscodium.com/#install y bajar hasta ver su distro o el OS.
* **control de distribucion** Aqui el estandar es **GIT** donde las 
distros Linux lo ofrecen y para el resto ir a https://git-scm.com/install/

Estas tres herramientas son olbigatorias, aunque funcionan en todos los OS, 
el despliegue y muchos agregados solo estan en algunos sistemas.

La mayoria de los agregados graficos estan solo en Windo y Mac, pero para 
la mayoria de sistemas como desplegar en un server de IA solo es en Linux, 
por lo que se recomienda utilizar siemrpe Linux ya que es donde termina 
siemrpe siendo desplegado.

#### Herramientas con python instaladas

Python no es solo un programa que compial y ejecuta, tiene varias herramientas 
parte de su estructura de ejecucion y tambien para manejarlo

* Compilador e interprete: este es el programa en si `python`
* Entorno virtual: premite ejecutar en un directorio separado, es `venv`
* Modulos de funcionalidad: son programs que agregan mas funcionalidades a reusar
* Gestor de modulos: permite instalar modulos al python, es `pip`
* Editor IDE python: ya hoy en desuso, es `idle`

NOTA: los OS linux y tipo Unix deben instalar aparte el PIP.

#### Herramientas obligatorias instaladas

Adicional al instalar las herramientas obligatorias estas tienen 
importancia adicional:

* **IDE** la industria hoy programa usando el comando `vscodium` que aunque 
tiene una entrada en menu en los OS, casi todos los tutoriales y videos 
mencionan ejecutar el comando justo en el disrectorio donde tiene el codigo.
La importancia de esta herramienta radica en la cantidad de extensiones que 
muchos otros desarrolladores usan en equipo y en trabajo distribuido.

* **GIT**: la industria hoy usa un control de versiones que hoy se convierte 
en un gestor de distribucion de el codigo fuente, aunque usaremos git, aun 
hay sistemas y equipos de trabajo que usan mercurial, raras excepciones se 
vera el uso de el ya casi extinto "subversion" solo para sistemas Windos.

## Modulos de python

Esto es como los plugins/packs para los que usan juegos...
Esto es como las bibliotecas para los que aprendieron C ...
Esto es como los imports para los que aprendierton JAVA ...

### Que son los modulos.

Un módulo en Python es un archivo con extensión .py que contiene código 
reutilizable, para nuevas funciones y variables, diseñado para organizar 
y estructurar programas.

Permiten dividir proyectos grandes en partes manejables, facilitando la 
importación de funcionalidades específicas (ej. math, os) sin recargar 
la memoria.

### Modulos y paquetes

Un módulo es un solo archivo .py, mientras que un paquete es un directorio 
que contiene varios módulos.

### Como se usan

Deben ser instalados despues de haber isntalador Python, y entonces usar 
el comando pip para los modulso listos, o sino tener que compilarlos.

* Modulos estandar: Estos son los que ya estan incluidos en Python.
* Modulos externos: Estos son los que se instalan con PIP
* Modulos incluidos: Estos son los que el usuario crea en su proyecto.

