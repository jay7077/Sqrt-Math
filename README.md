#include<iostream>
#include<math.h>
using namespace std;

int main()
{
    printf("welcome to sqrt calculator\n");
    double argument =0;
    double returnValue =0;

    cin >> argument;
    returnValue= sqrt(argument);
    
    printf("here is your answer\n");
    cout << returnValue << endl;

    system("pause");
    return 0;
    

}
