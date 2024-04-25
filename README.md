#include<iostream>
using namespace std;
int main(){

                                 // SUM OF TWO NUMBERS


    // int a,b;
    // cout<<"enter any two number:";
    // cin>>a>>b;

    // int sum=a+b;
    // cout<<"sum is:"<<sum;


                                 // SIMPLE INTEREST


    // int p,t,r,SI;
    // cout<<"enter the value of p,t,r:";
    // cin>>p>>t>>r;

    // SI=(p*t*r)/100;
    // cout<<"The value of simple interest is:"<<SI;


                                 // AVERAGE OF THREE NUMBERS

    // int a,b,c,avg;
    // cout<<"enter three  numbers:";
    // cin>>a>>b>>c;

    // avg=(a+b+c)/3;

    // cout<<"The average of three numbers is:"<<avg;


                                 // MAXIMUM BETWEEN TWO NUMBERS

    // int a,b;
    // cout<<"enter two numbers:";
    // cin>>a>>b;

    // (a>b)?cout<<"a is max":cout<<"b is max";

                                // NUMBER IS EVEN OR ODD

    // int a;
    // cout<<"enter a number:";
    // cin>>a;

    // if(a%2==0){
    //     cout<<"number is even";
    // }         
    // else{
    //     cout<<"number is odd";
    // }                      


                                // NUMBER IS +VE , -VE OR 0;


    // int n;
    // cout<<"enter a number:";
    // cin>>n;

    // if(n>0){
    //     cout<<"number is +ve";
    // }
    // else if(n<0){
    //     cout<<"number is -ve";
    // }
    // else{
    //     cout<<"number is 0";
    // }


                                // TRIANGLE VALID OR NOT


    // int a,b,c;
    // cout<<"enter the value of a,b,c:";
    // cin>>a>>b>>c;

    // if (a+b>c)
    // {
    //     if (b+c>a)
    //     {
    //         if (c+a>b)
    //         {
    //             cout<<"valid triangle:";
    //         }
            
    //     }
        
    // }
    // else{
    //     cout<<"not a valid triangle";
    // }
    

                                 // PRINT 1 TO N;

    // int n;
    // cout<<"enter a number:";
    // cin>>n;

    // for(int i=1;i<=n;i++){
    //     cout<<i<<endl;
    // }


                                 // EVEN NUMBER FROM 1 TO N

    // int n,num=2,count=0;
    // cout<<"enter a number:";
    // cin>>n;

    // for(int i=0;i<=n/2;i++){

    // if (num<=n)
    // {
    //     cout<<num;
    //     num=num+2;
    //     count++;
    //     cout<<endl;
    // }
    // }
    // cout<<"total even numbers:"<<count;
    
    

                                  // ODD NUMBERS FROM 1 TO N

    // int n,num=1,count=0;
    // cout<<"enter a number:";
    // cin>>n;

    // for(int i=0;i<=n/2;i++){

    // if (num<=n)
    // {
    //     cout<<num;
    //     num=num+2;
    //     count++;
    //     cout<<endl;
    // }
    // }
    // cout<<"total odd numbers:"<<count;
    

                                 // FIND SUM OF 1 TO N

    // int n,sum=0;
    // cout<<"enter a number:";
    // cin>>n;

    // for (int i = 1; i <= n; i++)
    // {
    //     sum=sum+i;
    // }
    // cout<<"sum is:"<<sum;


                                // FIND THE FACTORIAL OF N


    // int n,fact=1;
    // cout<<"enter a number:";
    // cin>>n;

    // for (int i = 1; i <= n; i++)
    // {
    //    fact=fact*i;
    // }
    // cout<<"factorial of "<<n<<" is:"<<fact;

    
    // CHECK PRIME OR NOT

    int n,num=2;
    cout<<"enter a number:";
    cin>>n;

    for(int i=2; i < n; i++){
        if (num<n)
        {
            if (n%num!=0)
            {
                num++;
                cout<<n<<" is prime for:"<<i<<endl;
                
            }
            
            else{
                cout<<"not prime";
                exit(0);
            }
        }
       
    }
      
return 0;
}


