//Using c++
//An array is a type of data structure that stores elements of the same type in a contiguous block of memory. In an array a , of size N, each memory location has some unique index i. (where 0<=N ), that can be referenced as A[i] or Ai .

//Reverse an array of integers.

//reverseArray has the following parameter(s):
//int A[n]: the array to reverse
#include <iostream>
using namespace std;

int main()
{
    int arr[1000], N, j,ex;

    //cout << "Please enter the size for array: ";
    cin >> N;

    //cout << "Please enter " << N << " array elements: ";

    for (int i = 0; i < N; i++)
    {
        cin >> arr[i];
    }

    j = N - 1;
    for (int i = 0; i < j; i++, j--)
    {
        ex = arr[i];
        arr[i] = arr[j];
        arr[j] = ex;
    }

    //cout << endl <<"The reverse the array is:"<<endl;

    for (int i = 0; i < N; i++)
    {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}
