# massiv-zapolnyaem
как заполняется массив С++

#include <iostream>
using namespace std;

int main()
{
    int const z = 16;
    int massiv[z];
        for (int  i = 0; i < z; i++)
        {
            
            massiv[i] = i + 1;
                
               
        }
        cout << "\n";
        for (int i = 0; i < z; i++)
        {

            cout << massiv[i]<<"\t";


        }
        

}
