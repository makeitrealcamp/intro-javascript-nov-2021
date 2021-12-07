# Ejercicios día 7

Recuerda que puedes hacer preguntas en el [Foro de Make It Real](https://foro.makeitreal.camp/c/intro-javascript-innpulsa-nov-2021/11).

## Ejercicio 35

Crea una variable llamada `pedro` de tipo objeto literal con las siguientes llaves y valores:

- `nombre` - "Pedro Perez"
- `edad` - 30
- `activo` - true
- `hobbies` - un arreglo con los siguientes elementos: "programar", "squash", "piano".

Ahora haz lo siguiente:

1. Imprime en consola el valor de la llave `edad`.
2. Agrega una propiedad con llave `estatura` y valor `1.8`.
3. Elimina la propiedad con llave `activo`.
4. Recorre todas las propiedades e imprímelas en consola (una línea por propiedad y separando la llave y el valor con dos puntos `:`).

El resultado en consola debería ser parecido al siguiente (puede que las propiedades no salgan en el mismo orden):

```
30
nombre: "Pedro Perez"
edad: 30
hobbies: ["programar", "squash", "piano"]
estatura: 1.8
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-35-js-noviembre/5418).

## Ejercicio 36

Escribe una función llamada saludar que reciba un objeto que representa una persona y retorne la frase como se muestra a continuación:

```javascript
// escribe tu función acá

// código de prueba
const pedro = { nombre: "Pedro", edad: 23 };
console.log(saludar(pedro)); // "Hola Pedro, tienes 23 años"

const maria = { nombre: "Maria", edad: 35 };
console.log(saludar(maria)); // "Hola Maria, tienes 35 años"

const juan = { nombre: "Juan" };
console.log(saludar(juan)); // "Hola Juan"
```

El objeto siempre tendrá la llave `nombre`. La llave `edad` es opcional y cuando no está presente deberás omitir la parte ", tienes x años".

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-36-js-noviembre/5419).

## Ejercicio 37

Escribe una función `buscarProducto` que reciba un arreglo de objetos y un número. La función deberá buscar el número dentro de cada objeto (en la llave id) y retornar el objeto encontrado.

Si no encuentra un objeto con ese id deberá retornar `null`.

```javascript
// escribe tu función acá

// código de prueba
let productos = [
  { id: 1, nombre: "A" },
  { id: 2, nombre: "B" },
];
console.log(buscarProducto(productos, 1)); // { id: 1, nombre: "A" }

productos = [
  { id: 1, nombre: "A" },
  { id: 2, nombre: "B" },
];
console.log(buscarProducto(productos, 566)); // null
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-37-js-noviembre/5420).

## Ejercicio 38

Escribe una función llamada `descifrar` que reciba un string y un objeto. Utiliza las propiedades del objeto para reemplazar los caracteres de la cadena y retorna el resultado:

```javascript
// escribe tu función acá

// código de prueba
console.log(descifrar("h0l4", { 0: "o", 4: "a" })); // "hola"
console.log(descifrar("pyrmizo", { y: "e", z: s })); // "permiso"
console.log(descifrar("igual", { h: "n" })); // "igual"
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-38-js-noviembre/5421).

## Ejercicio 39

Escribe una función llamada `frecuencias` que reciba un string y retorne un objeto con el número de veces que aparece cada carácter (exceptuando el espacio en blanco):

```javascript
// escribe tu función acá

// código de prueba
console.log(frecuencias("hola mundo"));
// { h: 1, o: 2, l: 1, a: 1, m: 1, u: 1, n: 1, d: 1 }

console.log(frecuencias("anita lava la tina"));
// { a: 6, n: 2, i: 2, t: 2, l: 2, v: 1 }
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-39-js-noviembre/5422).

## Ejercicio 40

Crea una variable llamada `persona` de tipo objeto literal con las siguientes propiedades:

- `peso` - 65
- `estatura` - 1.8
- `bmi` - una función que retorne el **índice de masa corporal de la persona**. Recuerda que la fórmula es `peso/estatura^2` (peso sobre estatura al cuadrado).

```javascript
// escribe tu código acá

// código de prueba
console.log(persona.bmi()); // 20.061728395061728
```

Comparte tu respuesta [en este enlace](https://foro.makeitreal.camp/t/respuestas-ejercicio-40-js-noviembre/5423).
