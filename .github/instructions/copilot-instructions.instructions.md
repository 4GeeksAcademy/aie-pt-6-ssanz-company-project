---
title: "Add explanatory comments to regex patterns"
description: "Ensure AI always includes detailed comments explaining regex components."
scope: "user"
alwaysApply: true
---

# Regla: Comentarios explicativos en patrones Regex

Cada vez que generes expresiones regulares (regex), debes incluir comentarios en línea dentro del bloque de código que desglosen y expliquen la función de cada componente del patrón.

## Formato de salida requerido

Debes incluir los comentarios utilizando la sintaxis de comentarios en línea del lenguaje correspondiente (por ejemplo, `//` en JavaScript, TypeScript, Java, C#, etc.).

### Ejemplo completo:

Para el patrón de validación de correo electrónico `/^\w+@[a-z]+\.[a-z]{2,3}$/`, la salida debe estructurarse de la siguiente manera:

```javascript
const emailRegex = /^\w+@[a-z]+\.[a-z]{2,3}$/;
// ^ : inicio de la cadena
// \w+ : uno o más caracteres de palabra (letras, números o guion bajo)
// @ : símbolo literal de arroba
// [a-z]+ : una o más letras minúsculas (dominio)
// \. : punto literal
// [a-z]{2,3} : dos a tres letras minúsculas (extensión TLD)
// $ : fin de la cadena
```
