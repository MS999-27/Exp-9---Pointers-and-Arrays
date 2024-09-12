# AIM
To use pointers and access elements of array and find address of different data types.

# Software Used
VS Code AND Online Cpp compiler

# Problem Statement

1.) Write a c++ program to initialize pointers of different data types and print the required values.

2.) Write a c++ program to access elements of array using pointer.

3.) Write a c++ program to access elements of array without using pointer variable.

# Theory

Pointers are symbolic representations of addresses. They enable programs to simulate call-by-reference as well as to create and manipulate dynamic data structures. Iterating over elements in arrays or other data structures is one of the main use of pointers. 

# Problem Codes

```javascript
 

 //INITIALIZE POINTERS OF DIFFERENT DATA TYPES

//INT
 #include <iostream>
using namespace std;
int main()
{
    int a = 10;
    int *ptr;
    ptr=&a;
   cout<< "The value pointed by *ptr is: "<<*ptr << endl;
    cout << "The value in b is: " <<a << endl;
    cout << "The value in pointer variable ptr is: "<<(void*)ptr << endl;

    cout << "the address of variable b is: "<<&a << endl;
    ptr ++;
    cout<< "After increment the value in pointer variable ptr is: " << (void*)ptr << endl;
}

//FLOAT
 #include <iostream>
using namespace std;
int main()
{
    float a = 'A';
    float *ptr;
    ptr=&a;
     cout<< "The value pointed by *ptr is: "<<*ptr << endl;
    cout << "The value in b is: " <<a << endl;
    cout << "The value in pointer variable ptr is: "<<(void*)ptr << endl;

    cout << "the address of variable b is: "<<&a << endl;
    ptr ++;
    cout<< "After increment the value in pointer variable ptr is: " << (void*)ptr << endl;
}

//CHAR
#include<iostream>
using namespace std;
int main()
{
    char a = 'c'; 
    

    char *ptr;

    ptr = &a;

    cout<< "The value pointed by *ptr is"<<*ptr << endl;
    cout << "The value in b is" <<a << endl;
    cout << "The value in pointer variable ptr is"<<(void*)ptr << endl;

    cout << "the address of variable b is "<<&a << endl;
    ptr ++;
    cout<< "After increment the value in pointer variable ptr is: " << (void*)ptr << endl;

    
}


//ACCESS ELEMENTS OF ARRAY USING POINTER.

#include<iostream>
using namespace std;
int main()
{
    int *ptr;
    int a[5] = { 1,2,4,8,9};
    ptr = &a[0];
    int i;
    for(i=0 ; i<5 ; i++)
    {
        cout << "Element "<< i+1 <<" "<<"="<<" "<<*ptr << endl;
        ptr ++;

    }
}

//ACCESS ELEMENTS OF ARRAY WITHOUT USING POINTER VARIABLE.

#include<iostream>
using namespace std;
int main()
{
    int *ptr;
    int a[5] = { 1,2,4,8,9};
    ptr = &a[0];
    int i;
    for(i=0 ; i<5 ; i++)
    {
        cout << "Element "<< i+1 <<" "<<"="<<" "<<*(a+i) << endl;
        ptr ++;

    }
}


```

# Output
## INITIALIZING POINTERS OF DIFFERENT TYPES
## A) INT
![exp 9- Pointer int](https://github.com/user-attachments/assets/b944d367-c603-4031-8a87-a6c4bea8a044)

## B) FLOAT
![Exp 9- Pointer Float](https://github.com/user-attachments/assets/72aa9bcd-eebf-4197-bd14-aaea28acab60)

## C) CHAR
![POINTER CHAR](https://github.com/user-attachments/assets/2e7eb783-3680-4b07-9d10-3e38935fb503)

## ACCESS ELEMENT OF ARRAY USING POINTER
![EXp 9 Extract element of array using pointer](https://github.com/user-attachments/assets/80a6564d-68a8-49af-939c-2f6813bac193)

## ACCESS ELEMENT OF ARRAY WITHOUT USING POINTER
![Exp 9 without pointer](https://github.com/user-attachments/assets/7b9840ae-6d0b-4f8e-b155-fc6534b5eec5)

# Conclusion

We learnt to initialize pointers of different data types.

We learnt to access elements of array using pointers and without pointers variable.
