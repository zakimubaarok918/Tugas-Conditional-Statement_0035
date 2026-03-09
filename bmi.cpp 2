#include <iostream>
using namespace std;

float berat, tinggi;

void inputData(){
    cout<<"Masukkan berat badan: ";
    cin>>berat;

    cout<<"Masukkan tinggi badan: ";
    cin>>tinggi;
}

float hitungBMI(float b, float t){
    return b/(t*t);
}

string kondisiBMI(float bmi){

    if(bmi < 18.5)
        return "Berat Badan Kurang";
    else if(bmi < 25)
        return "Berat Badan Normal";
    else if(bmi < 30)
        return "Berat Badan Kelebihan";
    else
        return "Obesitas";
}

int main(){

    inputData();

    float bmi = hitungBMI(berat, tinggi);

    cout<<"Nilai BMI : "<<bmi<<endl;
    cout<<"Kondisi : "<<kondisiBMI(bmi)<<endl;

    return 0;
}