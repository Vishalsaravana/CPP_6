# DOUBLY LINKED LIST

## PROGRAM STATEMENT:

To write a CPP program to INSERT an Element at LOCATION 1 in Doubly Linked List Using STL and Display the same.

## ALGORITHM:  

1.	Start the program.
2.	Initialize an empty list ele of integers.
3.	Use a loop to input 5 integers from the user, adding each to the end of ele using push_back.
4.	Input an additional integer, ent, and add it to the front of ele using push_front.
5.	Print "List: ".
6.	Use a loop to iterate through ele from beginning to end, printing each element.
7.	End the program.

## PROGRAM:
```
#include<iostream> #include<list> usingnamespacestd; int main()
{
list<int> ele; int num,i,ent;
for(i=0;i<5;i++)
{
cin>>num; ele.push_back(num);
}
cin>>ent; ele.push_front(ent); cout<<"List: ";
for(autoit=ele.begin();it!=ele.end();it++)
{
cout<<*it<<" ";
}
}
``` 
## OUTPUT :
![image](https://github.com/user-attachments/assets/2241e278-9215-4f07-aaba-770ff6fe9182)

## RESULT:

Thus, the C++ program to INSERT an Element at LOCATION 1 in Doubly Linked List Using STL and Display the same is created successfully.
 

