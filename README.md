#include <iostream>
using namespace std;

int main() {
    int edad;

    // Solicita al usuario que ingrese su edad
    cout << "Ingrese su edad: ";
    cin >> edad;

    // Verifica si es mayor o menor de edad
    if (edad >= 18) {
        cout << "Usted es mayor de edad." << endl;
    }
    else {
        cout << "Usted es menor de edad." << endl;
    }

    return 0;
}
