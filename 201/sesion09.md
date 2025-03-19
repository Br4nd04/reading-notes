### Mitos y Verdades sobre el DOM como API de Objetos

1. **Mito** ❌  
   - `querySelector()` devuelve **un único elemento**, no una colección de nodos. Si quieres múltiples elementos, debes usar `querySelectorAll()`.  

2. **Verdad** ✅  
   - El DOM permite manipular estilos mediante `.style` (para modificar propiedades CSS individuales) y `.classList` (para agregar, quitar o alternar clases CSS).  

3. **Mito** ❌  
   - El resultado de una expresión regular puede variar según el contexto, como configuraciones regionales o el uso de modificadores como `i` (insensible a mayúsculas y minúsculas) o `u` (para Unicode).  

4. **Verdad** ✅  
   - `getElementById()` es más eficiente para buscar un solo elemento porque accede directamente al ID, mientras que `querySelectorAll()` recorre todo el DOM y filtra los elementos.  

5. **Mito** ❌  
   - Los métodos del DOM pueden devolver diferentes tipos de objetos (`NodeList`, `HTMLCollection`, `Element`, etc.), dependiendo del método utilizado.  

6. **Verdad** ✅  
   - `querySelectorAll()` devuelve una `NodeList` estática, lo que significa que no se actualiza automáticamente si el DOM cambia después de la selección.  

7. **Verdad** ✅  
   - Es posible transformar texto con expresiones regulares en JavaScript sin librerías externas, aunque para tareas complejas es recomendable usar herramientas especializadas como `marked.js`.  

8. **Mito** ❌  
   - Los cambios en el DOM hechos con JavaScript no son permanentes tras un refresco de página, ya que el DOM se vuelve a generar desde el HTML original. Para hacerlos persistentes, se debe usar almacenamiento como `localStorage` o bases de datos.
