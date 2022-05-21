#include <iostream>
using namespace std;

void selection_sort(int arr[], int s, int e, int max)
{
   
   int temp=0;
   
   if(s==e)
   return;
   
    for(int i=0; i<=e; i++)
    {
        if(arr[i] >= arr[max])
        max= i;
        
        
    }
    temp= arr[max];
    arr[max]= arr[e];
    arr[e]= temp;
    
    
    selection_sort(arr, 0, e-1, 0);
}

int main()
{
    
    int arr[]= {5,4,8,2,1,6,1,3,4,5,6,7};
    selection_sort(arr, 0, sizeof(arr)/sizeof(arr[0])-1,0);
    
    for(int i=0; i<sizeof(arr)/sizeof(arr[0]); i++)
    {
        cout<<arr[i]<<" ";
    }

    return 0;
}
