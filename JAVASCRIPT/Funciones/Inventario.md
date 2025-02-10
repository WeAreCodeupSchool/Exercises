# Inventario

## Descripción del ejercicio
En este ejercicio, vamos a crear una función que simule un **sistema de gestión de inventario** para una tienda. La función deberá manejar operaciones como agregar productos, eliminar productos y calcular el valor total del inventario.

### Objetivos:
- Aprender a trabajar con estructuras de datos complejas (arrays y objetos).
- Practicar cómo implementar funciones modulares que interactúen entre sí.
- Implementar validaciones robustas para evitar errores con entradas incorrectas.

---

## Instrucciones

1. **Define la función principal**: Crea una función llamada `gestionarInventario` que acepte tres parámetros:
   - `inventario`: Un array que contiene los productos actuales en el inventario.
   - `accion`: Una cadena que indica la acción a realizar (`"agregar"`, `"eliminar"` o `"calcular"`).
   - `producto`: Un objeto que contiene información sobre el producto (nombre, cantidad y precio unitario). Este parámetro solo es necesario para las acciones `"agregar"` y `"eliminar"`.
2. **Validaciones**:
   - Verifica que el inventario sea un array.
   - Verifica que la acción sea válida (`"agregar"`, `"eliminar"` o `"calcular"`).
   - Para las acciones `"agregar"` y `"eliminar"`, verifica que el producto tenga las propiedades requeridas (`nombre`, `cantidad` y `precio`).
3. **Operaciones**:
   - Si la acción es `"agregar"`, añade el producto al inventario (o actualiza su cantidad si ya existe).
   - Si la acción es `"eliminar"`, reduce la cantidad del producto en el inventario o lo elimina si la cantidad llega a cero.
   - Si la acción es `"calcular"`, calcula el valor total del inventario multiplicando la cantidad de cada producto por su precio unitario y sumando todos los resultados.
4. **Devuelve el resultado**: Dependiendo de la acción, devuelve el inventario actualizado o el valor total del inventario.
5. **Llama a la función**: Prueba tu función con diferentes casos, incluyendo acciones inválidas.
