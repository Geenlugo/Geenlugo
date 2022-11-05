#include <iostream>
using namespace std;

float const lpg= 0.264179;
float calc(float litres, float miles)
{
    float gal;
    gal= lpg* litres;
    float milage= miles/gal;

    return(milage);
}
int main()
float lit,miles;
char ch;
do{
    cout<<"/n enter number of litres of gasoline: ";
    cin>>lit;

    cout<<"/n enter the number of miles travelled: ";
    cin>> miles;
    cout<<"/n Number of miles per gallon the car delivered:";
        cout<<"/n Number of miles per gallon the car delivered:";
    cout<< calc(lit, miles)<<endl;

return 0;
}
