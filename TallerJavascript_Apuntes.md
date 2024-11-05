Lenguaje MarkDown:
Objetivo: Proporcionar una herramienta para documentar codigo, o aspectos tecnicos para compartirlos o tenerlos de
referencia en mi Git u otra plataforma


El objetivo de su creador fua hacer que la gente pudiera escribir usando un formato de texto plano facil de leer, facil de escribir y
con la posibilidad de convertir su documento en HTML valido.

La gran simpleza de su sintaxis hizo que tuviera una rapida adaptacion popularidad en la
comunidad de desarrolladores.

Acctualmente aparte de permitir generar contenido HTML de forma dinamica, tambien se emplea  (casi de forma estandar) 


Conocer sintaxis de MarkDown:

1.- Parrafos [Párrafo 1...]

Párrafo 1...
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.




_cursiva_

**negrita**

~~tachado~~

**_cursiva y negrita_**

_~~cursiva y tachado~~_

**~~negrita y tachado~~**

**_~~cursiva, negrita y tachado~~_**

Encabezados:

# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6

Divisiones

Un bloque de contenido
---
Este es otro bloque de contenido



Listas: Podemos utilizar las lista ordenadas y listas desordenadas

1. html5
1. css
1. javaScript
1. Ajax
1. Json

- html5
- css
- javaScript
- Ajax
- Json

Citas
Podemos dar formato de cita a un texto, anteponiendo a la linea de un texto un caracter de mayor que (>)

>La IA en el futuro remplazara muchas funciones de TI. - EdsonBautista

>ChatGPT debe potenciar mi aprendizaje, no suprimir mi estado autodidacta
>
>EdsonBautista

Enlaces

[YouTube](https://www.youtube.com)
[Enlace a Google](https://google.com)

Imagenes

![Texto Alternativo](URLdelaimagen)

Tablas

| Columna 1 | Columna 2 | Columna 3 |
| --------- | --------- | --------- |
| A         | B         | C         |
| D         | E         | F         |
| G         | H         | I         |


Codigo
Podemos dar formato de codigo 


Esto es un `codigo` en linea

En _JavaScript_ una variable se escrie asi:
`let saludo = "Hola mundo";


Pero si queremos 




Estructuras de ciclo
---

//alert("Estamos en el archivo Estructuras de ciclo.js");

for(let i=0; i <= 10; i++){
    console.log("No. Iteracion: "+i);
}

let contador=1;

while (contador < 10){
    console.log(" [while] No. Iteracion: "+ contador);
    contador++;
}

let numero=1;


//Estructura de control do/while

do{
    console.log(" [do/while] No. Iteracion: "+ numero);
    numero++;
}while (numero < 10);

let estudiante = { nombre:"Juan Perez", edad:18, calificacion: 70};

//for in
//Este bucle itera sobre las propiedades enumerables de un objeto

for (let propiedad in estudiante){
    console.log(propiedad + ": " + estudiante[propiedad]);
}


//for...of
//Este objeto itera sobre los valores de un objeto iterable (como un)

let mis_numeros=[10,20,30,40,50];

for (let numero of mis_numeros){
    console.log(numero);
}




IMC
---
let peso;
let estatura;
    peso=prompt("Ingresa tu peso: ");
    estatura=prompt("Ingresa tu estatura: ")

let num1=parseFloat(peso);
let num2=parseFloat(estatura);
let resultado=parseFloat((num1/(num2^2)));
    console.log("Tu IMC es: "+resultado);

if (resultado<18.5){
    console.log("Usted esta bajo de peso");
}

else if (resultado>=18.6 && resultado<=24.9){
    console.log("Su peso es normal");
}

else if (resultado>=25 && resultado<=29.9){
    console.log("Usted tiene sobrepeso");
}

else if (resultado>=30 && resultado<=34.9){
    console.log("Usted tiene obesidad I");
}

else if (resultado>=35 && resultado<=39.9){
    console.log("Usted tiene obesidad II");
}

else if (resultado>40){
    console.log("Usted tiene obesidad III");
};


Taller
---

//Asi se utilizan los comenarios de JavaScript de una sola linea

console.log("Bienvenido al mundo de la programacion FrontEnd con JavaScript");

console.log("Esta es otra linea" + "Y se concatena con el +");

/*
Este es un comentario de mas de una linea
*/

/*
    En JavaScript no existe un compilador dado que es un lenguaje interpretado.
    Es por ello que tenemos que utilizar la instruccion console.log para monitorear
    el avance y el flujo de la logica de implementos. Sin embargo Chrome ofrece
    unas herramientas para revisar los errores.
*/

//Ahora vamos a trabajar con declaracion de  variables:
let estudiante="Juan Perez";
let edad=19;
let isEstudiante=true;
let calificacion=92.2;

console.log("Estudiante: "+ estudiante);
console.log("Edad: "+edad);
console.log("¿Estudia?: "+isEstudiante);
console.log(typeof calificacion);
console.log('El promedio global de estudiante es ${calificacion} ');


let valor1=7;
let valor2=4;
let valor3=9;
let valor4=2;

console.log("Suma: "+(valor3+valor4));
console.log("Resta: "+(valor1-valor2));
console.log("Multiplicacion: "+(valor3*valor1));
console.log("Division: "+(valor2/valor4));

let val1;
let val2;
    val1=prompt("Ingresa un primer numero: ");
    val2=prompt("Ingresa un segundo numero: ")

let num1=parseInt(val1);
let num2=parseInt(val2);
    
    console.log("La suma es: "+ (num1+num2));

/*
    Java Script es un leguaje ligeramente tipeado, esto significa que
    no es estricto en la declaracion de tipos de datos. Es decir, no
    fuerza a que inicialmente digas el tipo de dato de la variable. Y 
    esta puede cambiar en el transcurso de logica por otro tipo de 
    datos según sea la necesidad.
*/





















let x=10;
x += 5;
x -= 2;
x *= 3;
x /= 3;
x %= 5;


let a=5;  let b='5';
console.log(a == b);
console.log(a===b);
console.log(a != b);














let Cargo=200;

    if (Cargo >= 100 && Cargo <= 150){
        alert("Impuesto bajo");
    }else if(Cargo >= 151 && Cargo <= 200){
        alert("Impuesto medio");
    } else{
        alert("Revisar el tabulador");
    }



Calculadora
---
const pantalla = document.querySelector(".pantalla");
const botones = document.querySelectorAll(".btn");

botones.forEach(boton => {
    boton.addEventListener("click", () => {
        const botonApretado = boton.textContent;

        if (boton.id === "c") {
            pantalla.textContent = "0";
            return;
        }

        if (boton.id === "borrar") {
            if (pantalla.textContent.length === 1 || pantalla.textContent === "Error!") {
                pantalla.textContent = "0";
            } else {
                pantalla.textContent = pantalla.textContent.slice(0, -1);
            }
            return;
        }

        if (boton.id === "igual") {
            try {
                pantalla.textContent = eval(pantalla.textContent);
            } catch {
                pantalla.textContent = "Error!";
            }
            return;
        }

        if (pantalla.textContent === "0" || pantalla.textContent === "Error!") {
            pantalla.textContent = botonApretado;
        } else {
            pantalla.textContent += botonApretado;
        }
    })
})
