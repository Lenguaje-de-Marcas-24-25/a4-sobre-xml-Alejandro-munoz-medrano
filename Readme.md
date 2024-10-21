## 1. ¿Características del lenguaje XML?

- **Estructura jerárquica:** Organiza datos en un árbol.
- **Extensible:** Permite definir etiquetas personalizadas.
- **Texto legible:** Comprensible para humanos y máquinas.
- **Soporte para Unicode:** Admite múltiples idiomas.
- **Separación de contenido y presentación:** La estructura de datos se mantiene independiente de su presentación.

# Guía sobre XML

## 2. ¿Qué es un elemento vacío en XML?
Un **elemento vacío** es un elemento que no contiene ningún contenido ni elementos hijos. Se representa con una etiqueta de apertura y cierre en una sola línea.

## 3. ¿Qué sentido tiene crear documentos XML bien formados?
Crear documentos XML bien formados es esencial porque:

- **Interoperabilidad:** Permite que diferentes sistemas y aplicaciones procesen el documento sin errores.
- **Validación:** Facilita la validación del documento contra un esquema o DTD.
- **Mantenimiento:** Mejora la legibilidad y el mantenimiento del código.

## 4. ¿Qué es un espacio de nombres en XML?
Un **espacio de nombres** en XML es un mecanismo que permite evitar conflictos entre elementos que pueden tener el mismo nombre pero diferentes significados. Se define mediante un prefijo y una URI.

### Ventajas de uso:
- **Evita colisiones de nombres.**
- **Organiza elementos de manera lógica.**

## 5. ¿Qué son las entidades en XML?
Las **entidades** en XML son formas de representar caracteres especiales o secuencias de texto. Se pueden utilizar entidades predefinidas o definir entidades personalizadas.

## 6. ¿Cómo se manejan los comentarios en XML?
Los **comentarios** en XML se utilizan para incluir notas o información adicional que no se procesará como parte del contenido. Comienzan con `<!--` y terminan con `-->`.

## 7. Reglas sintácticas de XML
Un documento XML debe cumplir con ciertas reglas sintácticas:

- Un único nodo raíz.
- Los nombres de los elementos son sensibles a mayúsculas.
- Cada etiqueta de apertura debe tener una etiqueta de cierre correspondiente.
- No se permiten caracteres prohibidos sin entidades.

## 8. ¿Comentarios en XML. Muestra uno de los ejercicios anteriores con el enunciado dentro de un comentario. Dentro del comentario deben aparecer dos guiones?
<?xml version="1.0" encoding="UTF-8"?>
<libros xmlns:fantasia="http://ejemplo.com/fantasia">
    <fantasia:libro>
        <fantasia:titulo>El hobbit</fantasia:titulo>
        <fantasia:autor>J.R.R. Tolkien</fantasia:autor>
    </fantasia:libro>
    <libro>
        <titulo>XML para principiantes</titulo>
        <autor>Juan Pérez</autor>
    </libro>
</libros>
