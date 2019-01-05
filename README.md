# C-Konversi-Suhu

    #include <iostream>
    #include <conio.h>
    #include <stdio.h>

    using namespace std;

    int main(void)
    {
    ya : float suhu, hasil;
    int kode;
    char pilih;

    cout << "\t\t\Pelita bangsa\n\n" << endl;
    cout << "==========================================\n" << endl;
    cout << "Nama : Rafi Alwan Setyawan \nNIM  : 311810325\n" << endl;
    cout << "==========================================\n" << endl;

    cout << "\t     Konversi Suhu\n" << endl;

    cout<<" 1. Celcius      -> Reamur "<<endl;
    cout<<" 2. Celcius      -> Fahrenheit "<<endl;
    cout<<" 3. Celcius      -> Kelvin "<<endl;
    cout<<" 4. Reamur       -> Celcius "<<endl;
    cout<<" 5. Reamur       -> Fahrenheit "<<endl;
    cout<<" 6. Reamur       -> Kelvin "<<endl;
    cout<<" 7. Fahrenheit   -> Celcius "<<endl;
    cout<<" 8. Fahrenheit   -> Reamur "<<endl;
    cout<<" 9. Fahrenheit   -> Kelvin "<<endl;
    cout<<" 10.Kelvin       -> Celcius "<<endl;
    cout<<" 11.Kelvin       -> Reamur "<<endl;
    cout<<" 12.Kelvin       -> Fahrenheit "<<endl;
    cout << "==========================================\n" << endl;
    cout<<endl;
    cout<<"Masukkan Kode Angka Menu Yang Anda Pilih = ";
    cin>>kode;
    cout<<endl;

    switch(kode)
    {
    case 1:
    cout<<"Masukkan Suhu Dalam Celcius      = ";
    cin>>suhu;
    hasil=0.8*suhu;
    cout<<"Suhu Dalam Reamur                = "<<hasil<<" R"<<endl;
    break;
    case 2:
    cout<<"Masukkan Suhu Dalam Celcius      = ";
    cin>>suhu;
    hasil=1.8*suhu+32;
    cout<<"Suhu Dalam Fahrenheit            = "<<hasil<<" F"<<endl;
    case 3:
    cout<<"Masukkan Suhu Dalam Celcius      = ";
    cin>>suhu;
    hasil= suhu+273;
    cout<<"Suhu Dalam Kelvin                = "<<hasil<<" K"<<endl;
    break;
    case 4:
    cout<<"Masukkan Suhu Dalam Reamur       = ";
    cin>> suhu ;
    hasil= 1.25*suhu;
    cout<<"Suhu Dalam Celcius               = "<<hasil<<" C"<<endl;
    break;
    case 5:
    cout<<"Masukkan Suhu Dalam Reamur       = ";
    cin>>suhu ;
    hasil= 2.25*suhu+32;
    cout<<"Suhu Dalam Fahrenheit            = " <<hasil<<" F"<<endl;
    break;
    case 6:
    cout<<"Masukkan Suhu Dalam Reamur       = ";
    cin>>suhu ;
    hasil= 1.25*suhu+273;
    cout<<"Suhu Dalam Kelvin                = " <<hasil<<" K"<<endl;
    break;
    case 7:
    cout<< "Masukkan Suhu Dalam Fahrenheit  = ";
    cin>>suhu;
    hasil= 5*(suhu-32)/9;
    cout<<"Suhu Dalam Celcius               = " <<hasil<<" C"<<endl;
    break;
    case 8:
    cout<<"Masukkan Suhu Dalam Fahrenheit   = ";
    cin>>suhu;
    hasil= 4*(suhu-32)/9;
    cout<<"Suhu Dalam Reamur                = " <<hasil<<" R"<<endl;
    break;
    case 9:
    cout<<"Masukkan Suhu Dalam Fahrenheit   = ";
    cin>>suhu;
    hasil= ((5*(suhu-32)/9)+273);
    cout<<"Suhu Dalam Kelvin                = " <<hasil<<" K"<<endl;
    break;
    case 10:
    cout<<"Masukkan Suhu Dalam Kelvin       = ";
    cin>>suhu;
    hasil= suhu-273;
    cout<<"Suhu Dalam Celcius               = " <<hasil<<" K"<<endl;
    break;
    case 11:
    cout<<"Masukkan Suhu Dalam Kelvin       = ";
    cin>>suhu;
    hasil= 0,8*(suhu-273);
    cout<<"Suhu Dalam Reamur                = " <<hasil<<" R"<<endl;
    break;
    case 12:
    cout<<"Masukkan Suhu Dalam Kelvin       = ";
    cin>>suhu;
    hasil= (1,8*(suhu-273))+32;
    cout<<"Suhu Dalam Fahrenheit            = " <<hasil<<" F"<<endl;
    break;
    default:
    cout<<"Kode angka salah" <<endl;
    break;
    }

    cout<<"Apkah Anda Ingin Mengulangi (Y/T)? ";
    cin>>pilih;
    cout<<endl;
    jika_masukan_salah:
    switch(pilih)
    {
        case 'Y':
            goto ya;
            break;
            case 'T':
            break;
            default:

    cout<< "Masukan Salah " << endl << endl;
    cout<< "Apakah Anda Ingin Mengulangi (Y/T)? ";
    cin>> pilih;
    cout<<endl;
    goto jika_masukan_salah;
    break;
    }
        getch();
    return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Konversi-Suhu/blob/master/C++%20Konversi%20Suhu.png?raw=true)
