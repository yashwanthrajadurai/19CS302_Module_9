# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.

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



## Output:

![Screenshot 2025-05-26 170256](https://github.com/user-attachments/assets/b945182b-5f74-4760-a223-09f7ac747f53)


## Result:

Thus the program was executed and the output was verified successfully.
