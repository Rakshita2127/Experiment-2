# AIM
To learn about different data types and their size and demonstration of storage classes.

# Software Used
VS Code

# Problem Statement
Write a program to show size of different data types and to Write a program for static class.

# Theory
 
| Data type  | Size (bytes) |
| ------------- | ------------- |
|int	  | 4  |
| float  | 4 |
|string| 24 |
|char| 1 |
|short int| 2|

 _'size of'_ function is used to get the size of data type.


# Program Codes

```javascript
//Size
#include<iostream>
using namespace std;
int main()
{ 
cout << "Size of Integer is: "   << sizeof(int) <<" bytes"<< endl;
cout << "Size of Float is: "   << sizeof(float) <<" bytes"<< endl;
cout << "Size of String is: "   << sizeof(string) <<" bytes"<< endl;
cout << "Size of Character is: "   << sizeof(char) <<" bytes"<< endl;
cout << "Size of Short Integer is: "   << sizeof(short int) <<" bytes"<< endl;
}

//Static
#include<iostream>
using namespace std;
void staticExample(){
int z = 0;
z++;
cout<<"the value of z is: "<<z<<endl;
}
int main(){
staticExample();
staticExample();
return 0;
}
```

## Output
1.) Size of data types
![image](https://github.com/user-attachments/assets/237b627a-0a76-4002-837c-6561820045b5)

![image](https://github.com/user-attachments/assets/dfc87f08-f26b-4854-b2db-0ad67c67c253)

# Cocnclusion
We learnt to use _'size of'_ function & static class.
We learnt about different data types and their use.
