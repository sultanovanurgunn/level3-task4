# level3-task4
#include <iostream>
using namespace std;
int main() {
    int n;
    unsigned long long F=1;
    
    cout<<"ededi daxil edin: ";
    cin>> n;
    if (n<0){
        cout<< "menfi ededin faktoriali olmur."<<endl;
    } else {
        for (int i=1; i<= n; ++i){
            F*=i;
        }
        cout<< n <<"! = "<<F<< endl;
    }
    return 0;
    }
