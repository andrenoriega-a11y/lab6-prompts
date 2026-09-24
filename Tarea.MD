- **Qué cambié / por qué:** Incorporé los 5 componentes obligatorios (rol, instrucción, contexto, ejemplos y formato) junto con una restricción clara.
- **Qué mejoró:** La respuesta de la IA fue sumamente precisa, estructurada, fácil de entender y lista para ejecutarse sin dependencias externas.

## Componentes del prompt final

| Componente      | Detalle en mi prompt                                         |
| :-------------- | :----------------------------------------------------------- |
| **Rol**         | Desarrollador Python senior especializado en inventarios     |
| **Instrucción** | Escribir un script de CRUD en consola para productos         |
| **Contexto**    | Uso por personal de caja en una tienda pequeña               |
| **Ejemplo**     | Estructura de diccionario con código, nombre, stock y precio |
| **Formato**     | Explicación breve seguida del bloque de código en Python     |

## Evaluacion del resultado

| Criterio                                                | Cumple (Sí / No) |
| :------------------------------------------------------ | :--------------- |
| ¿Usa los 5 componentes del prompt profesional?          | Sí               |
| ¿Incluye restricciones claras (sin librerías externas)? | Sí               |
| ¿El código está estructurado y documentado?             | Sí               |
| ¿Explica claramente los cambios entre versiones?        | Sí               |

## Errores que evite

1. **Ser demasiado general:** En la versión 1 cometí el error de pedir solo "un CRUD" sin detalles; en la versión final detallé los campos exactos (código, stock, precio).
2. **No indicar formato ni restricciones:** Al inicio la IA generaba código con librerías externas avanzadas; agregué la restricción explícita de usar solo estructuras nativas para evitarlo.
