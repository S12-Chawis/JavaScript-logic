# JavaScript-logic

## Triangles clasifier
### Escribe un programa que reciba tres números positivos que representan las longitudes de los lados de un triángulo. El programa debe determinar si los lados forman un triángulo válido y, si es válido, clasificarlo como:

Equilátero: todos los lados son iguales.
Isósceles: dos lados son iguales.
Escaleno: todos los lados son diferentes.
Si los lados no forman un triángulo válido, muestra un mensaje de error.
```js
let side1 = Number(prompt('Enter the first side of the triangle'))
let side2 = Number(prompt('Enter the second side of the triangle'))
let side3 = Number(prompt('Enter the third side of the triangle'))

if ((side1 + side2 > side3) || (side1 + side3 > side2) || (side2 + side3 > side1)) {
     if (side1 == side2 && side2 == side3) {
        console.log('The formed triangle is equilateral')
    } else if (side1 != side2 && side1 != side3 && side2 != side3) {
        console.log('The formed triangle is scalene')
    } else {
        console.log('The formed triangle is isosceles')
     }
} else {
    console.log('Error: the values do not form a valid triangle')
}
```

## Arrays methods

### Ejercicio 1: Quita el primer elemento de un array de frutas.
```js
let fruits = ['watermelon', 'apple', 'pineapple', 'pear', 'banana']
console.log(fruits)
fruits.shift()
console.log(fruits)
```

### Ejercicio 2: Agrega un número al final de un array de números.
```js
let numbers = [19820, 23871, 2380, 802,  105]
console.log(numbers)
numbers.push(30293)
console.log(numbers)
```

### Ejercicio 3: Agrega un elemento al principio de un array de palabras.
```js
let words = ['array', 'object', 'main', 'root',  'spinning']
console.log(words)
words.unshift('stemming')
console.log(words) 
```

### Ejercicio 4: Elimina el último elemento de un array de colores.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
colors.pop()
console.log(colors) 
```

### Ejercicio 5: Extrae una porción de un array sin modificar el original.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
console.log(colors.slice(1, 4))
```

### Ejercicio 6: Reemplaza un elemento en una posición específica del array.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
colors.splice(2, 2, ...['cyan', 'blueviolet'])
console.log(colors)
```

### Ejercicio 7: Une los elementos de un array de palabras en un solo string separado por espacios.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
console.log(colors.join(" "))
```

### Ejercicio 8: Ordena alfabéticamente un array de nombres.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
colors.sort()
console.log(colors)
```

### Ejercicio 9: Invierte el orden de los elementos de un array.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
colors.reverse()
console.log(colors)
```

### Ejercicio 10: Verifica si un valor específico existe dentro del array.
```js
let colors = ['blue', 'yellow', 'green', 'red',  'violet']
console.log(colors)
console.log(colors.includes('red'))
```
## For excercises

### 1: Usa for...of para recorrer una palabra letra por letra e imprimir cada letra.
```js

```

### 2: Usa un bucle for para imprimir los números del 1 al 5.
```js

```

### 3: Usa for...in para recorrer una palabra e imprimir el índice y el carácter en esa posición.
```js

```
