#include <iostream>
#include <bitset>

int main() {
int numero;
std::cout << "digite seu numero: ";
std::cin >> numero;

std::bitset<sizeof(int)*8> binario(numero);
std::cout << "o numero " << numero << " em binário é: " << binário << std::endl;

return 0;
}
