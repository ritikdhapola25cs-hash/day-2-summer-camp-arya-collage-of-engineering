# day-2-summer-camp-arya-collage-of-engineering
Day 1 of the c++ programming in the summer training camp 
//this is the program of the even odd calculator



#include<iostream>
using namespace std;
int main(){int num;
    cout<<"enter a number even or odd "<<endl;
    cin>>num;
    if(num%2==0){
        cout<<"even number"<<endl;
    }
    else
    cout<<"odd number "<<endl;
    return 0;
}


//this is the program largest among the three number 

#include<iostream>
using namespace std;
int main(){
    int x,y,z;
    cout<<"enter three number "<<endl;
    cin>>x>>y>>z;
    if(x<y){
        if(y<z){cout<<z;
    }
    else{cout<<y;}
}
else{
    if(x>z){cout<<x;}
    else{cout<<z;}
}
return 0;
}


//this is the program of the grade calculator

#include<iostream>
using namespace std;
int main(){
    int tmarks,sub1,sub2,sub3;
    float per;
    cout<<"enter marks of the students out of 100 "<<endl;
    cin>>sub1>>sub2>>sub3;
    tmarks=sub1+sub2+sub3;
    per=tmarks/3;
    cout<<"total marks "<<tmarks<<endl;
    cout<<"per "<<per<<endl;
    if(per>90){
        cout<<"grade A "<<endl;
    }
    else if(75<=per && per<=90){
        cout<<"grade B "<<endl;
    }
    else
    cout<<"grade C "<<endl;
    return 0;
}


//this is the code of the simple calculator

#include <iostream>
using namespace std;
int main() {
    char op;
    double num1, num2;

    cout << "Enter an operator +, -, *, / ";
    cin >> op;

    cout << "Enter two numbers: ";
    cin >> num1 >> num2;
    switch (op) {
        case '+':
            cout << num1 << " + " << num2 << " = " << num1 + num2 << endl;
            break; 

        case '-':
            cout << num1 << " - " << num2 << " = " << num1 - num2 << endl;
            break;

        case '*':
            cout << num1 << " * " << num2 << " = " << num1 * num2 <<endl;
            break;

        case '/':
                cout << num1 << " / " << num2 << " = " << num1 / num2 << endl;
            
            break;

        default:
            cout << "Error: Invalid operator." << endl;
            break;
    }

    return 0;
}

//this is the code of the positive negative and zero


#include<iostream>
using namespace std;
int main(){int num;
    cout<<"enter a number "<<endl;
    cin>>num;
    if(num>0){
        cout<<"positive number "<<endl;
    }
    else if(num<0){
        cout<<"negative number "<<endl;
    }
    else
    cout<<"it is zero "<<endl;
    return 0;
}
