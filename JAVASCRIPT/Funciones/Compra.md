# Compra

## Descripción del ejercicio
En este ejercicio, vamos a crear una función que calcule el **precio total de una compra** en una tienda online. La función deberá aplicar un **descuento** si el monto de la compra supera cierto umbral y calcular el **IVA** correspondiente.

### Objetivos:
- Aprender a manejar múltiples cálculos dentro de una misma función.
- Practicar cómo devolver múltiples valores desde una función (usando objetos).
- Implementar validaciones para evitar errores con entradas incorrectas.

---

## Instrucciones

1. **Define la función**: Crea una función llamada `calcularPrecioFinal` que acepte dos parámetros: `monto` (el precio base de la compra) y `descuento` (un porcentaje de descuento opcional).
2. **Validaciones**: Verifica que el monto sea un número positivo. Si no lo es, la función debe devolver un mensaje de error.
3. **Cálculo**:
   - Si el monto supera los $100, aplica un descuento del 10% automáticamente (a menos que se especifique otro descuento).
   - Calcula el IVA (21%) sobre el monto después de aplicar el descuento.
   - Calcula el precio final sumando el IVA al monto descontado.
4. **Devuelve el resultado**: Usa un objeto para devolver el precio final, el descuento aplicado y el IVA calculado.
5. **Llama a la función**: Prueba tu función con diferentes valores de monto y descuento, incluyendo casos donde los valores sean inválidos.
