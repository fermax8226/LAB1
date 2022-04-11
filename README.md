# LAB1
Practicas de laboratorio
//Nombre: Maximilano David Ferreyra
//TP Nº: 1
//Ej Nº: 1
/*Hacer un programa para ingresar por teclado la cantidad
 de horas trabajadas por un operario y el valor que se le paga
  por hora trabajada y listar por pantalla el sueldo que le corresponda.*/
#include <iostream>
using namespace std;
#include <cstdlib>
int main(){
// ingreso de variables donde H=horas trabajadas
// y VH=valor horas S=sueldo a abonar
    int H,VH,S;
    cout << "ingrese Horas trabajadas: " << endl;
    cin >> H;
    cout << "ingrese valor hora trabajada: " << endl;
    cin >> VH;
    S=H*VH;
    cout << " El sueldo a abonar es: " << S;
	return 0;
}
