## EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
DATE:26/03/2026
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations.

## Algorithm
Start.
Define a variables.
Write a functions to perform enqueue and,display elements in Queue using array.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End

## Program:
```
char queue[50];
int size=10,front,rear,i; 
void enqueue(char data)
{
if(rear<size)
{
if(front==-1)
{
front=0;
}
rear=rear+1; 
queue[rear]=data;
}
{
printf("%c\n",queue[i]);
}
}
void dequeue()
{
if(front==-1||front>rear)
{
printf("Queue Underflow\n");
}
else
{
front=front+1;
}
}
void display()
{
for(i=front;i<=rear;i++)
printf(“%c “,queue[i]);
}
```
## Output:
<img width="905" height="729" alt="image" src="https://github.com/user-attachments/assets/87507415-a734-45fc-b868-afa1b5ebdb75" />


## Result:
Thus the program was executed and the output was verified successfully.
