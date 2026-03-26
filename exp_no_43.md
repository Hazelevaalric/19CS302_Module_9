## EX 43 C program to Write a function to display queue elements using array.
DATE:26/03/2026
## AIM:
To Write a function to display queue elements using array.

## Algorithm
Start.
Define a variables.
Write a function to display queue elements using array.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.

## Program:
```
float queue[50];
int rear=-1,front=-1,i; 
void display()
{
if(front==-1||front>rear) 
printf("No elements to display\n"); 
else
{
for(i=front;i<=rear;i++) 
printf("%.1f\n",queue[i]);
}
}
void display()
{
if(front==-1||front>rear)
{
printf("No elements to display\n");
else
{
for(i=front;i<=rear;i++)
}
}
```
## Output:
<img width="1125" height="731" alt="image" src="https://github.com/user-attachments/assets/88d81a2c-d171-4cf2-8f47-9b0a6ffd3b16" />



## Result:
Thus the program was executed and the output was verified successfully.
