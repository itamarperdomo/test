# curso de como programar con python MOD 1

- [Introduccion](#introduccion)
  - [Caracteristicas de python](#caracteristicas-de-python)
- [PORQUE PYTHON](#porque-python)
- [Porque la comparacion con C o Java](#porque-la-comparacion-con-c-o-java)
  - [Convertir o pasar de python a otro lenguaje](#convertir-o-pasar-de-python-a-otro-lenguaje)
- [Ejemplo de porque tuvo exito.](#ejemplo-de-porque-tuvo-exito.)
    - [Ejemplo en java](#ejemplo-en-java)
    - [Ejemplo en BASIC](#ejemplo-en-basic)
    - [Ejemplo en Python](#ejemplo-en-python)
    - [Si basic es facil porque se usa python](#si-basic-es-facil-porque-se-usa-python)
    - [Si java es potente porque se usa Python](#si-java-es-potente-porque-se-usa-python)
- [Programas y sistemas](#programas-y-sistemas)
  - [Lenguaje de programacion](#lenguaje-de-programacion)
  - [Compilacion interprete o ejecucion](#compilacion-interprete-o-ejecucion)
  - [Tiempo de ejecucion](#tiempo-de-ejecucion)
  - [Ejecutar o compilar Python](#ejecutar-o-compilar-python)
    - [modo de comando](#modo-de-comando)
    - [modo de lotes](#modo-de-lotes)
  - [Sintaxis](#sintaxis)
- [depuracion](#depuracion)
  - [tipos de errores](#tipos-de-errores)
- [Instalacion de python y herramientas](#instalacion-de-python-y-herramientas)
  - [Herramientas obligatorias](#herramientas-obligatorias)
    - [Herramientas con Python instaladas](#herramientas-con-python-instaladas)
    - [Herramientas obligatorias instaladas](#herramientas-obligatorias-instaladas)
- [Modulos de python](#modulos-de-python)
  - [Que son los modulos.](#que-son-los-modulos.)
  - [Modulos y paquetes](#modulos-y-paquetes)
  - [Como se usan](#como-se-usan)
- [En donde programar y porque entornos tipo Unix](#en-donde-programar-y-porque-entornos-tipo-unix)
- [Nateraleza de python o paradigma](#nateraleza-de-python-o-paradigma)
  - [paradigma de programacion](#paradigma-de-programacion)
  - [Python es multiparadigma](#python-es-multiparadigma)
  - [Programacion orientada objetos](#programacion-orientada-objetos)
    - [1 La Idea vs La Existencia (clase e instancia)](#1-la-idea-vs-la-existencia-(clase-e-instancia))
    - [2 Identidad y accion (atributos y metodos)](#2-identidad-y-accion-(atributos-y-metodos))
    - [3 Ejemplo de una clase, atributos y metodos](#3-ejemplo-de-una-clase,-atributos-y-metodos)
    - [4 herencia y polimorfismo](#4-herencia-y-polimorfismo)
- [Siguiente a leer](#siguiente-a-leer)

## Introduccion

Python es creado por Guido van Rossum en los 90 cuyo nombre está 
inspirado en los cómicos ingleses “Monty Python” por eso su sintaxis exagerada.

Pero Python no es adecuado sin embargo para la programación de bajo 
nivel o para aplicaciones en las que el rendimiento sea crítico. 
Esto lo mencionan libros como "Python Para Todos" (Raul G Duque),

Su éxito se debe a que lo empezó usar Google y la NASA cuando cambiaron 
todos los sistemas a Linux, python era el único lenguaje que tenia las 
mismas ventajas de Java pero que no requería tanta preparación para usarlo.

### Caracteristicas de python

TEXTO PARA LOS QUE NO TIENEN VIDA SOCIAL:
Se trata de un lenguaje interpretado o de script de programación:

1. con tipificado dinámico, fuertemente tipado
2. multiplataforma
3. orientado a objetos.

TRADUCCION PARA TONTOS O GENTE CON FAMILIA FELIZ:
Idioma para crear programas que exagera la forma en que se escribe:

1. fuertemente correctivo, si te falta un espacio esta malo.
2. multiplataforma, salvo a los usuarios de sistemas operativos ineficientes.
3. deja representar cosas y situaciones de la vida real.

## PORQUE PYTHON

Era menos complicado que C y aun mas fácil que Java.

## Porque la comparacion con C o Java

Cuando se implementó tecnología en institutos como la NASA o 
en las universidades, los profesores e investigadores no 
tenían ni podían perder tiempo en complicados conceptos de C o Java.

Al igual que Tanto C como Java requieren de complicaciones para 
que un simple proyecto se pueda portar a otras plataformas.

### Convertir o pasar de python a otro lenguaje

Los programas elaborados en Python parecen seudocódigo, (que son fáciles 
de seguir como si fuera contar una historia).

Debido a su forma de procesamiento, al ser casi como escribir una 
historia, muchos programadores hacen el código en Python primero 
y después traducen esto a otro lenguaje o tecnología.

Esto es porque Python el lenguaje como tal cumple con la gramática 
de un seudocodigo, porque como se menciono, su sintaxis es fuerte.

## Ejemplo de porque tuvo exito.

Porque los sistemas desplegados (Symbian y Windos) tenían que 
en un inicio pagar licencia si se usaba Java, si era C entonces 
el código fuente tenia que ser muy especifico según la biblioteca 
o funciones de cada sistema operativo.

#### Ejemplo en java

```python
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hola mundo");
    }
```

#### Ejemplo en BASIC

```basic
PRINT "Hola mundo"
END
```

#### Ejemplo en Python

```bash
print "Hola, Mundo"
```

#### Si basic es facil porque se usa python

BASIC tiene las siguientes tres inconvenientes terribles

1. Es un lenguaje pobre, secuencial, no hay objetos
2. Solo funciona en Windos, los sistemas de IA solo funcionan en Linux.
3. Con estas dos, python funciona en ambos.

Significa que los científicos podían hacer script pequeños en 
el python en sus maquinas Windos inestables y después despegarlas 
en las supercomputadores Linux sin muchos cambios.

#### Si java es potente porque se usa Python

JAVA tiene dos grandes inconvenientes:

1. Es un lenguaje complejo, abstracto, derivado de C
2. Funciona en todos los sistemas, pero requiere licencias.

Desplegar el código java no solo implicaba que cada científico y 
cada persona tuviera que estudiar complicados estándares y no 
tenían tiempo para eso.

## Programas y sistemas

La palabra implica programación. Una programación es coordinar tareas.

Un programa es un conjunto de tareas para lograr una meta.

En las computadores un programa son instrucciones (tareas) que 
logran una funcionalidad (tarea) como mostrar el texto (meta).

Un sistema es muchos programas coordinando muchas funcionalidades.

Hoy dia estos son sistemas tanto web (nube) como locales (escritorio)

### Lenguaje de programacion

El lenguaje es la forma en que se escribe esas reglas del programa.

El lenguaje no es lo importante sino la lógica implícita.

Los lenguajes son de alto nivel (Python, BASIC, C++), asi como 
los lenguajes de bajo nivel (C ANSI, assembler).

Código fuente es todas las instrucciones para hacer el programa,
pero usando ese lenguaje de programación.

### Compilacion interprete o ejecucion

El código fuente debe convertirse en otro lenguaje que la maquina entienda.

Un compilador lee el programa y lo traduce todo al mismo tiempo, antes de 
ejecutar cualquiera de las instrucciones. En este caso, al programa de alto 
nivel se le llama el código fuente, y al programa traducido el código de 
objeto o el código ejecutable.

Un interprete hace lo mismo que un compilador pero al mismo momento en que 
se están escribiendo las lineas de reglas de lenguaje de programación.

### Tiempo de ejecucion

Es el momento que dura el programa ejecutando.. imprimir hola es tan rápido 
que es instantáneo pero hacer miles de cálculos matemáticos tomara mucho mas 
tiempo, este tiempo se le llama "tiempo de ejecución" o "Runtime".

### Ejecutar o compilar Python

Python se considera como lenguaje interpretado porque los programas 
se ejecutan por medio de un intérprete, JAVA funciona de manera similar y 
el BASIC también funciona similar..

Existen dos maneras de usar el código o el lenguaje de programación:

#### modo de comando

En modo de comando el entorno Python esta en ejecución y ofrece 
al usuario que ingrese reglas de programación en lenguaje Python 
para que este muestra el resultado.

```python
general@devel-venenux$ python
Python 3.14.3 (main, Feb 13 2026, 15:31:44) [GCC 15.2.1 20260209] on linux
>>> 2
2
```

En este ejemplo, se ejecuto el interprete (comando `python`) después 
abrió una nueva interfaz para ingreso de comandos, en esa consola se 
volvió ingresar una regla de programación en lenguaje python ( se 
escribió la regla `2` ) y después le dimos enter para 
que el interprete mostrara el resultado (mostró el numero `2`). 

#### modo de lotes

En modo de lotes (mal llamado "guion" por los majo España), el 
entorno lee las reglas de programación desde un archivo para ser 
ejecutas de manera automática.

```bash
cat > miarchivo.py << EOF
2
EOF
python miarchivo.py
```

En este ejemplo, se crea un archivo (llamado `miarchivo.py` con `cat`) y 
coloca dentro el código (la regla `print (1 + 1)`) y después para 
ejecutar mandamos a interpretar el archivo (comando `python miarchivo.py`) 
(no muestra `2` pero no da error, ya que no se le intica imprimir nada).

### Sintaxis

El término sintaxis se refiere a la estructura escrita de un programa 
pues son la forma en que se escriben las reglas que formaran un programa.

Se consideran declaraciones o expresiones correctamente estructuradas en 
un lenguaje (en este caso python). Esto se aplica tanto a los lenguajes 
de programación, donde el documento que tiene estas reglas (sintaxis) 
representa el código fuente, como a los lenguajes de marcado, donde el 
documento que tiene las reglas (en este caso datos) representa los datos.

Para la mayoría de lectores, unos pocos errores sintácticos no son 
significativos, y por eso pueden leer la poesía de E. Cummings sin 
anunciar errores de sintaxis.

## depuracion

El proceso para corregir el programa. En python debido a ser de 
"alto nivel" es muy fácil que se produzcan errores.

La ironía es que en Python es mas fácil cometer un error que en los 
otros lenguajes, y por eso las herramientas de depuración en python 
son muy amplias e incluso mucho mas desarrolladas.

### tipos de errores

Hay tres tipos de errores que pueden ocurrir en un programa:

1. **Error de sintaxis** el mas famoso y común que ocurre en python, 
   porque es un lenguaje fuertemente tipificado, su sintaxis cuida incluso 
   los espacios y lugares en que esta ubicado una palabra. Lo que representa 
   una ironía respecto otros lenguajes de programación.
2. **Error de ejecución** el programa compila pero la regla que se 
   va ejecutar es imposible de obtener un resultado en el Runtime. Este tipo 
   de errores aparece solo cuando el programa esta ejecutándose.
3. **Error de semántica** cuando compila y ejecuta pero resultado incorrecto 
   significa que no hay errores pero tampoco el resultado esperado, el 
   programa ejecuta pero no muestra nada por ejemplo.

## Instalacion de python y herramientas

Instalarlo depende de el sistema operativo (SO) donde se trabajara.

En sistemas Linux siempre esta instalado el CPython hoy el estándar Python.

En los otros sistemas hay que instalarlo a mano, es realmente tan fácil 
como descargar el instalador y realizar el proceso en el OS respectivo. 
Solo se va al sitio de descarga y se ejecuta el instalador.

Al instalarlo no es solo un compilador o un interprete, es un conjunto de 
herramientas, en las siguientes secciones se detalla "que" se va 
a necesitar y como se va necesitar.

### Herramientas obligatorias

En los inicios con solo instalar Python y llevar los archivos en un 
dispositivos de almacenaje externo era todo lo necesario.

Hoy todo es en la nube casi que obligatoriamente y se debe usar un IDE. 
Las siguientes herramientas son obligatorias y se indica donde se obtienen.

- **Entorno y lenguaje** Este es el **Python** (todos los Linux lo tienen)
  pero para otros sistemas ir a https://www.python.org/downloads/ 
- **IDE para codificar** Aqui habra un unico estandar y es **VSCode** ir
  a https://vscodium.com/#install y bajar hasta ver su distro o el OS. 
- **control de distribucion** Aquí el estándar es **GIT** incluido en Linux,
  los otros OS debemos ir a https://git-scm.com/install/

Estas tres herramientas son obligatorias, aunque funcionan en todos los OS,
el despliegue y muchos agregados solo están en algunos OS.

La mayoría de los agregados gráficos están solo en Windo y Mac, pero para
la mayoría de sistemas como desplegar en un server de IA solo es en Linux,
por lo que se recomienda utilizar siempre Linux ya que es donde termina
siempre siendo desplegado.

#### Herramientas con Python instaladas

Python no es solo un programa que compila y ejecuta, tiene varias herramientas 
parte de su estructura de ejecución y trabajo que detallaremos asi:

- Compilador e interprete: el comando `python` este es el corazón.
- Entorno virtual: el comando `venv` permite ejecutar en un directorio separado.
- Modulos de Python: son programs que agregan mas funcionalidades a reusar
- Gestor de módulos: el comando `pip`, que permite instalar módulos al python
- Editor IDE Python: el comando `idle`, ya hoy esta en desuso.

NOTA: los OS Linux y tipo Unix deben instalar aparte el PIP.

#### Herramientas obligatorias instaladas

Adicional al instalar las herramientas obligatorias estas tienen
importancia adicional:

- **IDE** la industria hoy programa usando el comando `vscodium` que aunque 
  tiene una entrada en menu en los OS, casi todos los tutoriales y videos 
  mencionan ejecutar el comando justo en el directorio donde tiene el código. 
  La importancia de esta herramienta radica en la cantidad de extensiones que 
  muchos otros desarrolladores usan en equipo y en trabajo distribuido. 

- **GIT**: la industria hoy usa un control de versiones el comando `git` que 
  hoy se convierte en un gestor de distribucion de el código fuente, aunque 
  aun hay sistemas y equipos de trabajo que usan "mercurial", y raramente 
  se vera el uso de el ya casi extinto "subversion" solo para sistemas Windos.

## Modulos de python

Esto es como los plugins/packs para los que usan juegos...

Esto es como las bibliotecas para los que aprendieron C ...

Esto es como los imports para los que aprendieron JAVA ...

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

Deben ser instalados después de haber instalador Python, y entonces usar 
el comando pip para los módulos listos, o sino tener que compilarlos.

- Módulos estándar: Estos son los que ya están incluidos en Python.
- Módulos externos: Estos son los que se instalan con PIP
- Módulos incluidos: Estos son los que el usuario crea en su proyecto.

## En donde programar y porque entornos tipo Unix

Los codigos fuentes se colocan en archivos, y estos son ejecutados o 
precompilados por el programa Python.

El problema es cuando se maneja entornos mas complejos o variables.

Los proyectos son desplegados en **sistemas Docker o Kuberness**. Estos 
aunque funcionan en Windos requieren de configuraciones e incluso rutas 
especificas que nunca son comunes entre los distintos desarrolladores. El 
que trabaja en windos entorpece el trabajo de los demas en estos casos.

El siguiente contenido de archivo es un codigo Python que muestra "hola":

``` python
2
```

Sin embargo cuando se trabaja con sistemas grandes nos encontraremos con 
una linea al inicio como este ejemplo.

``` python
#!/usr/bin/env python
2
```

Esto se denomina "shebang" o "hashbang", y esto unicamente funciona en 
sistemas Unix o Linux.

## Nateraleza de python o paradigma

En programacion un paradigma es la forma de la logica en que se fabrican 
las "reglas" (instrucciones del codigo fuente) del lenguaje.

No confundamos la logica del programa (que realiza y como lo llega lograr) 
con la logica del lenguaje y su engine (como se escribe y como se interpreta).

### paradigma de programacion

Los paradigmas de programación son enfoques, estilos o conjuntos de reglas 
que estructuran cómo se conceptualiza, diseña y escribe el código de software 
para resolver problemas. Se clasifican principalmente en:

* **imperativos** cómo hacerlo, paso a paso
  * **orientada a procesos** como procedimientos que se llaman entre sí 
    que relizan los calculos sin que estos tengan uan naturaleza dada, 
    un numero puede ser natural asi como flotante con solo remover sus 
    decimales, los datos son solo herramientas para procesar un resultado.
  * **orientado al objeto** como representaciones que contienen tanto la 
    estructura de datos como el comportamiento asociado, utiliza estructuras 
    de datos que consisten en campos y métodos de datos junto con sus 
    interacciones (objetos) para diseñar programas. Significa que un objeto 
    no se puede convertir en otro a menos que el mismo objeto defina en su 
    propia estructura (naturaleza) una manera de procesar dicha equivalentcia.
* **declarativos** qué hacer, describiendo el problema para su resultado
  * **data languaje / SQL** es el mayor ejemplo, SQL emplea funciones 
    sin orientarse a representar naturaleza o resultados, puesto solo 
    necesita el resutlado como tal y no que este este verificado de donde 
    viene ni para que sera usado.

### Python es multiparadigma

Python no es puro orientado a objetos. Por ende NO es orientado objetos.

Python puede ser usado para proyectos usando orientacion objetos asi como 
solo funciones y modulos secuencialmente. Tambien mexclar ambos paradigmas.

### Programacion orientada objetos

Este paradigma es soportado por Python y se usa las siglas OOP de su 
nombre en ingles Object Orient Programing.

#### 1 La Idea vs La Existencia (clase e instancia)

En el lenguaje de programacion tenemos la lista de reglas que dice cómo 
debe ser algo. Esa lista no se puede tocar, es solo un pensamiento.

En la programacion orientada objetos usamos esa lista para crear algo real.

Es decir "la lista" es una idea en la cabeza y cuando hacemos una lista 
en una hoja de papel estamos "usando la misma lista(idea) muchas veces 
para crear listas(reales) de la idea", pero cada una es independiente.

La idea de lista en tu cabeza es lo que llamamos "clase" que define el 
objeto. Una clase no es tangible, es una representacion (la idea)

Al crear una lista en uan hoja de papel estamos "instanciando" la idea.
Llevar a cabo la idea de tu cabeza se le llama "instanciar" la clase.

#### 2 Identidad y accion (atributos y metodos)

En el mundo de la programación de objetos, la identidad (o descripción) 
se llama Atributos. Son los datos o la información que esa "existencia" 
posee o "se le atribuye" (a la instancia de la idea, la lista en el papel).

La idea es una en tu cabeza pero muchos pueden llevarla a cabo, los atributos 
distinguen una instancia de otra (cada lista tendra atributos distintos)

La identidad responde a la pregunta: "¿Cómo es?" o "¿Qué tiene?".

Para acceder a estos atributos estan los metodos que definiran las acciones 
que cada lista (idea instanciada o hecha realidad) puede llevar a cabo.

#### 3 Ejemplo de una clase, atributos y metodos

* Perro (clase)
  - GoldenRetriever (instancia, de la clase perro)
    - Poro (atributo nombre)
      - miNombre (metodo para obtener el nombre
      - ponerNombre (metodo para darle otro nombre
    - Dorado (atributo color)
      - miColor (metodo para obtener el nombre
      - ponerColor (metodo para darle otro nombre

#### 4 herencia y polimorfismo

* Perro (clase padre}
  - Lobo (clase QUE VA HEREDAR todo de padre, pero agrega mas)
    - Salvage (atributo nuevo que no tiene la clase padre)

Una confusion que siempre ocurre es que se cree que uan clase padre 
al ser inicial tiene mas cosas que las clases hijas. esto es totalmente 
lo contratrio, en OOP la herencia es para "mutar" del padre.

Realmente un "padre" nunca tiene mas "features" que un "hijo", ya que 
en la vida real y en la biologia los hijos tiene mutaciones leves de los 
padres al no ser copias exactas de los mismos.


## Siguiente a leer

* [curso-minimo-python-2-lenguaje.md](curso-minimo-python-2-lenguaje.md)
* https://t.me/latam_programadores




