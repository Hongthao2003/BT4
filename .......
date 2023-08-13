#include <iostream>

using namespace std;

int Dem(int n){
    int dem =0;
    while(n > 0){
        int du = (n%10);
        dem++;
        n /=10;
    }
    return dem;
}

int Tong(int n){
    int sum =0;
    while(n > 0){
        sum += (n%10);
        n /=10;
    }
    return sum;
}

int TongCSLE(int n){
    int sum =0;
    while(n > 0){
        int du = (n%10);
        if(du % 2==1){
            sum += du;
        }
        n /=10;
    }
    return sum;
}

int TongCSChan(int n){
    int sum =0;
    while(n > 0){
        int du = (n%10);
        if(du % 2==0){
            sum += du;
        }
        n /=10;
    }
    return sum;
}

void SoDaoNguoc(int n){
    int sodao = 0;
    while(n > 0){
        sodao = sodao * 10 + (n % 10);
        n /= 10;
    }
    
    cout << "So dao nguoc cua nó la: " << sodao;
   
}
int main()
{
    int chon;
    cout << "Nhap so cau muon xem: ";
    cin >> chon;
    
    switch(chon) {
        case 1:{
            int n;
            cout << "Nhap so duong: ";
            cin >>  n;
            int KQ = Dem(n);
            cout << "So luong chu so la: " << KQ;
            break;}
        case 2:{
            int n;
            cout << "Nhap so duong: ";
            cin >>  n; 
            int KQ = Tong(n);
            cout << "Tong cac chu so la: " << KQ;
            break;}
        case 3:{
            int n;
            cout << "Nhap so duong: ";
            cin >>  n; 
            int KQ = TongCSLE(n);
            cout << "Tong cac chu so le la: " << KQ;
            break;}
        case 4:{
            int n;
            cout << "Nhap so duong: ";
            cin >>  n; 
            int KQ = TongCSChan(n);
            cout << "Tong cac chu so le la: " << KQ;
            break;}
        case 5:{
            int n;
            cout << "Nhap so duong: ";
            cin >>  n; 
            SoDaoNguoc(n);
            break;}
    }

    return 0;
}
