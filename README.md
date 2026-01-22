# MatematikFinal-soru1-ve-soru2
Khamit Sarsenov
2507020082
bilgisayar mühendisliği

soru 1:

     #include <iostream>
     #include <cmath>
     using namespace std;

    int main() {
    double a, b, c;
     cout << "a, b, c katsayilarini giriniz: ";
     cin >> a >> b >> c;

    double delta = b*b - 4*a*c;
    cout << "Diskriminant (Δ) = " << delta << endl;

    if (delta < 0) {
        cout << "Gercek kok yoktur." << endl;
    }
    else if (delta == 0) {
        double x = -b / (2*a);
        cout << "Tek bir gercek kok vardir: x = " << x << endl;
    }
    else {
        double x1 = (-b + sqrt(delta)) / (2*a);
        double x2 = (-b - sqrt(delta)) / (2*a);
        cout << "Iki farkli gercek kok vardir:" << endl;
        cout << "x1 = " << x1 << endl;
        cout << "x2 = " << x2 << endl;
    }

    return 0;
    }

soru 2: Dosyayı yükledim
