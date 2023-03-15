#include <iostream>

using namespace std;

int add(int x, int y) {
  return x + y;
}

int multiply(int x, int y) {
  return x * y;
}

void printResult(int result) {
  cout << "The result is: " << result << endl;
}

int main() {
  int a = 5;
  int b = 10;

  int sum = add(a, b);
  printResult(sum);

  int product = multiply(a, b);
  printResult(product);

  return 0;
}
