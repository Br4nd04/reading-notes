# Programación Funcional En JavaScript

## 1. ¿Qué diferencias fundamentales encuentras entre resolver un problema con programación imperativa y hacerlo con programación funcional?

+ Imperativa: Se centra en cómo hacer las cosas, con instrucciones que modifican el estado del programa.

+ Funcional: Se enfoca en qué se quiere lograr, usando funciones puras y evitando cambios de estado.

## 2. ¿Cuándo es mejor usar funciones puras y cuándo no?

+ Ventajas: Son predecibles, fáciles de probar y permiten paralelización.

+ Desventajas: No son ideales para tareas que requieren cambios de estado, como interacciones con bases de datos o interfaces.

## 3. ¿Qué aportan map(), filter() y find() al código?

Mejoran la legibilidad y reducen la complejidad al manejar colecciones de datos de manera declarativa, sin bucles explícitos.

## 4. ¿Por qué la programación funcional facilita las pruebas y depuración?

Las funciones puras no dependen del estado externo ni causan efectos secundarios, lo que permite pruebas más simples y código más predecible.

## 5. ¿Cómo integrar programación funcional en proyectos imperativos?

+ Refactorizar poco a poco: Convertir funciones en puras cuando sea posible.

+ Usar funciones de orden superior: Reemplazar bucles con map(), filter(), etc.

+ Evitar mutabilidad: Usar estructuras de datos inmutables.