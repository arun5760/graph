#include <iostream>
using namespace std;
int main()
{
    int x,y;
    cin>>x>>y;
    if(x>0 & y>0)
    {
        cout<<"Ist quadrant ";
    }
    else if(x<0 && y>0)
    {
        cout<<"IInd quadrant";
    }
    else if(x<0 && y<0)
    {
        cout<<"IIIrd quadrant";
    }
    else if(x>0 && y<0)
    {
        cout<<"IVth quadrant";
    }
    return 0;
}
