# Respuestas read 09

## ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí? ##

Tipos de datos en JavaScript
En JavaScript, los tipos de datos se dividen en dos categorías principales: primitivos y objetos.

Primitivos:

Number: Representa números, tanto enteros como decimales.

String: Representa cadenas de texto.

Boolean: Representa valores verdaderos (true) o falsos (false).

Undefined: Representa una variable que ha sido declarada pero no inicializada.

Null: Representa la ausencia intencional de cualquier valor.

Symbol: Representa un valor único e inmutable.

BigInt: Representa números enteros de gran tamaño.

Objetos:

Object: Estructura de datos que permite almacenar colecciones de datos y entidades más complejas.

Array: Lista ordenada de valores.

Function: Bloque de código reutilizable.

Date: Representa fechas y horas.

RegExp: Representa expresiones regulares.

## ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa? ##

Estructuras condicionales if y else
Las estructuras condicionales if y else se utilizan para ejecutar diferentes bloques de código según ciertas condiciones.
let edad = 18;

if (edad >= 18) {
  console.log("Eres mayor de edad.");
} else {
  console.log("Eres menor de edad.");
}

En este ejemplo, si la variable edad es mayor o igual a 18, se ejecuta el primer bloque de código. De lo contrario, se ejecuta el bloque de código dentro de else.

## ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos? ##

Tipos de operadores en JavaScript
Aritméticos: Realizan operaciones matemáticas.

+ (suma)

- (resta)

* (multiplicación)

/ (división)

% (módulo)

** (exponenciación)

let a = 10;
let b = 5;
console.log(a + b); // 15
console.log(a - b); // 5
console.log(a * b); // 50
console.log(a / b); // 2
console.log(a % b); // 0
console.log(a ** b); // 100000

Asignación: Asignan valores a las variables.

= (asignación)

+= (suma y asignación)

-= (resta y asignación)

*= (multiplicación y asignación)

/= (división y asignación)

%= (módulo y asignación)

Comparación: Comparan dos valores.

== (igualdad)

=== (igualdad estricta)

!= (desigualdad)

!== (desigualdad estricta)

> (mayor que)

< (menor que)

>= (mayor o igual que)

<= (menor o igual que)

Lógicos: Realizan operaciones lógicas.

&& (AND)

|| (OR)

! (NOT)

## ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad? ##

Declaración de variables en JavaScript
var: Tiene un alcance de función y puede ser redeclarada y reasignada.

let: Tiene un alcance de bloque y puede ser reasignada, pero no redeclarada en el mismo ámbito.

const: Tiene un alcance de bloque y no puede ser reasignada ni redeclarada.

var nombre = "Juan";
let edad = 25;
const pais = "Perú";

nombre = "Carlos"; // Válido
edad = 30; // Válido
pais = "Chile"; // Error: No se puede reasignar una constante


[Inicio](https://github.com/Br4nd04/reading-notes.git)