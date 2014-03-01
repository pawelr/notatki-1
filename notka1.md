##Początki programowania  
Poznawanie trudnej sztuki programowania rozpoczyna się najczęściej od prostego programu ***Hello World***.  
Jego twórcą był ***Denis Ritche***.  
![Tekst alt](http://www.chip.pl/blobimgs/2011/10/full/ea882209c5c896ffda86ca443d4188f4.jpeg)  
Z tego wynika, że ja zaczęłam nietypowo:  
 1. najpierw przepisałam program w języku C++ liczący liczbę groszków w strąkach,  
 2. napisałam prosty program w języku C++.  
**Oto on:**  
#include <iostream>  
#include <conio.h>  
using namespace std;  

int main ( )  

{  
    cout << "Witam\n";  
    
	int liczba_A, liczba_B, suma, iloczyn;   
    
    cout << "Po wpisaniu kazdej liczby nacisnij [Enter].\n";  
    cout << "Podaj liczbe A:\n";  
    cin >> liczba_A;  
    cout << "Podaj liczbe B:\n";   
    cin >> liczba_B;  

           suma = liczba_A + liczba_B;  

    cout << "suma wynosi:\n ";  
    cout << suma << endl;  
    
    
            iloczyn = liczba_A * liczba_B;  
            
    cout << "iloczyn wynosi:\n ";  
    cout << iloczyn;  
    cout << "\n";  
    
    cout << "Zegnam\n";  

    
    getch();  
}

