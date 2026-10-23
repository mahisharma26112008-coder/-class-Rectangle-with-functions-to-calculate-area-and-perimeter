# -class-Rectangle-with-functions-to-calculate-area-and-perimeter

#include<iostream>
  using namespace std;
 class rectangle{
     public:
     int breadth,length;

     void area(){
     cout<<"area "<<length*breadth<<"\n";
 }
     void perameter(){
         cout<<"perameter "<<2*(length + breadth);
     }
 };
int main(){
   rectangle r1;

    cout<<"enter  the value of breadth and height";
    cin>>r1.breadth>>r1.length;
    r1.area();
    r1.perameter();

    return 0;
}
