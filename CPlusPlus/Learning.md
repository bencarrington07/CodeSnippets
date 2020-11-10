# Material Gathered while learning more C++

## Using cin and cout
```c++
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int a = 0;
    int b = 0;
    int c = 0;
    
    cin >> a >> b >> c;
    cout << a + b +c << endl;  
    return 0;
}
```

## Case statements

```c++
#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    // Complete the code.
    //Variables
    int a, b;
    string one = "one";
    string two = "two";
    string three = "three";
    string four = "four";
    string five = "five";
    string six = "six";
    string seven = "seven";
    string eight = "eight";
    string nine = "nine";
    
    cin >> a >> b;
    
    for(int i = a; i <= b; i++){
        if(i >= 1 && i <= 9){
            switch(i){
            case 1 :
                cout << one << endl;
                break;
            case 2 :
                cout << two << endl;
                break;
            case 3 :
                cout << three << endl;
                break;
            case 4 :
                cout << four << endl;
                break;
            case 5 :
                cout << five << endl;
                break;
            case 6 :
                cout << six << endl;
                break;
            case 7 : 
                cout << seven << endl;
                break;
            case 8 :
                cout << eight << endl;
                break;
            case 9 : 
                cout << nine << endl;
                break;
            }    
        } 
        else if(i % 2 == 0) {
            cout << "even" << endl;
        }
        else{
            cout << "odd" << endl;
        }
        
    }
    return 0;
}
```
