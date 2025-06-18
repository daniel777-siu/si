# si
### 1. clasificador de triangulos
```javascript
let a = Number(prompt("Escribe el primer lado del triangulo"));
let b = Number(prompt("Escribe el segundo lado del triangulo"));
let c = Number(prompt("Escribe el tercer lado del triangulo"));

function clasificar(a,b,c) {
    if (a + b <= c || a + c <= b || b + c <= a) {
        console.log ("no es un triangulo");
    } 
   else if (a === c && b === c){
        console.log ("equilatero");
    }
    else if (a === b || a === c || b === c) {
        console.log ("isoceles");
    }
    else 
   console.log("escaleno"); 

    }
 
    clasificar(a,b,c)
```
---
Metodos de arrays
---
### 1. Quitar el primer elemento de un array de frutas
```javascript
let frutas = ["manzana", "banana", "pera"];
frutas.shift()
console.log(frutas)
```
### 2. agregar numero al final de array de numeros



