# skewlstuff
Skewlstuff
include <iostream>
using namespace std;

int main()
{
    double n = 0;
    cout << "Input maximum celsius: ";
    cin >> n;
    double breytir = n;
    double reiknir = Celsius_Fahrenheit(breytir);

        for(int i = 0; i < (n + 1); i++)
        {
                cout << i << endl;


        }





    return 0;
}


double Celsius_Fahrenheit (double breytir){

    double fahren =  (breytir * 9.0) / 5.0 + 32;
    return fahren;
}
