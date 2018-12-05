#include <iostream>
using namespace std;

void TowerOfHanoi(int n,char src,char dest,char helper)
{
    if(n==0)
    {
        return;
    }
    //Recursion case
    //First step is to move n-1 disc from sorce to helper
    TowerOfHanoi(n-1,src,helper,dest);
    cout<<"Moving ring "<<n<<" from "<<src<<" to "<<dest<<endl;
    TowerOfHanoi(n-1,helper,dest,src);
}

int main() {
    int n;
    cin>>n;
    TowerOfHanoi(n,'A','B','C');
    return(0);
}

