#include <iostream>
using namespace std;
int main()
{
    int i, j, n;
    cout<<"Enter the number : ";
    cin>>n;
    
    for(i=n; i>1; i--)
    {
        for(j=n;j>=1;j--)
        {
            if(j>i) 
            cout<< j;
            else 
            cout<< i;
        }
        for(j=2;j<=n;j++)
        {
            if(j>i) 
            cout<< j;
            else 
            cout<< i;
        }
        cout<<"\n";
    }    
    for(i=1; i<=n; i++)
    {
        for(j=n;j>=1;j--)
        {
            if(j>i)
            cout<< j;
            else 
            cout<< i;
        }
        for(j=2;j<=n;j++)
        {
            if(j>i) 
            cout<< j;
            else 
            cout<< i;
        }
        cout<<"\n";
    }
    
    return 0;
}
