#include <iostream>

using namespace std;

int main()
{
    float C,F, K, R;
    cout<< " Program konversi suhu"<< endl;
    cout<< " Masukkan nilai Celciusnya =";
    cin >> C;
    F= C*1.8 + 32;
    K= C*273.15;
    R= C*0.8;
    cout<< "nilai farenheit =" <<F<< endl;
    cout<< "nilai Kelvin ="<< K<<endl;
    cout<< "nilai Rankine ="<< R<<endl;
    return 0;
}
