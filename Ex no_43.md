# EX 43 C program to Write a function to display queue elements using array.

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


## Output:

![Screenshot 2025-05-26 165840](https://github.com/user-attachments/assets/8a1d1c8d-4998-43a1-bd15-1634362ca440)


## Result:

Thus the program was executed and the output was verified successfully.
