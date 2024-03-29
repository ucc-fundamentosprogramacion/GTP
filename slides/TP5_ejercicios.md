---
title: TP5 - Programación Modular
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

## TP5: Programación Modular
Created by <i class="fab fa-telegram"></i>
[edme88]("https://t.me/edme88")


---
## Ejercicio TP5
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 1</h3>
        N° al Cuadrado
        <p>
            <a href="#/3"><img src="images/problema.png"></a>
            <a href="#/6"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 2</h3>
        Suma de N°
        <p>
            <a href="#/8"><img src="images/problema.png"></a>
            <a href="#/11"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 3</h3>
        N° mayor
        <p>
            <a href="#/13"><img src="images/problema.png"></a>
            <a href="#/16"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 4</h3>
        + - 0
        <p>
            <a href="#/18"><img src="images/problema.png"></a>
            <a href="#/21"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 5</h3>
        División exacta
        <p>
            <a href="#/23"><img src="images/problema.png"></a>
            <a href="#/26"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 6</h3>
        Vocal
        <p>
            <a href="#/28"><img src="images/problema.png"></a>
            <a href="#/31"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 7</h3>
        Trayectoria proyectil
        <p>
            <a href="#/33"><img src="images/problema.png"></a>
            <a href="#/36"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 8</h3>
        N° primo
        <p>
            <a href="#/38"><img src="images/problema.png"></a>
            <a href="#/41"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 9</h3>
        Conversión N°
        <p>
            <a href="#/43"><img src="images/problema.png"></a>
            <a href="#/46"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 10</h3>
        Polar ^ Cartesiano
        <p>
            <a href="#/48"><img src="images/problema.png"></a>
            <a href="#/51"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 11</h3>
        Factorial
        <p>
            <a href="#/53"><img src="images/problema.png"></a>
            <a href="#/56"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 12</h3>
        Serie a^0,a^1,a^2,...,a^n
        <p>
            <a href="#/58"><img src="images/problema.png"></a>
            <a href="#/61"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
</div>

---
## Ejercicio TP5
<!-- .slide: style="font-size: 0.70em" -->
<div class="grid2">
    <div>
        <h3>EJ 13</h3>
        Área: C, c, R, T
        <p>
            <a href="#/63"><img src="images/problema.png"></a>
            <a href="#/66"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 14</h3>
        Código Morse
        <p>
            <a href="#/68"><img src="images/problema.png"></a>
            <a href="#/71"><img src="images/Cmasmas.png"></a>
        </p>
    </div>
    <div>
        <h3>EJ 15</h3>
        Pared
        <p>
            <a href="#/73"><img src="images/problema.png"></a>
        </p>
    </div>
    
---
### EJ1: N° al Cuadrado
Escriba una función que reciba de parámetro un número entero, y devuelva el cuadrado del mismo.

<a href="#/1"><img src="images/back_indice.png"></a>

---
#### EJ1: N° al Cuadrado
<a href="#/1">![back](images/back_indice.png)</a>

---
## EJ1: N° al Cuadrado
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
## EJ1: N° al Cuadrado
````javascript
//Calcula el cuadrado de un numero
#include <iostream>
#include <math.h>
using namespace std;

//PROTOTIPO
int calculoCuadrado(int numero);

//PROGRAMA PRINCIPAL
int main(){
    int num;
    cout<<"Ingrese un numero: ";
    cin>>num;
    cout<<"El cuadrado del numero es: "<<calculoCuadrado(num)<<endl;
}

//FUNCIONES
int calculoCuadrado(int numero){
    int resultado;
    //resultado = pow(numero, 2);
    resultado = numero*numero;
    return resultado;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
## EJ1: N° al Cuadrado

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ2: Suma de N° 
Escriba una función que reciba como parámetros 2 números, y retorne la suma de ambos.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ2: Suma de N° 

---
### EJ2: Suma de N° 
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ2: Suma de N° 
````javascript
#include <iostream>
using namespace std;

//PROTOTIPOS
int sumatoria(int num1, int num2);


//FUNCION PRINCIPAL
int main(){
    int numero1, numero2;

    cout<<"Ingrese 2 numeros: ";
    cin>>numero1>>numero2;

    cout<<"El resultado de sumar ambos numeros es: "<<sumatoria(numero1, numero2)<<endl;
}

//FUNCIONES
int sumatoria(int num1, int num2){
    int resultado;
    resultado = num1 + num2;
    return resultado;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ2: Suma de N° 

---
### EJ3: N° mayor
La función debe recibir como parámetro 2 números, y debe devolver como resultado el mayor de ellos.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ3: N° mayor 

---
### EJ3: N° mayor 
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ3: N° mayor 
````javascript
#include <iostream>
using namespace std;

//PROTOTIPOS
int mayorNumero(int numero1, int numero2);

//FUNCION PRINCIPAL
int main(){
    int num1, num2;

    cout<<"Ingrese 2 numeros: "<<endl;
    cin>>num1>>num2;

    cout<<"El mayor numero es: "<<mayorNumero(num1, num2)<<endl;

}

//FUNCIONES
int mayorNumero(int numero1, int numero2){
    if(numero1>numero2){
        return numero1;
    }

    if(numero1<=numero2){
        return numero2;
    }
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ3: N° mayor 

---
### EJ4: + - 0 
Escriba una función que  tenga un argumento de tipo entero, y que devuelva la letra P, si es positivo, N si es negativo y C si es cero.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ4: + - 0 

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ4: + - 0 
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ4: + - 0 
````javascript
#include <iostream>
using namespace std;

//PROTOTIPOS
char verificaNumero(int numero);

//PROGRAMA PRINCIPAL
int main(){
    int num;
    char letra;
    cout<<"Ingrese un numero: ";
    cin>>num;

    letra = verificaNumero(num);
    cout<<endl<<letra;
}

//FUNCIONES
char verificaNumero(int numero){
    if(numero>0){
        cout<<"El numero "<<numero<<" es positivo";
        return 'P';
    }
    if(numero<0){
        cout<<"El numero "<<numero<<" es negativo";
        return 'N';
    }
    if(numero==0){
        cout<<"El numero "<<numero<<" es cero";
        return 'C';
    }
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ4: + - 0 

---
### EJ5: División exacta 
Escriba una función que reciba de argumento 2 números enteros, y devuelva true si la división es exacta, o false si no lo es.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ5: División exacta 

---
### EJ5: División exacta 
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ5: División exacta 
````javascript
#include <iostream>
using namespace std;

//prototipo
bool verificarDivision(int num1, int num2);

//main()
int main(){
    int num1, num2;
    bool verifacion;

    cout<<"Ingrese 2 numeros: ";
    cin>>num1>>num2;

    verifacion=verificarDivision(num1, num2);

    if(verifacion==true){
        cout<<"La division es exacta"<<endl;
    }else{
        cout<<"La division no es exacta"<<endl;
    }
}

//funciones
bool verificarDivision(int num1, int num2){
    bool b;

    if(num1%num2==0){
        b=true;
    }else{
        b=false;
    }
    return b;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ5: División exacta 

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ6: Vocal
Escriba una función lógica Vocal, que determine si un carácter es una vocal.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ6: Vocal

---
### EJ6: Vocal
````javascript 
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ6: Vocal
````javascript
#include <iostream>
using namespace std;

//prototipo
bool det_vocal(char vocal);

int main (){
char det;
        cout<<"ingrese un caracter"<<endl;
        cin>>det;

        if(det_vocal(det)){
            cout<<"Es una vocal"<<endl;
        }else{
            cout<<"No es una vocal"<<endl;
        }
}
//funcion
bool det_vocal(char vocal){
    bool resultado;

    if (vocal=='A'||vocal=='a'||vocal=='E'||vocal=='I'||vocal=='O'||vocal=='U'||vocal=='e'||vocal=='i'||vocal=='o'||vocal=='u'){
        resultado=true;
    }else {
        resultado=false;
    }
    return resultado;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ6: Vocal
<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ7: Trayectoria proyectil  
Escribir una función para calcular las coordenadas x e y de la trayectoria de un proyectil de acuerdo a los parámetros 
ángulo de inclinación alfa y la velocidad inicial v a intervalos de 0,1s.
![Proyectil](images/TP5/EJ7_proyectil.png)

Nota: Tener en cuenta que el proyectil volará hasta tocar el suelo, es decir, cuando y=0.


<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ7: Trayectoria proyectil  

---
### EJ7: Trayectoria proyectil  
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ7: Trayectoria proyectil 
````javascript
#include <iostream>
#include <cmath>
using namespace std;

//prototipo
float coorX(float ang, float vel_inicial, float t);
float coorY(float ang, float vel_inicial, float t);

//programa principal
int main(){
    float ang, vel_inicial, val_X, val_Y, t;
    val_Y=1;
    t=0.1;

    cout<<"Ingrese angulo: ";
    cin>>ang;
    cout<<"Ingrese velocidad inicial:";
    cin>>vel_inicial;

    ang=ang*M_PI/180;

    while(val_Y>0){
        val_Y=coorY(ang, vel_inicial, t);
        val_X=coorX(ang, vel_inicial, t);
        cout<<"La coordenada X es: "<<val_X<<endl;
        cout<<"La coordenada Y es: "<<val_Y<<endl;
        t+=0.1;
    }

    cout<<"El alcance máximo es: "<<val_X<<endl;
    cout<<"El tiempo total de vuelo es: "<<t-0.1<<endl;
}

//funciones
float coorX(float ang, float vel_inicial, float t){
    float x;
    x=cos(ang)*vel_inicial*t;

    return x;
}

float coorY(float ang, float vel_inicial, float t){
    float y;
    y=(sin(ang)*vel_inicial*t)-0.5*9.8*t*t;

    return y;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ7: Trayectoria proyectil  

---
### EJ8: N° primo
La función debe recibir como parámetro un número, y retornar si es primo o no. Recuerde que un número primo solo es 
divisible en 1 y en sí mismo.
* Modifique el programa anterior para obtener de salida los 10 primeros números primos.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ8: N° primo

---
### EJ8: N° primo
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ8: N° primo
````javascript
#include <iostream>
using namespace std;

//PROTOTIPOS
bool esPrimo(int num);

//FUNCION PRINCIPAL
int main(){
    int num;
    cout<<"Ingrese un numero: ";
    cin>>num;

    if(esPrimo(num)){
        cout<<num<<" es primo"<<endl;
    }
    else{
        cout<<num<<" no es primo"<<endl;
    }
}

//FUNCIONES
bool esPrimo(int num){
    bool esPri=true;

    for(int k=2; k<num; k++){
            if(num%k==0){
                esPri=false;
                break;
            }
    }
    return esPri;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ8: N° primo

---
### EJ9: Conversión N° 
La función debe recibir como parámetros un número y la unidad. Debe ser capaz de convertir Kilómetros a millas, metros a 
yardas, metros a pies, centímetros a pulgadas, litros a galones y celcius a farenheit. Debe imprimir por pantalla el 
resultado de esta conversión.

|Conervsion|          |
|----------|----------|
|1 kilometro|0.621371 millas|
|1 metro|1.09361 yardas|
|1 metro|3.28084 pies|
|1 centimetro|0.393701 pulgada|
|1 litro|0.264172 galones|

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ9: Conversión N° 

---
### EJ9: Conversión N° 
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ9: Conversión N° 
````javascript
#include <iostream>
using namespace std;

//prototipo
float conversion(float cantidad, char unidadIngresada, char unidadAconvertir);

//funcion principal
int main(){
    float cantidad;
    char unidadIngresada, unidadAconvertir;

    do{
        cout<<"Ingrese cantidad a convertir: ";
        cin>>cantidad;

        cout<<"Ingrese unidad: "<<endl;
        cout<<"k) kilometro"<<endl;
        cout<<"m) metro"<<endl;
        cout<<"c) centimetro"<<endl;
        cout<<"l) litro"<<endl;
        cin>>unidadIngresada;

        cout<<"Ingrese unidad a la cual desea convertir: "<<endl;
        cout<<"M) millas"<<endl;
        cout<<"y) yardas"<<endl;
        cout<<"P) pies"<<endl;
        cout<<"p) pulgadas"<<endl;
        cout<<"g) galones"<<endl;
        cin>>unidadAconvertir;

        cout<<"La conversion es: "<<conversion(cantidad, unidadIngresada, unidadAconvertir)<<endl;
    }while(true);

}

//funcion
float conversion(float cantidad, char unidadIngresada, char unidadAconvertir){
    float resultado;

    if(unidadIngresada=='k' && unidadAconvertir=='M'){
        resultado=cantidad*0.621371;
    }else if(unidadIngresada=='m' && (unidadAconvertir=='y' || unidadAconvertir=='P')){
        if(unidadAconvertir=='y'){
            resultado=cantidad*1.09361;
        }else{
            resultado=cantidad*3.28084;
        }
    }else if(unidadIngresada=='c' && unidadAconvertir=='p'){
        resultado=cantidad*0.393701;
    }else if(unidadIngresada=='L' && unidadAconvertir=='g'){
        resultado=cantidad*0.264172;
    }else{
        cout<<"Conversion no valida"<<endl;
        resultado=0;
    }

    return resultado;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ9: Conversión N° 

---
### EJ10: Polar ^ Cartesiano 
Escriba un programa que permita al usuario elegir entre 2 opciones. Deben existir 3 funciones: menu, 
convertir_polar_cartesiano, convertir_cartesiano_polar.
* Convertir de coordenadas de polares a cartesianas. Recuerde que x=r×cos(θ) y y=r×sen(θ)
* Convertir de coordenadas de cartesianas a polares. Recuerde que r=raiz(x^2+y^2) y =atan(y/x)

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ10: Polar ^ Cartesiano 

---
### EJ10: Polar ^ Cartesiano 
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ10: Polar ^ Cartesiano 
````javascript
#include <iostream>
#include <cmath>
using namespace std;

//prototipo
double coorX(double radio, double angulo);
double coorY(double radio, double angulo);
double calcularRadio(double x, double y);
double calcularAngulo(double x, double y);

//funcion principal
int main(){
    double radio, angulo, x, y;
    int opcion;

    cout<<"Seleccione una opcion"<<endl;
    cout<<"1) Cartesianas a Polares"<<endl;
    cout<<"2) Polares a Cartesianas"<<endl;
    cin>>opcion;

    switch(opcion){
        case 1:
            cout<<"Ingrese valor de x: ";
            cin>>x;
            cout<<"Ingrese valor de y: ";
            cin>>y;

            cout<<"El radio es: "<<calcularRadio(x, y)<<endl;
            cout<<"El angulo es"<<calcularAngulo(x, y)<<endl;
            break;
        case 2:
            cout<<"Ingrese el radio: ";
            cin>>radio;

            cout<<"Ingrese el angulo: ";
            cin>>angulo;

            angulo=angulo*M_PI/180;

            cout<<"La coordenada X es: "<<coorX(radio, angulo)<<endl;
            cout<<"La coordenada Y es: "<<coorY(radio, angulo)<<endl;

            break;
        default:
            cout<<"Opcion invalida"<<endl;
    }
}

//funciones
double coorX(double radio, double angulo){
    double x;
    x = radio*cos(angulo);

    return x;
}

double coorY(double radio, double angulo){
    double y;
    y = radio*sin(angulo);

    return y;
}

double calcularRadio(double x, double y){
    double radio;
    radio=sqrt(x*x+y*y);

    return radio;
}

double calcularAngulo(double x, double y){
    double angulo;
    angulo=atan(y/x);

    angulo=angulo*180/M_PI;
    return angulo;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ10: Polar ^ Cartesiano 

---
### EJ11: Factorial
La función debe recibir como parámetro un número ‘n’, y debe imprimir por pantalla el factorial de ese número. 
Recuerde que por ejemplo 5!=1x2x3x4x5=120.

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ11: Factorial

---
### EJ11: Factorial
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ11: Factorial
````javascript
#include <iostream>
using namespace std;

//prototipo
int calcularFactorial(int n);

//funcion principal
int main(){
    int n;

    do{
        cout<<"Ingrese un numero n: ";
        cin>>n;
    }while(n<=0);

    cout<<"El factorial de "<<n<<" es: "<<calcularFactorial(n);
}

//funcion
int calcularFactorial(int n){
    int acum;
    acum=1;

    for(int i=1;i<=n;i++){
        acum=acum*i;
    }

    return acum;
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ11: Factorial

---
### EJ12: Serie a^0,a^1,a^2,...,a^n  
La función debe recibir como entrada un número ‘a’ y un número ‘n’, y debe mostrar por pantalla: a^0,a^1,a^2,...,a^n  


<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ12: Serie a^0,a^1,a^2,...,a^n  

---
### EJ12: Serie a^0,a^1,a^2,...,a^n  
````javascript
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ12: Serie a^0,a^1,a^2,...,a^n  
````javascript
#include <iostream>
#include <math.h>
using namespace std;

//PROTOTIPOS
void funcion(double n, double a);

//PROGRAMA PRINCIPAL
int main(){
    double n, a;
    cout<<"Ingrese un valor de n: ";
    cin>>n;

    cout<<"Ingrese un valor de a: ";
    cin>>a;

    funcion(n,a);
}


//FUNCIONES
void funcion(double n, double a){
    for(int i=0; i<=n; i++){
        cout<<pow(a, i)<<" , ";
    }
}
````

<a href="#/1"><img src="images/back_indice.png"></a>

---
### EJ12: Serie a^0,a^1,a^2,...,a^n  

---
### EJ13: Área: C, c, R, T
Escribir un programa que permita al usuario elegir el cálculo del área de cualquiera de las figuras geométricas: 
círculo, cuadrado, rectángulo o triángulo mediante funciones.

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ13: Área: C, c, R, T

---
### EJ13: Área: C, c, R, T
````javascript

````

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ13: Área: C, c, R, T
````javascript
#include <iostream>
#include <cmath>
using namespace std;

//prototipo
float area_circulo(float rad);
float area_rectangulo(float base, float altura);
float area_cuadrado(float lado);
float area_triangulo(float base, float altura);

//funcion principal
int main(){
    char op;
    float base, altura, lado, radio, area;
    area = 0;

    do{
        cout<<"Ingrese c, r, x o t para: "<<endl;
        cout<<"c) circulo"<<endl;
        cout<<"r) rectangulo"<<endl;
        cout<<"x) cuadrado"<<endl;
        cout<<"t) triangulo"<<endl;
        cin>>op;

        if(op=='c' || op=='C'){
            cout<<"Ingrese valor del radio: ";
            cin>>radio;
            area = area_circulo(radio);
        }else if(op=='r' || op=='R'){
            cout<<"Ingrese valor de la base: ";
            cin>>base;
            cout<<"Ingrese valor de la altura: ";
            cin>>altura;
            area = area_rectangulo(base, altura);
        }else if(op=='x' || op=='X'){
            cout<<"Ingrese valor de lado: "<<endl;
            cin>>lado;
            area = area_cuadrado(lado);
        }else if(op=='t' || op=='T'){
            cout<<"Ingrese valor de la base: ";
            cin>>base;
            cout<<"Ingrese valor de la altura: ";
            cin>>altura;
            area = area_triangulo(base, altura);
        }else{
            cout<<"Se ingreso opcion invalida"<<endl;
        }

        /*switch(op){
            case 'c':
            case 'C':
                cout<<"Ingrese valor del radio: ";
                cin>>radio;
                area = area_circulo(radio);
                break;
            case 'R':
            case 'r':
                cout<<"Ingrese valor de la base: ";
                cin>>base;
                cout<<"Ingrese valor de la altura: ";
                cin>>altura;
                area = area_rectangulo(base, altura);
                break;
            case 't':
            case 'T':
                cout<<"Ingrese valor de la base: ";
                cin>>base;
                cout<<"Ingrese valor de la altura: ";
                cin>>altura;
                area = area_triangulo(base, altura);
                break;
            default:
                cout<<"Se ingreso opción invalida"<<endl;
        }*/

        cout<<"El area es: "<<area<<endl;
    }while(true);
}

//funciones
float area_circulo(float rad){
    float areaC;

    areaC=M_PI*(rad*rad);
    return areaC;
}

float area_rectangulo(float base, float altura){
    float areaR;

    areaR=base*altura;
    return areaR;
}

float area_cuadrado(float lado){
    float areaCuad;
    areaCuad = lado * lado;
    return areaCuad;
}

float area_triangulo(float base, float altura){
    float areaT;
    areaT = (base*altura)/2;
    return areaT;
}
````

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ13: Área: C, c, R, T

---
### EJ14: Código Morse
Escribir un programa que traduzca un texto a código morse:

![Codigo Morse](images/TP5/EJ14_morse.png) <a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ14: Código Morse 

---
### EJ14: Código Morse 
````javascript
````

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ14: Código Morse 
````javascript
#include <iostream>
using namespace std;

//prototipo
void escribir_morse(char letra);

//funcion principal
int main(){
    char letra;

    do{
        cout<<"Ingrese una letra: ";
        cin>>letra;
        escribir_morse(letra);
    }while(true);
}
//funcion
void escribir_morse(char letra){
    if(letra=='A' || letra=='a'){
        cout<<"._";
    }else if(letra=='H' || letra=='h'){
        cout<<"....";
    }else if(letra=='l' || letra=='L'){
        cout<<"._..";
    }else if(letra=='o' || letra=='O'){
        cout<<"_ _ _";
    }
}
````

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ14: Código Morse 

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ15: Pared
<!-- .slide: style="font-size: 0.70em" -->
Escribir un programa que permita al usuario ingresar el tipo de aparejo, espesor de la junta y largo y ancho de la 
pared a construir. Debe dar como salida la cantidad de ladrillos necesarios para construir una pared de esas dimensiones. 
Tener en cuenta:
![Ladrillos](images/TP5/ladrillos.png) ![Pared](images/TP5/ladrillos2.png)

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ15: Pared

---
### EJ15: Pared
````javascript
````

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ15: Pared
````javascript
````

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ15: Pared

<a href="#/2"><img src="images/back_indice.png"></a>

---
### EJ22: Cálculo de Raíces 
![back](images/back_indice.png)

![C++](images/Cmasmas.png)

![FlowChart](images/flow_chart.png)

![Problema](images/problema.png)

![Pseint](images/pseint_logo.png)

![Youtube](images/youtube_logo.png)