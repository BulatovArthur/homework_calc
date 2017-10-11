#include <iostream>
#include <cmath>
#include <locale>

using namespace std;

int main() {
  int count;
  int a, b;
  setlocale(LC_ALL, "RUSSIAN");
  do {
    cout << "Viberete deistvie:	1) + 2) - 3) * 4) / 5) ^ 6) % 7) < 8) > "
            "9) & 10) | 11) !: ";
    cin >> count;
    cout << "Vvedite pervoe chislo: ";
    cin >> a;
    cout << "Vvedite vtoroe chislo: ";
    cin >> b;
    switch (count) {
      case 1: {
        cout << a << "+" << b << "=" << a + b << endl;
        break;
      }
      case 2: {
        cout << a << "-" << b << "=" << a - b << endl;
        break;
      }
      case 3: {
        cout << a << "*" << b << "=" << a * b << endl;
        break;
      }
      case 4: {
        if (b != 0)
          cout << a << "/" << b << "=" << a / b << endl;
        else
          cout << "kto na 0 delit-to?" << endl;
        break;
      }
      case 5: {
        cout << a << "^" << b << "=" << pow(a, b) << endl;
        break;
      }
      case 6: {
        cout << a << "%" << b << "=" << (a % b) << endl;
        break;
      }
      case 7: {
        cout << a << "<" << b << "=" << (a << b) << endl;
        break;
      }
      case 8: {
        cout << a << ">" << b << "=" << (a >> b) << endl;
        break;
      }
      case 9: {
        cout << a << "&" << b << "=" << (a & b) << endl;
        break;
      }
      case 10: {
        cout << a << "|" << b << "=" << (a | b) << endl;
        break;
      }
      case 11: {
        cout << "!" << a << "=" << (!a) << endl;
        break;
      }
      default:
        cout << "Nepravilnoe deistvie" << endl;
    }
  } while (count, cout << endl << "Repeat? ");
  system("pause");
  return 0;
}
