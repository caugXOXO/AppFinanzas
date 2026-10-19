# Introduccion a JavaScript

JavaScript es un lenguaje de programacion versatil que se utiliza para crear paginas web interactivas y aplicaciones. Puede ejecutarse en el navegador y, con entornos como Node.js, tambien en el servidor.

## Ejemplo basico

Este ejemplo define una funcion, recibe un nombre y devuelve un saludo:

```javascript
function saludar(nombre) {
  return `Hola, ${nombre}!`;
}

const mensaje = saludar("Mundo");
console.log(mensaje);
```

## Conceptos utiles

- **Variables:** usa `const` para valores que no se reasignan y `let` cuando el valor puede cambiar.
- **Funciones:** agrupan instrucciones que puedes reutilizar.
- **Arreglos y objetos:** permiten organizar colecciones de datos.
- **Modulos:** ayudan a separar el codigo en archivos reutilizables.

## Ejecutar el ejemplo

Guarda el codigo en un archivo, por ejemplo `ejemplo.js`. Puedes ejecutarlo con Node.js desde una terminal:

```bash
node ejemplo.js
```

La salida sera:

```text
Hola, Mundo!
```
