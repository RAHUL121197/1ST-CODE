// Online C++ compiler to run C++ program online
#include <iostream>
#include<string>
using namespace std;

class Teacher{
 private:
 double salary;
 public:
  string name;
  string dept;
  string subject;
  
  
  
  void chengeDept(string newDept)
  {
      dept=newDept;
      
  }
  void setSalary(double s)
  {
      salary=s;
  }
  double getsalary()
  {
      return salary;
  }
};

int main() {
   
   Teacher t1;
   t1.name="NAME:Rahul";
   t1.subject="SUB:c++";
   t1.dept="DEPT;computer sci";
   t1.setSalary(25000);
   
   
   cout<<t1.name<<endl;
   cout<<t1.subject<<endl;
   cout<<t1.dept<<endl;
   cout<<t1.getsalary() <<endl;
   
    return 0;
}
