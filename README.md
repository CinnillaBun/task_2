# task_2
#include <iostream>
 
using namespace std;
 
int f(int n){
    int a = 0;
    int b = 1;
    for (int i = 0; i < n; i++)
    {
        cout << a << " ";
        a = a + b;
        b = a - b;
    }
    return a;
}
 
int main(){
    int n;
    cout << "n = ";
    cin >> n;
    f(n);
    return 0;
}
