# Konversi-Detik-Ke-Hari-Jam-Menit-Detik
    #include <iostream>

    using namespace std;

    int main(){

    int totaldetik, hari, hari1,jam,jam1,menit, menit1, detik;

    cout<<"Konversi Detik ke jam, menit, Detik";cout<<endl;

    cout<<"Masukan Detik: "; cin>>totaldetik;

        hari=totaldetik/86400;
        hari1=totaldetik%86400;
        jam=hari1/3600;
        jam1=hari1%3600;
        menit=jam1/60;
        menit1=jam1%60;
        detik=menit1;

    cout<<hari<< " hari "<<jam<<" jam "<<menit<<" menit "<<detik<<" detik"<<endl;

    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Konversi-Detik-Ke-Hari-Jam-Menit-Detik/master/Konversi%20Detik%20Ke%20Hari%2C%20Jam%2C%20Menit%2C%20Detik.png)
