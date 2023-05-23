#include<bits/stdc++.h>
using namespace std;

float CalcularFahrenheit(int celcius);

int main(){
	
	int celcius;
	
	cout<<"Ingresar temperatura en celcius: ";
	cin>>celcius;
	
	cout<<"Temperatura Fahrenheit: "<<CalcularFahrenheit(celcius)<<" F"<<endl;
	
	return 0;
}

float CalcularFahrenheit(int celcius){
	
	float F = 0;
	
	F = celcius * 1.8 + 32;
	
	return F;
	
}
