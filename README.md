#include <iostream>
#include <cmath>
using namespace std;
 void intro(){
    cout << "Que desea hacer:" << endl << "(1)Hacer ..." << endl << "(2)Hacer ..." <<  endl << "(3)Hacer ..." << endl << "(4)Hacer ..." << endl << endl;
}
 void imagen(){
    cout << endl;
    for (int j = 1; j < 10; ++j){
        for (int i = 0; i < 20-2*j; ++i)
            cout << '0';
        for (int i = 0; i < 2*j; ++i)
            cout << '1';
        cout << '0';
        for (int i = 0; i < 20-2*j; ++i)
            cout << '1';
        for (int i = 0; i < 2*j; ++i)
            cout << '0';
        cout << endl;
    }
    cout << endl;
}
 int main()
{
    imagen();
    intro();
    int n;
    cout << "->";
    cin >> n;
    if (n == 1)
    return 0;
}
