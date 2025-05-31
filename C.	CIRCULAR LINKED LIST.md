# CIRCULAR LINKED LIST

## PROGRAM STATEMENT:

To write a CPP program to SEARCH an element from the Circularly Linked List and Display the same.

## ALGORITHM:  

1.	Start the program.
2.	Define a Node class with data and nextptr (pointer to next node).
3.	Create a create() function to create a new node with given data and set its nextptr to 0.
4.	If the list is empty (head == 0), set both head and tail to the new node, otherwise, add the node at the end and update tail->nextptr to head.
5.	Implement the display() function to traverse the circular linked list and print each node’s data until it reaches back to head.
6.	Implement the search() function to traverse the list and compare each node’s data with a given target, printing whether it is found or not.
7.	In main(), input 5 integers to create the list, input a target element, display the list, and search for the target in the list.
8.	End the program

## PROGRAM:
```
#include<iostream> using namespace std; class Node{
public:
int data;
Node*nextptr;
}*head,*tail,*newn,*temp; void create(int n)
{
newn=new Node; newn->data=n; newn->nextptr=0; if(head==0)
{
head=newn; tail=newn;
}
else{
tail->nextptr=newn; tail=newn;
 
tail->nextptr=head;
}
}
voiddisplay()
{
temp=head; do{
cout<<"Data="<<temp->data<<""; temp=temp->nextptr;
}while(temp->nextptr!=head); cout<<"Data="<<temp->data<<""; cout<<endl;
}
void search(int a)
{
temp=head; boolans=0;
for(int i=0;i<5;i++)
{
if(temp->data==a){ ans=1;
break;
}
else{
temp=temp->nextptr;
}
}
if(ans==1)
{
cout<<"Element"<<a<<" Found";
}
else{
cout<<"Element not Found";
}
}
int main()
{
int num;
for(int i=0;i<5;i++)
{
cin>>num; create(num);
}
int d; cin>>d; display(); search(d);}
 ```
## OUTPUT :
![image](https://github.com/user-attachments/assets/8c667244-17f2-414b-8e19-ac935fa27c1c)

## RESULT:

Thus, the C++ program to SEARCH an element from the Circularly Linked List and Display the same is created successfully.

