---
title: Estructuras Iterativas
theme: sky
slideNumber: true
---
<style>
.reveal section img {
    background: none !important;
    box-shadow: none !important;
    border: none !important;
}
.reveal i.fab {
    font-family:"Font Awesome 5 Brands";
    font-style: normal;
} 

table{
    font-size: 20px;
}

div.grid2{
    display: grid;
    /*grid-template-columns: auto auto auto auto;*/
    grid-template-columns: 25% 25% 25% 25%;
    grid-row-gap: 1ch;
    grid-column-gap: 1ch;
}

div.grid2 div{
    border: white 1px solid;
    font-size: 0.8em;
    background: #9fd1ff;
}

div.grid2 div h3{
    padding: 0;
    margin: 0;
}

div.grid2 div p{
    padding: 0;
    margin: 0;
}

div.grid2 div:hover{
    background: linear-gradient(-45deg, #383bff, #52bfff,#23a6d5,#23d5ab);
    animation: change 4s ease-in-out infinite;
    box-shadow: 5px 7px 12px #5e7280;
}

@keyframes change {
    0%{
        background-position: 0 50%;
    }
    50%{
        background-position: 100% 50%;
    }
    100%{
        background-position: 0 50%;
    }
}
</style>

## TP3: Estructuras Iterativas o Repetitivas
Created by [edme88]("https://t.me/edme88")

---
## Ejercicios TP3
#### Ejercicios Introductorios
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 1</h3>
        Suma N números
        <p>
            <a href="#/5"><img src="images/problema.png"></a>
        </p>
    </div>
</div>
    
#### Estructura de control repetitiva **While**
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 2</h3>
        Suma 1 a 10
        <p>
            <a href="#/13"><img src="images/problema.png"></a>
            <a href="#/17"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 3</h3>
        Gastos Viaje
        <p>
            <a href="#/18"><img src="images/problema.png"></a>
            <a href="#/21"><img src="images/Cmasmas.png"></a>
            <a href="#/22"><img src="images/youtube_logo.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 4</h3>
        Promedio Notas
        <p>
            <a href="#/23"><img src="images/problema.png"></a>
            <a href="#/26"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 5</h3>
        Tabla multiplicar
        <p>
            <a href="#/28"><img src="images/problema.png"></a>
            <a href="#/31"><img src="images/Cmasmas.png"></a>
            <a href="#/32"><img src="images/youtube_logo.png"></a>
        </p>
    </div>
</div>

#### Estructura de control repetitiva **Do While**
<div class="grid2">
    <div>
        <h3>EJ 6</h3>
        Suma 1 al 10
        <p>
            <a href="#/33"><img src="images/problema.png"></a>
            <a href="#/36"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 7</h3>
        100 pares
        <p>
            <a href="#/33"><img src="images/problema.png"></a>
            <a href="#/36"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
            <h3>EJ 8</h3>
            Unidades Producto
            <p>
                <a href="#/33"><img src="images/problema.png"></a>
                <a href="#/36"><img src="images/Cmasmas.png"></a>
            </p>
        </div>
    <div>
        <h3>EJ 9</h3>
        Aumento de Sueldo
        <p>
            <a href="#/38"><img src="images/problema.png"></a>
            <a href="#/41"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
</div>

---
## Ejercicio TP3
#### Estructura de control repetitiva **for**
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 10</h3>
        Suma 1 a 10
        <p>
            <a href="#/48"><img src="images/problema.png"></a>
            <a href="#/51"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 11</h3>
        Cantidad 0
        <p>
            <a href="#/53"><img src="images/problema.png"></a>
            <a href="#/56"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 12</h3>
        Mayor y Menor
        <p>
            <a href="#/58"><img src="images/problema.png"></a>
            <a href="#/61"><img src="images/Cmasmas.png"></a>
            <a href="#/62"><img src="images/youtube_logo.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 13</h3>
        + - 0
        <p>
            <a href="#/63"><img src="images/problema.png"></a>
            <a href="#/66"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 14</h3>
        Factorial
        <p>
            <a href="#/68"><img src="images/problema.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 15</h3>
        Notas: A, D, P
        <p>
            <a href="#/73"><img src="images/problema.png"></a>
            <a href="#/76"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 16</h3>
        Par, Impar, Nulo
        <p>
            <a href="#/78"><img src="images/problema.png"></a>
            <a href="#/81"><img src="images/Cmasmas.png"></a>
            <a href="#/82"><img src="images/youtube_logo.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 17</h3>
        Sueldos
        <p>
            <a href="#/83"><img src="images/problema.png"></a>
            <a href="#/86"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 18</h3>
        Primos
        <p>
            <a href="#/88"><img src="images/problema.png"></a>
        </p>
    </div>
</div>

---
## Ejercicio TP3
#### Estructura de control repetitiva **EXTRA**
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 19</h3>
        Serie 2,5,7,10..
        <p>
            <a href="#/93"><img src="images/problema.png"></a>
            <a href="#/96"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 20</h3>
        Cant. Ventas
        <p>
            <a href="#/98"><img src="images/problema.png"></a>
            <a href="#/101"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 21</h3>
        Serie 1-1/2+1/3-...
        <p>
            <a href="#/103"><img src="images/problema.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 22</h3>
        Fibonacci
        <p>
            <a href="#/108"><img src="images/problema.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 23</h3>
        Conjetura Ulam
        <p>
            <a href="#/114"><img src="images/problema.png"></a>
            <a href="#/117"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 24</h3>
        Cant. Votos
        <p>
            <a href="#/119"><img src="images/problema.png"></a>
            <a href="#/121"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 25</h3>
        Estación metereologica
        <p>
            <a href="#/123"><img src="images/problema.png"></a>
            <a href="#/126"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 26</h3>
        Aproximación Pi
        <p>
            <a href="#/128"><img src="images/problema.png"></a>
            <a href="#/131"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 27</h3>
        Llamada telefonica
        <p>
            <a href="#/133"><img src="images/problema.png"></a>
            <a href="#/136"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 28</h3>
        Pares 2 al 200
        <p>
            <a href="#/138"><img src="images/problema.png"></a>
            <a href="#/141"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 29</h3>
        Producto
        <p>
            <a href="#/143"><img src="images/problema.png"></a>
            <a href="#/146"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 30</h3>
        División
        <p>
            <a href="#/143"><img src="images/problema.png"></a>
            <a href="#/146"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
</div>

---
## Ejercicio TP3
#### Estructura de control repetitiva **EXTRA**
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 31</h3>
        Potencia
        <p>
            <a href="#/148"><img src="images/problema.png"></a>
            <a href="#/151"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 32</h3>
        Cuadrado Cubo
        <p>
            <a href="#/153"><img src="images/problema.png"></a>
            <a href="#/156"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 33</h3>
        Suma-Producto
        <p>
            <a href="#/163"><img src="images/problema.png"></a>
            <a href="#/166"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 34</h3>
        Piezas
        <p>
            <a href="#/148"><img src="images/problema.png"></a>
            <a href="#/151"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 35</h3>
        10,20,30,40
        <p>
            <a href="#/153"><img src="images/problema.png"></a>
            <a href="#/156"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 36</h3>
        A y B
        <p>
            <a href="#/163"><img src="images/problema.png"></a>
            <a href="#/166"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 37</h3>
        A, B y C
        <p>
            <a href="#/148"><img src="images/problema.png"></a>
            <a href="#/151"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 38</h3>
        N pares X,Y
        <p>
            <a href="#/153"><img src="images/problema.png"></a>
            <a href="#/156"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 39</h3>
        MCD
        <p>
            <a href="#/163"><img src="images/problema.png"></a>
            <a href="#/166"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 40</h3>
        Funciones
        <p>
            <a href="#/148"><img src="images/problema.png"></a>
            <a href="#/151"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 41</h3>
        Max y Min
        <p>
            <a href="#/153"><img src="images/problema.png"></a>
            <a href="#/156"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 42</h3>
        Dibujo
        <p>
            <a href="#/163"><img src="images/problema.png"></a>
            <a href="#/166"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
</div>

---
### EJ1: Suma N números 
<!-- .slide: style="font-size: 0.50em" -->
Dada la siguiente consigna: “Calcular la suma de un conjunto de N números leídos desde teclado”, determinar si los 
siguientes diagramas de flujo, resuelven correctamente lo pedido. En caso contrario, indicar los errores:
![Ej1](images/TP3/FlowChart_3.png)
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ1: Suma N números 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ1: Suma N números 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ1: Suma N números 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Suma 1 a 10
<!-- .slide: style="font-size: 0.50em" -->
Realice la sumatoria de los números enteros comprendidos entre el 1 al 10.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Suma 1 a 10
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Suma 1 a 10
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Suma 1 a 10
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Gastos Viaje 
Queremos conocer los gastos de nuestro último viaje. Permita al usuario ingresar todos los gastos deseados. 
El programa mostrará la sumatoria de los mismos cuando el usuario ingrese un valor negativo.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Gastos Viaje 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Gastos Viaje 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Gastos Viaje 
````javascript

````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Gastos Viaje 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ4: Promedio Notas
Permita al usuario ingresar cualquier cantidad de notas. El proceso finalizará cuando se ingrese un ‘0’. Posteriormente, 
calculará el promedio de las notas.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ4: Promedio Notas
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ4: Promedio Notas
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ4: Promedio Notas
````javascript

````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ4: Promedio Notas
<iframe width="560" height="315" src="https://www.youtube.com/embed/4eEfMvFH2fs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ5: Tabla multiplicar 
Muestre por pantalla la tabla de multiplicación del número que ingrese el usuario. Para definir hasta que número desea 
que muestre la tabla de multiplicación el usuario también deberá ingresar este valor. La tabla de multiplicación a 
mostrar debe empezar en la multiplicación por 1.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ5: Tabla multiplicar 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ5: Tabla multiplicar 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ5: Tabla multiplicar 
````javascript

````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ5: Tabla multiplicar 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ6: Suma 1 al 10 
Realice la sumatoria de los números enteros comprendidos entre el 1 al 10.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ6: Suma 1 al 10 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ6: Suma 1 al 10 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ6: Suma 1 al 10 
````javascript
````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ6: Suma 1 al 10 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ7: 100 pares  
Existen 1000 unidades de un determinado producto. Mientras existan más de 200 se pueden seguir realizando entregas. 
Si la cantidad baja de 200 debe notificarse un alerta.


<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ7: 100 pares 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ7: 100 pares 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ7: 100 pares 
````javascript

````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ7: 100 pares 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ8: Aumento de Sueldo
En una empresa se decidió aumentar en un 12% el sueldo de aquellos empleados que cobren menos de $18.000. 
El programa debe permitir ingresar el sueldo del empleado y si corresponde mostrar el mensaje 
“El empleado tiene un aumento. Su nuevo sueldo es:”.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ8: Aumento de Sueldo
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ8: Aumento de Sueldo
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ8: Aumento de Sueldo
````javascript
````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ8: Aumento de Sueldo
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ9: Aumento de Sueldo 
Calcule el aumento de sueldo de para un grupo de empleados teniendo en cuenta el siguiente criterio: Si el sueldo es 
inferior a $18000, aumento de 15%, Si el sueldo es mayor o igual a $18000, aumento del 12%.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ9: Aumento de Sueldo 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ9: Aumento de Sueldo 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ9: Aumento de Sueldo 
````javascript
````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ9: Aumento de Sueldo 

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ10: Suma 1 a 10
Realice la sumatoria de los números enteros comprendidos entre el 1 al 10.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ10: Suma 1 a 10
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ10: Suma 1 a 10 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ10: Suma 1 a 10 
````javascript

````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ10: Suma 1 a 10 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ11: Cantidad 0
Permite ingresar 12 números por teclado. Cuenta la cantidad de veces que se ingresó el cero.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ11: Cantidad 0
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ11: Cantidad 0
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ11: Cantidad 0
````javascript
````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ11: Cantidad 0
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ12: Mayor y Menor 
Determinar el mayor y el menor entre diez números enteros ingresados por teclado.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ12: Mayor y Menor 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ12: Mayor y Menor 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ12: Mayor y Menor 
````javascript

````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ12: Mayor y Menor 
<iframe width="560" height="315" src="https://www.youtube.com/embed/yfITZKFtpfY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ13: + - 0 
Leer diez números y determinar la cantidad de ceros, positivos y negativos.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ13: + - 0 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ13: + - 0 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ13: + - 0 
````javascript
````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ13: + - 0 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ14: Factorial 
El programa debe calcular el factorial de un número N que ingrese el usuario.

Ej.      6! = 6 x 5 x 4 x 3 x 2 x 1 = 720


<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ14: Factorial 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ14: Factorial 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ14: Factorial 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ14: Factorial 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ15: Notas: A, D, P
Permita ingresar 10 notas por teclado, y que determine si está aprobado (4 o más) o no. Contabilice la cantidad de 
aprobados, la cantidad de desaprobados, y el promedio.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ15: Notas: A, D, P
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ15: Notas: A, D, P
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ15: Notas: A, D, P
````javascript
````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ15: Notas: A, D, P
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ16: Par, Impar, Nulo 
Ingresar 8 números por teclado. Contabilizar la cantidad de pares, impares y nulos.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ16: Par, Impar, Nulo 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ16: Par, Impar, Nulo 
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ16: Par, Impar, Nulo 
````javascript
````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ16: Par, Impar, Nulo 

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ17: Sueldos
Ingresar la cantidad de trabajadores de la empresa. Posteriormente, ingresar sus sueldos. Calcular el monto que la empresa invierte en sueldos.
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ17: Sueldos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ17: Sueldos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ17: Sueldos
````javascript
````
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ17: Sueldos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ18: Primos
Permite al usuario ingresar un número. Verifica si el número es o no primo. Imprime por pantalla el texto “Es primo” ó “No es Primo.
1. Desarrolle Solución 1: Verificar que solo tiene 2 divisores (1 y sí mismo)
2. Modifique el código de forma tal, que si el número NO es primo, muestre en qué números es divisible.
3. Desarrolle Solución 2: Emplee una bandera que cambie de estado si el número NO es primo.

<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ18: Primos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ18: Primos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ18: Primos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ18: Primos
<a href="#/2"><img src="images/back_indice.png"></a>

---
#### EJ19: Serie 2,5,7,10..
El programa debe imprimir los términos de la siguiente serie: 2,5,7,10,12,15,17 (hasta llegar a 100).

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ19: Serie 2,5,7,10..
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ19: Serie 2,5,7,10..
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ19: Serie 2,5,7,10..
````javascript
````

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ19: Serie 2,5,7,10..
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ20: Cant. Ventas 
Un vendedor hizo una serie de ventas y desea conocer aquellas de $200 o menos, las mayores a $200 pero inferiores a $400, 
y las de $400 o más. El programa debe permitir ingresar el número de ventas, el monto de cada una. Finalmente, mostrar 
la cantidad de ventas de cada categoría.

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ20: Cant. Ventas 
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ20: Cant. Ventas 
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ20: Cant. Ventas 
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ20: Cant. Ventas 
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ21: Serie 1-1/2+1/3-...
El usuario debe poder ingresar un número N, y el programa muestra como salida el resultado de la siguiente serie: 
1-1/2+1/3-1/4+…±1/N

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ21: Serie 1-1/2+1/3-...
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ21: Serie 1-1/2+1/3-...
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ21: Serie 1-1/2+1/3-...
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ21: Serie 1-1/2+1/3-...
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ22: Fibonacci
La sucesión de Fibonacci es una sucesión infinita de números naturales: 0,1,1,2,3,5,8,13… La sucesión comienza con los 
números 0 y 1, y a partir de los mismos, cada término es la suma de los 2 anteriores. El programa debe permitir al 
usuario ingresar la cantidad de números de la sucesión que desea que se muestren (mínimo: 3). Se debe imprimir por 
pantalla la cantidad de números de la sucesión de Fibonacci correspondiente. 

<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ22: Fibonacci
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ22: Fibonacci
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ22: Fibonacci
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ22: Fibonacci
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ22: Fibonacci
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ23: Conjetura Ulam 
Según la “Conjetura de Ulam o Collatz” se puede obtener una serie de números siguiendo las reglas: comenzar por 
cualquier entero positivo. Si es par dividirlo por 2, si es impar multiplicarlo por 3 y agregarle 1. El programa debe 
dejar al usuario introducir un número para comenzar, y debe imprimir por pantalla todos los números de la serie hasta llegar a 1.
Ej: Si num=6, los números son 6, 3, 10, 5, 16, 8, 4, 2, 1


<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ23: Conjetura Ulam 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ23: Conjetura Ulam 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ23: Conjetura Ulam 
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ23: Conjetura Ulam 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ24: Cant. Votos
En una elección hubo 4 candidatos (con identificadores 1,2,3 y 4). El programa debe contar el número de votos 
correspondientes a cada uno (y voto en blanco ‘cero’) y el porcentaje que obtuvo respecto al total de votantes. 
El usuario ingresará los votos, indicando con -1 cuando haya terminado.

<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ24: Cant. Votos 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ24: Cant. Votos 
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ24: Cant. Votos 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ25: Estación metereologica 
En una estación meteorológica se llevan los registros mensuales de las lluvias de 3 regiones: norte, centro y sur. El 
programa debe permitir ingresar estos datos, calcular el promedio de cada región, y la región con mayor lluvia.

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ25: Estación metereologica
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ25: Estación metereologica 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ25: Estación metereologica 
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ25: Estación metereologica 
<a href="#/3"><img src="images/back_indice.png"></a>  

---
#### EJ26: Aproximación Pi 
Calcular el valor de Pi utilizando la siguiente serie:
Pi=4/1-4/3+4/5-4/7+4/9-…
La diferencia entre la serie y Pi debe ser menor a 0,0005. El programa debe imprimir el número de términos requeridos para obtener esa precisión.

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ26: Aproximación Pi 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ26: Aproximación Pi 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ26: Aproximación Pi 
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ26: Aproximación Pi 
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ27: Llamada telefonica
Para calcular el precio de unas llamadas telefónicas se posee la siguiente información:”
* Internacional
 * 3 primeros minutos $7.59
 * Cada minuto adicional $3.03
* Nacional
 * 3 primeros minutos $1.20
 * Cada minuto adicional $0.48
* Local
 * 50 primeras llamadas, gratis
 * Luego, $0.60 por llamada

El usuario debe ingresar el tipo de llamada y la cantidad de minutos hablados. Si en tipo, se ingresa un valor distinto 
a ‘i’,’n’ ó ‘l’, el programa muestra el costo de todas las llamadas, y un resumen por tipo.

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ27: Llamada telefonica
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ27: Llamada telefonica
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ27: Llamada telefonica
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ27: Llamada telefonica
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ28: Pares 2 al 200 
Sumar los números pares comprendidos entre 2 y 200.

<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ28: Pares 2 al 200 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ28: Pares 2 al 200 
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ28: Pares 2 al 200 
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ28: Pares 2 al 200
<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ29: Producto
Realizar el producto entre dos enteros como sumas sucesivas.

<a href="#/3"><img src="images/back_indice.png"></a> 

---
#### EJ29: Producto
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ29: Producto
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ29: Producto
````javascript
````
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ29: Producto
<a href="#/3"><img src="images/back_indice.png"></a>

---
#### EJ30: División
Realizar la división entre dos enteros como diferencias sucesivas, indicando el cociente y el resto de la división.

<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ30: División
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ30: División
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ30: División
````javascript
````
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ30: División
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ31: Verificar cuadrante
Diseñar un algoritmo que permita determinar si un punto de coordenadas (X,Y), está en un cuadrante ingresado en forma 
de número entero. El programa debe mostrar por pantalla el valor 0 si es falso ó 1 si es verdadero. 
Tanto las coordenadas del punto, como el cuadrante, deben ser leídos desde teclado.

<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ31: Verificar cuadrante
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ31: Verificar cuadrante
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ31: Verificar cuadrante
````javascript
#include <iostream>
using namespace std;

int main(){
	float  coorX, coorY;
	int Cuadrante;
	cout<<"Ingrese el valor de la coordenada X ";
	cin>>coorX;
	cout<<"Ingrese el valor de la coordenada Y";
	cin>>coorY;
	cout<<"Ingrese el cuadrante ";
	cin>>Cuadrante;
	if (coorX>0 && coorY>0 && Cuadrante==1){
		  cout<<"1"<<endl;
    }
    else{
 		if (coorX>0 && coorY<0 && Cuadrante==4){
			cout<<"1"<<endl;
		}
		else{
			if (coorX<0 && coorY>0 && Cuadrante==2){
              cout<<"1"<<endl;
            }
            else{
				if (coorX<0 && coorY<0 && Cuadrante==3){
					cout<<"1"<<endl;
                }
                else{
					cout<<"0"<<endl;
                }
		    }
        }
    }
}
````
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ31: Verificar cuadrante
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ32: 24hs a 12am/pm
Escribir un programa que lea la hora de un día de notación de 24 horas y la respuesta en notación de 12 horas. 
(Ej. 13:45, la salida es 1:45 PM). Le pedirá al usuario que ingrese 5 caracteres de la forma 05:00.
 
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ32: 24hs a 12am/pm 
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ32: 24hs a 12am/pm 
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ32: 24hs a 12am/pm
````javascript

````
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ32: 24hs a 12am/pm 
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ33: Año Bisiesto
Escribir un programa que determine si un año es bisiesto. Recuerde que un año es bisiesto si es múltiplo de 4 (Ej. 1984). 
Sin embargo, los años múltiplos de 100 sólo son bisiestos cuando a la vez son múltiples de 400 (Ej. 1800 no es bisiesto, pero 2000 si).  

<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ33: Año Bisiesto 
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ33: Año Bisiesto 
<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ33: Año Bisiesto
````javascript
#include <iostream>
using namespace std;

int main(){
	int anio;
	cout<< "Ingresar el valor del anio";
	cin>>anio;
	if ((anio%4 == 0 && anio%100!=0) || anio%400 == 0){
		cout<<"El año es bisiesto"<<endl;
	}
    else{
        cout<<"El año no es bisiesto"<<endl;
    }
}
````

<a href="#/4"><img src="images/back_indice.png"></a>

---
#### EJ33: Año Bisiesto 
<a href="#/4"><img src="images/back_indice.png"></a>