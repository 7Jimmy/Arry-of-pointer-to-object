#include<iostream>
using namespace std;
class test{
	private:
		char name;
		public:
			void in(){
				cout<<"Enter the integer"<<endl;
				cin>>n;
			}
				void out(){
				cout<<"the integer"<<n<<endl;
				
			}
};
int main(){
test *ptr[5];
ptr[5]=new test;
for(int i=1;i<=4;i++){
	ptr[i]->in();
	
}
for(int i=1;i<=4;i++){
	ptr[i]->out();
}
	return 0;
}
