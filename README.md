# My-Cpp-Projects
#include <iostream>

int mod(int a, int b) {
    return a % b;
}

int main() {
    int num1, num2;
    std::cout << "Enter two numbers: ";
    std::cin >> num1 >> num2;
    
    std::cout << "The modulus of " << num1 << " and " << num2 << " is: " << mod(num1, num2) << std::endl;
    
    return 0;
}
