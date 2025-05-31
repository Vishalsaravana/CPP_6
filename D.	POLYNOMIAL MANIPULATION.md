# POLYNOMIAL MANIPULATION

## PROGRAM STATEMENT:

To debug a C++ function int printList(Node *head) to print the polynomial expression in polynomial addition program using Linked list concept.

## ALGORITHM:  

1.	Define a function printList that takes a pointer to the head node of a linked list as input.
2.	Print "Linked List" as the header.
3.	Use a while loop to traverse the linked list as long as head is not NULL:
4.	For each node, print its coeff (coefficient) followed by "x^" and its power (exponent).
5.	Move to the next node by setting head = head->next.
6.	Once all nodes are printed, return 1 to indicate successful completion.
7.	End the program.

## PROGRAM:
```
int printList(Node*head)
{
cout<<"Linked List"<<endl; while(head!=NULL){
cout<<""<<head->coeff<<"x^"<<head->power; head=head->next;
}
return 1;
}
```
## OUTPUT :
![image](https://github.com/user-attachments/assets/37ff7c3a-b364-40cd-81cb-839829d1b733)

## RESULT:

Thus, the C++ program to print the polynomial expression in polynomial addition program using Linked list concept is created successfully.


