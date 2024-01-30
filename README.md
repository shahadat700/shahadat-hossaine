#include<iostream>
#include<iomanip>
#include<cmath>
using namespace std;
int main()
{
    double leangth_a,leangth_b,leangth_c,semi_pm,area;
    cout<<fixed;
    cout<<setprecision(6);
    cout<<"enter 1'st leangth:";//<<endl;
    cin>>leangth_a;
    cout<<"enter 2'nd leangth:";//<<endl;
    cin>>leangth_b;
    cout<<"enter 3'rd leangth:";//<<endl;
    cin>>leangth_c;

    semi_pm=(leangth_a+leangth_b+leangth_c)/2;
    area=sqrt(semi_pm*(semi_pm-leangth_a)*(semi_pm-leangth_b)*(semi_pm-leangth_c));
    cout<<"The area of triangle is="<<area;





return 0;







}
