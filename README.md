#include <iostream>

using namespace std;

int main()
{
    //INGRESAR
    float nombres [3][6];

    for (int i=0;i<3;i++){
        for (int j=0;j<6;j++){
        cout << "INGRESE LOS NOTAS: "<<"["<<i<<"]"<<"["<<j<<"]"<<endl;
        cin>>nombres[i][j];
    }
}

//IMPRIMIR
    for (int i=0;i<3;i++){
        for (int j=0;j<6;j++){

        cout <<nombres[i][j]<<"  ";
        }
        cout<<endl;
    }

    return 0;
}
