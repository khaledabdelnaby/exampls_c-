### sheet section 1

- 1

Write a program to Solve the following formula: 𝑦−𝑐𝑑+𝑣 where y=10, d=20, Enter the c and v values during the program execution.

```c++

#include <iostream>
using namespace std;
int main() {
    
    int y = 10, c , d =20 , v ; 
    cout << "enter two value : ";
    cin >>c>>v;
    int result; 
    result = y + c*d + v;
    cout<<y<< " + "<<c << " * " << d <<" + "<< v <<"=  "<< result;
    
    

    return 0;
}
```

- 2 

Write a program in C++ to calculate the volume of a cube. Input the side of a cube: 5 Volume=𝑠𝑖𝑑𝑒3

```c++

#include <iostream>
using namespace std;
int main() {
    
    int side ; 
    cout << "enter value : ";
    cin >>side;
     int volume = side * side * side ;
    cout << "volume = "<< volume;
    
    

    return 0;
}
```

- 3

  Write a program in C++ to calculate the volume of a sphere with different radius= 6? ----------------- Sample Output: Input the radius of a sphere: 6 The volume of a sphere is: 904.32 Note: volume of sphere is: V = ⁴⁄₃π r³ where: r=radius, π=3.14

```c++

#include <iostream>
using namespace std;
int main() {
    
    // radius = r 
    int r = 6; 
    float pi = 3.14; 
    float V = (4*pi * r * r * r)/3;
    cout << " the value = "<< V;
    

    return 0;
}
```

- 4

Write a program in C++ to find power )^2 (any number ? 

Note: The user will input the base and exponent numbers.

```c++

#include <iostream>
using namespace std;
int main() {
    float num , powr , result = 1; 
    cout << " enter the base number : ";
	cin >>num;
    cout <<endl << " enter the pow number : " ;
	cin >>powr;
	for (int i=1 ; i<= powr ; i ++){
	  result*=num;   
	}
    cout <<endl<<  " the number after calc bowr= "<< result;
    return 0;
}
```

- 5

Write a program in C++ to calculate the volume of a cylinder. Go to the editor Sample Output: Calculate the volume of a cylinder: ----------------------------------------- Input the radius of the cylinder: 4 Input the height of the cylinder: 8 The volume of a cylinder is: 401.92 

Pictorial Presentation:

![image-20231216175528240](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20231216175528240.png)

```c++

#include <iostream>
using namespace std;
int main() {
  float pi = 3.14 , r=4 , h= 8 ; 
    float volume = pi * r *r * h ;
    float area =( 2* pi * r *r ) + (2* pi * r * h ) ;
    cout << " the volume = "<< volume << endl ;
    cout << " the area = "<< area ;
    
    
    
    return 0;
}
```

- 6

Write a program in C++ to find Size of fundamental data types.

```c++

#include <iostream>
using namespace std;
int main() {
 
   cout << " size of int = "<< sizeof(int)<< " bit"<<endl;
   cout << " size of float = "<< sizeof(float)<< " bit"<<endl;
   cout << " size of double = "<< sizeof(double)<< " bit"<<endl;
   cout << " size of bool = "<< sizeof(bool)<< " bit"<<endl;
   cout << " size of long int = "<< sizeof(long int)<< " bit"<<endl;
   cout << " size of short int = "<< sizeof(short int)<< " bit"<<endl;
   
    return 0;
}
```

- 7

Write a program in C++ to swap two numbers?

```c++

#include <iostream>
using namespace std;
int main() {
 int x, y ;
    cout << " enter x and y : ";
    cin >>x>>y;
    cout << "before swab " <<endl ;
    cout << " x = "<<x <<endl<< " y = "<<y << endl;

    int z ; 
    z = x;
    x=y;
    y=z;
    cout <<" after swab " <<endl; 
    cout << " x = "<<x <<endl<< " y = "<<y << endl;
    return 0;
}
```

- 8

Write a program in C++ to convert temperature in Celsius to Fahrenheit.
Sample Output: Convert temperature in Celsius to Fahrenheit: --------------------------------------------------- Input the temperature in Celsius: 35

 The temperature in Celsius : 35 The temperature in Fahrenheit : 95

![image-20231216181928138](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20231216181928138.png)

```c++

#include <iostream>
using namespace std;
int main() {
    float C ;
    cout << " enter the tempratior by celisus : ";
    cin >>C ;
    float F = (9*C + (32 * 5 ))/5;
    cout << "the tembrationr by Fehr = "<<F<<endl;
    
    
    return 0;
}

```

- 9 

Write a program in C++ that converts kilometers per hour to miles per hour.

```c++

#include <iostream>
using namespace std;
int main() {
    float kel ; 
    cout << " enter kilometers per hour : ";
    cin >>kel;
    cout << " miles per hour= "<<kel* 0.6213712 << endl;
    
    return 0;
}

```

- 10

Write a program in C++ to print the code (ASCII code / Unicode code etc.) of a given character.

```c++

#include <iostream>
using namespace std;
int main() {
    char x ; 
    cout << " enter the char : ";
    cin>>x;
    cout << "the char = "<<int( x)<<" Dec";
    
    return 0;
}
```

### sheet section 2

- 1

Write a program in C++ to display the operation of pre- and post-increment and decrement?

```c++

#include <iostream>
using namespace std;
int main() {
    int x=1;
    int y=1;
    
 cout << "x++ = "<< x++ << endl;
 cout << "++x = " << ++x << endl;
 cout << "y-- = "<< y-- << endl;
 cout << "--y = "<< --y << endl;
     
    return 0;
}
```

- 2

Write a program in C++ to find the third angle of a triangle?

![image-20231216225151988](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20231216225151988.png)

```c++

#include <iostream>
using namespace std;
int main() {
    int a , b=70 , c=50;
    //a + b + c = 180
    a = 180 - ( b + c );
    cout << "angle a = "<<a;
    
    
    return 0;
}
```

- 3

Create a Calculator using the if Statement? 

```c++

#include <iostream>
using namespace std;
int main() {
 
    int num1 , num2;
    char operatore ;
    cout << " enter the first number : ";
    cin>>num1;
    cout << "enter the operator : ";
    cin >>operatore;
    cout << " enter the sacnd number : ";
    cin>>num2;
    if (operatore == '+'){
	cout <<num1 << " + "<< num2 << " = "<< num1 + num2 <<endl;
    }
    else if (operatore == '-'){
	cout <<num1 << " - "<< num2 << " = "<< num1 - num2 <<endl;
    }
     else if (operatore == '*'){
	cout <<num1 << " * "<< num2 << " = "<< num1 * num2 <<endl;
    }
     else if (operatore == '/'){
	cout <<num1 << " / "<< num2 << " = "<< num1 / num2 <<endl;
    }
     else if (operatore == '%'){
	cout <<num1 << " % "<< num2 << " = "<< num1 % num2 <<endl;
    }
    return 0;
}
```

- 4

write a C++ program to find if an integer is even or odd or neither (0)?

```c++

#include <iostream>
using namespace std;
int main() {
 
    int x ; 
    cout << "enter number for chanig even or odd : ";
    cin >>x;
    if (x%2==0 and x!=0 ){
        cout <<" the number is 'even' ";
    }
    else if (x%2!=0 and x!=0 ){
        cout <<" the number is 'odd' ";
    }
    else
     	cout <<" the number is ( 0 ) ";

    return 0;
}
```

- 5

write a c++ program to check some personal data for a job applicant,the program asks him some questions then decide if he acceptable or not acceptable

```c++

#include <iostream>
using namespace std;
int main() {
 	cout << " aplication for ablye job "<< endl ;
    cout <<"_____________________________________"<< endl;
    int ayer , graduated , experiencs ;
    char empaloyed , graduate ;
    cout << "how old are you ? "<< endl;
    cin>>ayer;
    cout<<"when you graduated ?"<<endl;
    cin>>graduated;
    cout << "are you employed_before :Y/N?"<< endl;
    cin >>empaloyed;
    cout << "how many experience years ?"<<endl;
    cin>> experiencs;
    cout <<"what is your graduate grade e=excellent , v=very good , g=good ? "<<endl;
    cin>>graduate;
    
    if((ayer >= 25 and ayer <= 40) and graduated >= 2010 and empaloyed == 'Y' and experiencs >= 3 and (graduate == 'e' or graduate == 'v' )){

        cout <<" you accept ";
    }
    else 
        cout <<" you dont accept ";
        
    
    return 0;
}
```

- 7

write a C++ Program to Find the Length of a String?

```c++

#include <iostream>
using namespace std;
int main() {
 	 string name ; 
     cout << " enter your name : ";
     cin>>name;
    cout << " lingth your name =" << size(name);
    return 0;
}
```

### sheet section 3

- 1

Write a program in C++ that takes a number as input and prints its multiplication table up to 10.

```C++

#include <iostream>
using namespace std;
int main() {
 	
    int num ;
    cout << "enter number : ";
    cin >>num;
    for (int i=1 ; i <=10 ; i++){
        cout << i << " * " <<num <<" = "<<num * i<<endl;
    }
    return 0;
}
```

- 2

Write a C++ program to add all the numbers from 1 to a given number

```c++

#include <iostream>
using namespace std;
int main() {
 	
   int x ;
    cout << " enter number : ";
    cin >>x;
    int sum = 0;
    for(int i=1 ; i<=x ; i++ ){
	sum+=i;
    }
    cout << "the sume = "<< sum <<endl;
    return 0;
}
```

- 3

Write a program in C++ to check whether a number is prime or not

```c++

#include <iostream>
using namespace std;
int main() {
 	
   int x ;
    cout << " enter number : ";
    cin >>x;
 	 int prim=0;
    for (int i=1 ; i<=x ; i++ ){
        if (x % i ==0 ){
		prim++;
        }
    }
    if (prim==2){
        cout << " the number is prime ";   
    }
    else
       cout << " the number is not prime ";
    return 0;
}
```

- 4

Write a program in C++ to find the sum of the series 1 + 1/2^2 + 1/3^3 + …. + 1/n^n.

```c++

#include <iostream>
#include <cmath>
using namespace std;
int main() {
 	int num ;
    double sum = 0;
    cout << "enter number : ";
    cin >>num;
    for (int i=1 ; i<=num ; i++){
         sum+= (1/pow(i,i));
    }
 cout << "the sumiation = "<<sum;
    return 0;
}
```

- 5

Write a program in C++ to calculate the series (1) + (1+2) + (1+2+3) + (1+2+3+4) + ... + (1+2+3+4+...+n).

```c++

#include <iostream>
using namespace std;
int main() {
 	int num ;
    double sum = 0;
    cout << "enter number : ";
    cin >>num;
    for (int i=1 ; i<=num ; i++){
 		for(int j=1 ; j<=i ; j++){
            sum+=j;
        }
    }
 cout << "the sumiation = "<<sum;
    return 0;
}
```

- 6

Write a program in C++ to print a square pattern with # character.

```c++

#include <iostream>
using namespace std;
int main() {
    for (int i=1 ; i<=4 ; i++){
 		for(int j=1 ; j<=4 ; j++){
 			cout << "#  ";
        }
    	cout << endl;
    }
    return 0;
}
```

- 7

Write a program in C++ to display the n terms of harmonic series and their sum.1 + 1/2 + 1/3 + 1/4 + 1/5 ... 1/n terms?

```c++

#include <iostream>
using namespace std;
int main() {
    int num ;
    double sum=0.0;
    cout << "enter number : ";
	cin >>num;
        for (int i=1 ; i<=num ; i++){
            cout << "(1 / "<<i <<" ) ";
            sum+=(1.0/i);
            if (i<num){
                cout << "+ ";
            }
    }
	cout << " = "<<sum;    
    return 0;
}
```

- 8

Write a program in C++ to find the number and sum of all integer between 100 and 200 which are divisible by 9?

```c++
#include <iostream>
using namespace std;
int main() {
 	int sum =0 ;
    for (int i=100 ; i<=200 ; i++){
        if (i%9==0){
			sum+=i;
			cout << i ;
			if (i<200)
			    cout << " + ";
        }
    }
    cout <<" = " <<sum;
    return 0;
}
```

- 9

Write a program in C++ to make such a pattern like right angle triangle using number which will repeat the number for that row?

```c++
#include <iostream>
using namespace std;
int main() {
    int num ;
    cout << "input numcer : ";
	cin >>num;
    for (int i=1 ; i<=num ; i++){
        for (int j=1 ; j<=i ; j++){
            cout <<i;
        }
        cout <<endl;
    }
    return 0;
}
```

- 10

Write a program in C++ to find power of any number using for loop.?

```c++
#include <iostream>
using namespace std;
int main() {
    int num ;
    cout << "input numcer : ";
	cin >>num;
    for (int i=1 ; i<=1 ; i++){
 		cout << " the power = "<< num *num;
    }
    return 0;
}
```

- 11

Write a program in C++ to enter any number and print all factors of the number?

```c++
#include <iostream>
using namespace std;
int main() {
   
    for (int i=1 ; i<=12 ; i++){
        for(int j=1 ; j<=i ; j++){
			if (i*j==12){
                cout << i <<" * "<<j <<" = "<<i*j <<endl;
                
            }            
        }
    }
   
//   _______________________________________________
    for (int i=1 ; i<=12 ; i++){
        for(int j=1 ; j<=i ; j++){
			if (i*j==12){
			   
                cout << i <<" , "<<j << " , ";
                        
            }       
        }
    }
    return 0;
}
```

