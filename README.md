#include <iostream>
#include <math.h>

using namespace std;
float a,b,c,alpha;

int main() {
    cin>>a;
    cin>>b;
    cin>>alpha;
    c= sqrt(pow(a,2)+pow(b,2)-2*a*b* cos(alpha));
    cout<<c;
    return 0;
}
