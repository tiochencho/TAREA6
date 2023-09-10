// TAREA6
//Arreglo
let A =[];
//Elementos iniciales
const t = [1, 11, 54 ,2 , 30, 65];
//Visualizar los elementos del arreglo
console.log(t);
//Hacemos la suma de los arreglos 
let suma = t.reduce(

         (sum, item) => sum + item,
         0
);
console.log(suma);
//Consultamos el promedio de los elementos 
let promedio = suma/t.length;
console.log(promedio);
