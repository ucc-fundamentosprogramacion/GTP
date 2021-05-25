---
title: Programación en C++
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
    /*grid-template-columns: auto auto auto;*/
    grid-template-columns: 33% 33% 33%;
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

## TP4: Programación en C++
Created by [edme88]("https://t.me/edme88")

---
## Ejercicios TP4
#### Ejercicios Introductorios
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 1</h3>
        Hola Mundo!
        <p>
            <a href="#/2"><img src="images/problema.png"></a>
            <a href="#/4"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 2</h3>
        Pez
        <p>
            <a href="#/6"><img src="images/problema.png"></a>
            <a href="#/8"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 3</h3>
        Espada
        <p>
            <a href="#/10"><img src="images/problema.png"></a>
            <a href="#/13"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
</div>

#### Estructuras
<div class="grid2">
    <a href="TP1_ejercicios.html">
    <div>
        <h3>Estructura Secuencial <br> TP 1</h3>
    </div>
    </a>
    <a href="TP2_ejercicios.html">
    <div>
        <h3>Estructuras de Decisión o Selección <br> TP 2</h3>
    </div>
    </a>
    <a href="TP3_ejercicios.html">
    <div>
            <h3>Estructuras de Iteración o Repetición <br> TP 3</h3>
        </div>
    </a>
</div>

---
### EJ1: Hola Mundo! 
Realizar un programa que genere (imprima) la siguiente salida por pantalla: Hola Mundo!!!

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ1: Hola Mundo! 
<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ1: Hola Mundo! 
````javascript
#include <iostream>
using namespace std;

int main(){
    cout<<"Hola Mundo!"<<endl;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ1: Hola Mundo! 
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Pez
Realizar un programa que genere (imprima) la siguiente salida por pantalla (pez): ><(((('>

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Pez
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Pez
````javascript
#include <iostream>
using namespace std;

int main(){
    cout<<"><(((('>"<<endl;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ2: Pez
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Espada
Realizar un programa que genere (imprima) la siguiente salida por pantalla (espada): (===||:::::::::::::::>

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Espada
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Espada
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Espada
````javascript
#include <iostream>
using namespace std;

int main(){
    cout<<"(===||:::::::::::::::>"<<endl;
}
````
<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ3: Espada
<a href="#/1"><img src="images/back_indice.png"></a>
