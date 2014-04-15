programacion
============

Hellyeah
// mientras.cpp : Defines the entry point for the console application.
//
#include "stdafx.h"
#include <iostream>
#include "conio.h"

using namespace std;

void main(){
	int cont,N,suma,i;
	cout<<"Ingrese N";
	cin>>N;
	suma=0;
		i=1;
		cont=1;
		while (i<=N)
        {
			suma=suma+cont;
			cont=cont+2;
			i=i+1;
		}
		cout<<"la suma es:";
		cout<<suma;

		getch();
}

