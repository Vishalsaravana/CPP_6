# SINGLY LINKED LIST

## PROGRAM STATEMENT :

To write a CPP program to INSERT an Element at location 2 using STL and Display the same.

## ALGORITHM:  

1.	Start the program
2.	Initialize a forward_list of integers, flist, with values {1, 2, 3, 4, 5}.
3.	Create an iterator it pointing to the beginning of the list.
4.	Move the iterator it to the second position in the list.
5.	Insert the integer 50 after the position indicated by it.
6.	Use a loop to iterate over flist from the beginning to the end, printing each element.
7.	End the program.

## PROGRAM:
```
#include<iostream>
#include<forward_list>
using namespace std;
int main(){
forward_list<int>flist; flist={1, 2, 3, 4, 5};
auto it=flist.begin(); it++; flist.insert_after(it,50);
for (it=flist.begin();it!=flist.end();it++)
{ cout<<*it<<"";}
}
 ```
## OUTPUT :
![image](https://github.com/user-attachments/assets/5cb617e5-ebdf-4594-ae11-910b9eeac512)

## RESULT :

Thus, the C++ program to INSERT an Element at location 2 using STL and Display the same is created successfully.

