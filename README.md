# ukan-bilangan-prima-atau-bukan

    #include<iostream>
    using namespace std;

    int main()
    {
    int x,i,count=0;
    cout<<"\n masukkan sebuah angka : ";
    cin>>x;
    for(i=2;2<=x/2;i++)
    {
        if(x%i==0)
        count++;
    }
    if(count>0||x<2)
        cout<<x<<"bukan bilangan prima\n";
    else
        cout<<x<<"\n Bilangan prima \n";
    }
    
![img](https://raw.githubusercontent.com/VIKTORKEVIN/ukan-bilangan-prima-atau-bukan/master/menentukan%20bilangan%20prima%20atau%20bukan.png)
