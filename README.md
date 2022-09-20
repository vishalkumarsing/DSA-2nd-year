# DSA-2nd-year
NOTES AND ASSIGNMENT 2ND YEAR
// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
int main() {
int n;
cin>>n;
int a[n];
for(int i=0;i<n;i++){
    cin>>a[i];
}
int max=a[0];
for(int i=0;i<n;i++){
    
    if(a[i]>max){
        max=a[i];
    cout<<"i;"<<i<<" a[i];"<<a[i] <<"max"<<max<<endl;
}
else{
    cout<<"max"<<max;
}
}
    return 0;
}
