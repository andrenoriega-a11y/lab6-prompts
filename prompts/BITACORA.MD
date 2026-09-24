# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: (escribe aqui cual usaste)

## Ejercicio 2: Tokens y ventana de contexto
| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 34 | 7 |
| The students program in Java. | 29 | 6 |
| desafortunadamente | 18 | 4 |
en el paso 4 si se acordo porque estabamos en el mismo chat y tenia el contexto ahi. en el cambio al chat nuevo ya no sabia nada porque estaba vacio y me pidio mas info o invento otra cosa.
## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|------------|----------------|----------------------------------------------------|
| 0          | 100.0%         | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5        | 65.3%          | PrestaLibro, BiblioTec, BiblioTec, LibroYa, BiblioTec |
| 1          | 44.5%          | BiblioTec, BiblioTec, PrestaLibro, BiblioTec, BiblioTec |
| 1.8        | 32.2%          | BiblioTec, LectoGo, BiblioTec, PrestaLibro, BiblioTec |
Al subir la temperatura aumenta la variedad de nombres elegidos. El simulador no inventa palabras nuevas porque solo selecciona entre las opciones predefinidas.
## Ejercicio 4: Prompt vago vs estructurado
| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | Sí | Sí |
| Menciona a los usuarios principales | Sí | Sí |
| Tiene exactamente 3 funcionalidades | No | Sí |
| Está en 3 párrafos | No | Sí |
| Lo usaría en un informe real | No | Sí |
## Ejercicio 5: Anatomia de un prompt
 | Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actúa como desarrollador Java. |
| Instrucción | Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos código, nombre, precio y stock. |
| Contexto | (Incluido en la instrucción del sistema de tienda). |
| Ejemplo | Usa este estilo para los métodos: getPrecio(), setPrecio(double precio). |
| Formato | Explica primero la estructura de la clase y luego presenta el código Java. |
## Ejercicio 6: Del prompt basico al profesional
| Qué revisar | Cumple (Sí / No) |
| :--- | :--- |
| ¿Está escrito en Java y usa Swing? | Sí |
| ¿Pide correo y contraseña? | Sí |
| ¿Explica el funcionamiento antes o después del código? | Sí |
| ¿El código está organizado en clases? | Sí |
| ¿Valida los datos que ingresa el usuario? | No |

README.md
- [Bitacora de prompts](prompts/BITACORA.md)
