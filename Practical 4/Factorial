#include <iostream>
using namespace std;
int iterative(int n) {
    int f = 1;
    for (int i = 1; i <= n; i++)
        f *= i;
    return f;
}
int recursive(int n) {
    if (n <= 1) return 1;
    return n * recursive(n - 1);
}
int main() {
    int n;
    cin >> n;
    cout << "Iterative: " << iterative(n) << endl;
    cout << "Recursive: " << recursive(n) << endl;
    return 0;
}
