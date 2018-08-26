#include <iostream>
 using namespace std;
 int main ()

{
    int one, two, three, sum;
    cout<<"_______________ Welcome User!_____________" <<endl;
    cout<<"There are 3 different types of trees in our backyard, guava tree, acacia tree, and mango tree. How many trees would be in our backyard?\n\n";
  
    cout<<"Lets calculate the total numner of trees in our backyard!" <<endl;
    cout<<"Enter the no. of Guava tree."<<endl;
    cin>> one;
    cout<<"Enter the no. of Acacia tree."<<endl;
    cin>> two;
    cout<<"Enter the no. of Mango tree."<<endl;
    cin>> three;
    sum=one+two+three;
    cout<<"There are "<<one<<" Guava tree/s, "<<two<<" Acacia tree/s, and "<<three<<" Mango tree/s for a total of "<<sum<<" trees in our backyard!" <<endl;
    
    return 0;
}
