/*escribe un programa que lea de la entrada estandar
el precio de un producto
y muestre en la salida estandar 
el precio del producto al aplicarle el iva 
*/

#include <iostream>

using namespace std;
int main(){

float producto, iva = 0.16; //son las variables
	
	cout<<"introduce el precio del producto:"; cin>>producto;  //aqui se debe introducior el precio del producto
	
	iva = 0.16 * producto;  //se realiza la operacion
	
	cout<<"\nel iva es:"<<iva<<endl;  //este es la salida del total dl precio del producto mas el iva
	
	
	
	return 0; //esta es la salida de este programa y lo imprime
	
}

