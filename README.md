# Latihan-3
//Nama : Reina Puteri Ramadhani
//NIM : 18320039
//Latihan 3-Structure & Union

#include <iostream.h>
using namespace std;

int main()
{
    cout<<"Program Persentase Kehadiran Mahasiswa"<<endl;
    
    //deklarasi
    
    struct mhs {
        char nama[50];
        int nim[8];
        float hadir;
    };
    struct mhs [5] = {{" Muhammad Abdul",10022001,76.8},{"Dewi Nur",10022002,89},{"Dian Putri",10022003,100},
                        {"Putu Ika",10022004,79},("Aditya",10022005,95.2)};;;;
    
    if(hadir < 80){
        cout<<"Daftar Mahasiswa dengan Persentase Kehadiran di bawah 80%.";
        printf("%d %s\n", mhs[0].nama, mhs[0].nim, mhs[0].hadir);
        printf("%d %s\n", mhs[3].nama, mhs[3].nim, mhs[3].hadir);
        return(0);
        
    else(hadir > 80){
        cout<<"Daftar Mahasiswa dengan Persentase Kehadiran di atas 80%.";
        printf("%d %s\n", mhs[1].nama, mhs[1].nim, mhs[1].hadir);
        printf("%d %s\n", mhs[2].nama, mhs[2].nim, mhs[2].hadir);
        printf("%d %s\n", mhs[4].nama, mhs[4].nim, mhs[4].hadir);
        return(0);
    }
    }  
}
