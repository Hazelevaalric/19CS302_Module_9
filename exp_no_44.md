## EX 44 C functions to perform enqueue, dequeue, display, peek in Queue using Array.
DATE:27/03/2026
## AIM:
To write a C Write a functions to perform enqueue, dequeue, display, peek in Queue using Array.

## Algorithm
Start.
Define a variables.
Write a functions to perform enqueue,dequeue ,display,peek in Queue using array.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End

## Program:
```
char queue[50];
int size=10,front,rear,i; 
void enqueue(char data)
{if(rear<size){
if(front==-1){
front=0;
}rear=rear+1; queue[rear]=data;
}{
printf("%c\n",queue[i]);
}
}
void dequeue()
{
if(front==-1||front>rear){
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
void peek()
{
printf("%c\n",queue[front]);
}
}
```
## Output:
<img width="885" height="732" alt="image" src="https://github.com/user-attachments/assets/43ccd247-6f14-442f-b89e-55ba587bd8da" />


## Result:
Thus the program was executed and the output was verified successfully.
