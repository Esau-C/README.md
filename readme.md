# **Tarea algoritmos** 
Esta tarea consiste en realizar un codigo que consiste en pedir un numero representado en centimetros para convertirlo a yardas, pies, metros o varas dependiendo la opcion que elija el usuario.

>Este ejercicio debe ser creado de 3 formas diferentes, las cuales son: 
* C++
* Python
* Pseint

# *Acontinuacion el codigo*
---
## **Ejercicio en C++**
```c++
#include <iostream>
using namespace std;
int main(){
	float n1, metros, yardas, varas, pulgadas, pies, respuesta;
	int des;
	metros = 0.01;
	yardas = 0.0109361;
	varas = 0.01196308192916;
	pulgadas = 0.393701;
	pies = 0.0328084;
	cout<<"Ingrese la opcion que desea convertir de centimetros \n 1. Metros\n 2.Yardas\n 3. Varas\n 4. Pulgadas\n 5. pies\n Eliga una opcion : ";
	cin>>des;
	cout<<"Ingrese los centimetros que quiere convertir : ";
	cin>> n1;
	switch(des){
		case 1: 
		respuesta = n1 * metros;
		cout<<"El resultado es : "<<respuesta<<" Metros";
		break;
		case 2:
			respuesta = n1 *yardas;
			cout<<"El resultado es : "<<respuesta<<" Yardas";
			break;
			case 3:
				respuesta = n1 * varas;
				cout<<"El resultado es : "<<respuesta<<" Varas";
				break;
				case 4:
					respuesta = n1 * pulgadas;
					cout<<"El resultado es : "<<respuesta<<" Pulgadas";
					break;
					case 5: 
					respuesta = n1 * pies;
					cout<<"El resultado es : "<<respuesta<<" Pies";
					break;
	}	
		return 0;
}
```
---
## **Ejercicio en Python**
```python
import decimal
metros = 0.01
yardas = 0.0109361
varas = 0.01196308192916
pulgadas = 0.393701
pies = 0.0328084

des=int(input("Seleccione la combercion de centimetros que desea realizar\n 1.Metros\n 2.Yardas\n 3. Varas\n 4. Pulgadas\n 5. Pies\n Elija una opcion : "))
n1=float(input("Ingrese los centimetros que desea convertir : "))
if(des == 1):
    resultado=float( n1 * metros)
    input(f"El resultado es : {resultado} Metros ")
else:
    if(des ==2):
        resultado=float( n1 * yardas)
        input(f"El resultado es : {resultado} Yardas ")
    else:
        if(des ==3):
            resultado=float(  n1 * varas)
            input(f"El resultado es : {resultado} Varas ")
        else:
            if(des == 4):
                resultado=float(  n1 * pulgadas)
                input(f"El resultado es : {resultado} Pulgadas ")
            else:
                if(des == 5):
                    resultado=float(  n1 * pies)
                    input(f"El resultado es : {resultado} Pies ")
                
```
---
## **Ejercicio en Pseint**
```
Algoritmo conversiondecentimetros
	definir n1, metros, yardas, varas, pulgadas, pies, respuesta como real
	definir des Como Entero
	metros = 0.01
	yardas = 0.0109361
	varas = 0.01196308192916
	pulgadas = 0.393701
	pies = 0.0328084
	Escribir "Ingrese una opcion para convertir los centimetros : "
	Escribir "1. Metros"
	Escribir "2. Yardas"
	Escribir "3. Varas"
	Escribir "4. Pulgadas"
	Escribir "5. Pies"
	Escribir "Ingrese una opcion : "
	leer des
	Escribir "Ingrese los centimetros que desea convertir : "
	leer n1
	Segun des hacer
		caso 1:
			respuesta = n1 * metros
			Escribir "El resultado es : ", respuesta, " Metros"
		caso 2:
			respuesta = n1 * yardas
			Escribir "El resultado es : ", respuesta, " Yardas"
		caso 3:
			respuesta = n1 * varas
			Escribir "El resultado es : ", respuesta, " Varas"
		caso 4:
			respuesta = n1 * pulgadas
			Escribir "El resultado es : ", respuesta, " Pulgadas"
		caso 5:
			respuesta = n1 * pies
			Escribir "La respuesta es : ", respuesta, " Pies"
	FinSegun
FinAlgoritmo
```
---
# *Tareas finalizadas:*
* [X] C++
* [X] Python
* [X] Pseint

:sunglasses:
:sunglasses:
