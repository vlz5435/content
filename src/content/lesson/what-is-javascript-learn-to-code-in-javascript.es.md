---
title: "¿Qué es JavaScript? Aprende a Programar en JavaScript"
subtitle: "Conozca qué es JavaScript, todos están hablando de ello y, probablemente, ya sepa que es hora de aprender a programar en JavaScript para llevar las cosas al siguiente nivel."
cover: "https://ucarecdn.com/4cc6fa0b-2530-4052-aa7e-8dac03788ac3/"
textColor: "white"

date: "2018-02-11"
tags: ["javascript"]
---

## **Pero, Qué es programar?**
***

**La programación no es HTML, CSS o Posición y visualización ...** Esos idiomas no fueron diseñados para desarrolladores, son la única forma en que tenemos que renderizar cosas en un navegador.

**La Programación es hacer *que la computadora* "obedezca"…**

Todo el mundo usa las computadoras por diferentes razones. Algunas computadoras se crean para ayudar a las personas en su oficina (como las computadoras personales), otras para mantener una habitación a una temperatura específica (como [NEST](https://nest.com/es/)), otras están hechas para caminar En Marte, y muchas más cosas.

No importa para qué está hecha la computadora, la misma base de su existencia es la misma: seguir los comandos. En este capítulo, aprenderás 5 cosas básicas que necesitarás para entender cualquier computadora moderna a través del código.

## **Variables**
***

<iframe width="830" height="467" src="https://www.youtube.com/embed/Q-eob0WBKs0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div align="right"><small><a href="https://www.youtube.com/embed/Q-eob0WBKs0">Click aquí para abrir el video en una nueva ventana</a></small></div>

Las variables no son un concepto nuevo, cualquiera que sepa matemáticas está familiarizado con el concepto de variables.

Una variable es un contenedor en el que puede almacenar cualquier dato. Por ejemplo, puedes tener la siguiente variable:

```javascript
var age = 24;
```

![what is javascript](https://ucarecdn.com/ecb49b67-f513-49b3-bd4a-dd7cc44e9bce/)

Con prácticamente cualquier lenguaje de programación, puede crear tantas variables como desee o necesite. Para comenzar, debe **declarar el nombre de esa variable** usando el término: * var * seguido de un nombre _único_ (relativo al documento/proyecto).

El **nombre de la variable** es la forma más efectiva que tenemos de describir el contenido de la variable, así que úsalo sabiamente. Es importante elegir un nombre que te indique claramente (y a otros programadores) los datos que se almacenan en la variable. Si elegimos un nombre malo o ambiguo, nuestro código será casi imposible de entender, por lo que se vuelve inutilizable. Por ejemplo, digamos que cambiamos el nombre de nuestra variable "age" a `a`, que sería:

```javascript
var a = 24 ;
```

Como puedes ver arriba, el nuevo nombre de la variable no nos dice nada sobre los datos que se almacenan y por qué los estamos utilizando.

La elección del nombre para tu variable realmente importa, por lo que te rogamos que no utilice nombres genéricos. ¡Se descriptivo! Un nombre vago dificultará la comprensión del propósito de la variable, especialmente para otros programadores (incluido su futuro yo).

## **Asignando un valor a las variables**
***

Como desarrolladores, podemos establecer el valor de una variable en cualquier momento utilizando el operador `=`. No es necesario establecer un valor cuando declara una variable por primera vez. Puedes establecer, o restablecer (anular) el valor tantas veces como desees, cuando lo desees. El valor siempre será el último que establezcas. A continuación se muestran algunos ejemplos sobre cómo establecer valores en variables:

```javascript
var a = 24;
  a = 25;
  a = 80;

var b ;
  b = 9 ;
  b = 108 ;
```

### `var` vs.  `let`  vs. `const`
***

Como aprendimos anteriormente, usamos la palabra clave `var` para declarar una variable. Hay otras dos palabras clave que también podemos usar para declarar variables: ***const & let***. Las principales diferencias entre estos tipos de variables tienen que ver con el alcance.

***Const***:  Esta palabra clave se utiliza cuando el valor permanece constante durante toda la vida del script. El valor de la variable declarada con esta palabra clave nunca se puede cambiar. Si intenta cambiarlo, se producirá un error.

***Let***:  Los valores solo están limitados al alcance del bloque de código (cualquier cosa entre paréntesis) en el que se declara. Si una función tiene más de un bloque de código, la variable se considerará una variable diferente en cada bloque.

***Var***:  Su alcance está dentro de la función en la que se declara. Esto significa que la variable se mantendrá igual durante toda la función, incluso si hay más de un bloque de código en la función.

[[info]]
|:link: [Lee más sobre `*var*`, `let` y `const`](http://wesbos.com/let-vs-const/)

Los valores variables están sujetos a cambios en el tiempo. Para recuperar un valor variable, puede imprimir el valor en la pantalla en cualquier momento. Cada idioma tiene sus propios métodos para imprimir; Así es como lo haces en JavaScript:

<iframe src="https://repl.it/F0R2/1?lite=true" frameborder="0" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" width="100%" height="400px" scrolling="no" allowtransparency="true" allowfullscreen="true"></iframe>

<div align="right"><small><a href="https://repl.it/F0R2/1?lite=true" >Click aquí para abrir el video en una nueva ventana</a></small></div>



## **Tipos de Datos**
***
Las variables pueden tener diferentes tipos de valores. Algunos de ellos están disponibles solo en lenguajes de programación específicos, pero casi todos tienen los siguientes tipos

|**Data-Type**   |**Posible Valores**   |**Descripción**   |
|:---------------|:--------------------|:-----------------|
|Booleano         |Verdadero \| Falso         |Los booleanos están destinados a operaciones lógicas. Si le preguntas a una computadora algo como: "¿X es igual a 3?" Responderá con un booleano (verdadero o falso).   |
|Cadena        |Cualquier serie de caracteres     |Las cadenas son la única forma en que tenemos que almacenar palabras (series de caracteres). Nota: las cadenas deben estar encerradas entre comillas.  |
|Número    |Solo números     |Números enteros, números negativos, números decimales, flotadores, etc. Todos los tipos posibles de números. <br> Nota: Si incluye un número entre comillas, JavaScript lo tratará como una cadena. |
|Indefinido     |El vacío     |Cuando una variable no tiene un valor asignado, queda indefinida.   |
|Arreglo     |Una lista de cualquier tipo de valor.   |Una sucesión de cualquier tipo de valores. Pueden ser tipos mixtos de valores; por ejemplo: [2, 3, ‘Word’, 2, 1, null, 232, 5, 3, 23, 234, 5, ‘hello’].     |
|Objetos    |Cualquier objeto    |Puedes crear tus propios tipos de datos con operaciones más complejas. Hablaremos más sobre esto más adelante.  |
|Nulo     |Solo nulo    |Se utiliza para especificar cuándo la base de datos o cualquier otra función no devuelve nada.   |

<iframe src="https://repl.it/F05K/3?lite=true" frameborder="0" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" width="100%" height="400px" scrolling="no" allowtransparency="true" allowfullscreen="true"></iframe>

<div align="right"><small><a href="https://repl.it/F05K/3?lite=true">Click aquí para abrir el video en una nueva ventana</a></small></div>




## **Operaciones**
***

¿Qué operaciones puedo hacer con las variables? Dependiendo del tipo de datos tienes algunas posibilidades diferentes:

+ Los números son fáciles - puedes hacer cualquier operación matemática que desees.
+ Las cadenas se pueden concatenar (fusionar), dividir, convertir a mayúsculas o minúsculas, etc.
+ No se puede hacer mucho con los tipos de datos nulos, booleanos y no definidos.
+ Hablaremos de Arreglos y Objetos en una sección diferente. Requieren mucha más atención.

## **Funciones**
***

Las funciones son piezas de código que se pueden reutilizar varias veces durante el tiempo de ejecución, independientemente de su posición en el código. Hay cientos de razones para usar funciones, pero aquí están las 2 más importantes:

+ Divide y conquista: siempre es más fácil dividir tus problemas en varios problemas más pequeños. Esto se convertirá en su mayor desafío a la hora de resolver problemas complejos. Las funciones serán tus mejores herramientas para la abstracción.
+ Reutilización: cualquier desarrollo normal tomará al menos 5,000 líneas de código. Es redundante e ineficiente seguir escribiendo el mismo código una y otra vez.

## **Declarar una Función**
***

Para declarar una función en JavaScript, debes comenzar a utilizar la palabra `function` seguida del nombre que desea para esa función.

Luego debes especificar los parámetros (entradas) que la función tendrá entre paréntesis.

Luego, abrirás un corchete y escribirás el código que tu función siempre debe realizar. Una vez que haya terminado, cierre el corchete y ahora tu función está lista para ser utilizada.

**Nota:**  Para devolver algo, use la palabra `return` en cualquier momento dentro del contenido de su función (entre corchetes).

![learn to code in javascript](https://ucarecdn.com/0c4fa020-02f6-4ec0-bfeb-a6292145a153/)

```javascript
function multiply (param1, param2)
{
    return (param1 * param2);
}
```
<iframe src="https://repl.it/F10t/0?lite=true" frameborder="0" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" width="100%" height="400px" scrolling="no" allowtransparency="true" allowfullscreen="true"></iframe>

<div align="right"><small><a href="https://repl.it/F10t/0?lite=true">Click aquí para abrir el video en una nueva ventana</a></small></div>

## **Parámetros y Alcance de la Función**
***

El alcance de una variable determina dónde está disponible esa variable para ser utilizada. Hay dos tipos principales de ámbitos:

### Variables Locales

Una variable local está disponible solo dentro del alcance de las llaves más cercanas. Por ejemplo, las variables que se pasan como parámetros a funciones, solo están disponibles dentro del contenido de esa función en particular.

### Variables Globales

Si declaras una variable al comienzo de tu código, estará disponible en todo el código, incluso durante el contenido de cualquier función en particular.

<iframe src="https://repl.it/F10t/2?lite=true" frameborder="0" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" width="100%" height="400px" scrolling="no" allowtransparency="true" allowfullscreen="true"></iframe>

<div align="right"><small><a href="https://repl.it/F10t/2?lite=true">Click aquí para abrir el video en una nueva ventana</a></small></div>

## Operaciones lógicas
***

Las computadoras piensan todo en blanco o negro. Todo es verdadero o falso. Todas las decisiones en una computadora se reducen a un simple **booleano**. Puedes preparar una computadora para resolver problemas particulares si escribes un código que haga las preguntas adecuadas para resolver ese problema.

Por ejemplo, si quiero una computadora para dar dulces solo a niños mayores de 13 años de edad, puedo indicarle a la computadora que pregunte:

 **¿La edad de este niño es mayor de 13 años? ¿Si o no?**

**En JavaScript, puedes indicar a la computadora que realice las siguientes operaciones lógicas:**

|**Operación**  |**Sintaxis**   |**Ejemplos**   |
|:--------------|:--------------|:--------------|
|Igual a     |==             |Es 5 == 5? True!<br>Es 5 == 4? False!<br>Es 5 == '5'? True!    |
|No Igual a    |!=             |Es 5 != 5? False!<br>Es 5 != '5'? False!<br>Es 1 != 'Hello' True!   |
|Mayor que   |>              |Es 5 > 5? False!<br>Es 6 > 3? True!    |
|Menos que    |<              |Es 6 < 12? True            |
|Mayor o igual |>=             |Es 6 <= 6? True<br>Es 3 <= 6? True    |
|Menor o igual  |<=            |Tienes la idea 🙂       |

Para crear operaciones realmente útiles, puedes combinar varias operaciones en la misma pregunta usando AND, OR y NOT.

Puedes agrupar las operaciones lógicas entre paréntesis y también usar paréntesis anidados para varias operaciones al mismo tiempo.

|**Operación**   |**Sintaxis**   |**Ejemplos**   |
|:---------------|:--------------|:--------------|
|AND             |&&             |Con AND, ambos lados TIENEN QUE SER TRUE para que todo se convierta en realidad.<br>Es (5 == 5 && 3 > 1) ? True!<br>Es ('Ramon' == 'Pedro' && 2 == 2) ? False!    |
|OR     |\|\|     |Es ('Oscar' != 'Maria' OR 2 != 2)? True!<br>Es (5 == '5' AND 'Ramon' != 'Pedro') OR (2 == 2)? True!   |
|NOT     |!     |NOT será exactamente lo contrario del resultado del operador lógico:<br>Es !(5 > 5)? True!<br>Is !(True)? False!    |


## **Controla el Flujo de Tú Código**
***

Bien, ahora es cuando todo empieza a ponerse divertido! Para controlar el flujo de tu aplicación, tendrás varias opciones y las utilizarás cada día. Por lo tanto, debes sentirte cómodo usándolas.

### If…else…

La primera herramienta que tienes es el condicional `if ... else`. Es muy fácil. Puedes decirle a la computadora que omita cualquier parte de tu código dependiendo del valor actual de sus variables.

La instrucción `if` te permite ejecutar un fragmento de código si se cumplen ciertas condiciones (o son verdaderas). La declaración "else" ejecutará un fragmento de código alternativo en caso de que la condición sea falsa.
```javascript
if (number < 18) {
    document.write("Hello");
} else {
     document.write("Good bye!");
}
```

## **Switch**
***

Similar a if ... else ... pero un poco más organizado. Aquí especificará todos los escenarios de casos posibles, incluido el "escenario predeterminado" que ocurrirá si no ocurre ninguno de los otros escenarios.

<iframe src="https://repl.it/F2EK/5?lite=true" frameborder="0" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals" width="100%" height="400px" scrolling="no" allowtransparency="true" allowfullscreen="true"></iframe>

<div align="right"><small><a href="https://repl.it/F2EK/5?lite=true">Click aquí para abrir el video en una nueva ventana</a></small></div>

[[info]]
|Usa `switch` en lugar de` if` cuando: <br> <br> • Estás comparando varias condiciones posibles de una expresión y la expresión en sí no es trivial. • Tienes múltiples valores que pueden requerir el mismo código . <br> • Tienes algunos valores que requerirán esencialmente toda la ejecución de otro valor, más solo unas pocas declaraciones. <br> <br> Utiliza `if` en lugar de` switch` cuando: <br> <br> • Deseas probar la veracidad de una expresión. <br> • Solo tienes una única prueba afirmativa. <br> • Necesitas evaluar diferentes expresiones para cada rama.


## While
***

Es posible hacer un bucle de un segmento de su código tantas veces como desee o necesite. Los bucles son una de las herramientas más importantes para los desarrolladores en estos días.

Imagina que estás dentro de un ascensor: el ascensor debe girar en bucle por los pisos hasta que alcance el piso específico que deseas.

Un bucle `while` ejecutará un bloque de código siempre que una condición sea verdadera. Una vez que la condición devuelve falso, el bucle dejará de ejecutar el bloque de código.

```javascript
var sum = 0;
var number = 1;
while (number <= 50) {
  sum += number;
  number++;
}
console.log("Sum = " + sum);
```

## For
***

`For` es similar a` while,` con la única diferencia de que debe especificar la condición de detención desde el principio. Por esa razón, `for` es un poco más organizado y más fácil de entender.

Nota: cuando realice un bucle, asegúrese de que la declaración finalmente devuelva falso para evitar un bucle infinito. En un bucle infinito, el código se ejecuta indefinidamente y causará que su navegador se bloquee.

<iframe width="578" height="325" src="https://www.youtube.com/embed/TSMzvFwpE_A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div align="right"><small><a href="https://www.youtube.com/embed/TSMzvFwpE_A">Click aquí para abrir el video en una nueva ventana</a></small></div>


```javascript
for (var i = 0; i < 10; i++) {
    document.write("This is number" + " " + i);
}
```

## For..in
***

Los bucles `For… in` pueden usarse para recorrer en bucle las propiedades de un objeto. Dentro de los paréntesis, puedes establecer cualquier nombre para representar la información dentro del objeto, y luego incluir el nombre del objeto:

for (var in object)<br> {
code block to be executed
}

```javascript
var dog = {
  species: "Great Dane",
  size: "Extra Large",
  age: 3 ,
  name: "Rocky"

}

for(items in dog){
  console.log(dog[items]);
}
```

## **Entonces ... dime, ¿te gustó la programción?**
***

La programación es como Taco Bell: siempre se usan los mismos ingredientes, excepto que se mezclan de diferentes maneras. Sabes cómo escribir código, pero ... ¿sabes cómo resolver problemas reales?


