#include <stdio.h>
#define MAX_SIZE 5
int circular_queue[MAX_SIZE];
int front = -1, rear = -1;

int is_empty() {
    return (front == -1 && rear == -1);
}
int is_full() {
    return ((rear + 1) % MAX_SIZE == front);
}
void write_queue(int data) {
    if (is_full()) {
        front = (front + 1) % MAX_SIZE;
    } else if (is_empty()) 
{
        front = 0;
        rear = 0;
    }
 else {
        rear = (rear + 1) % MAX_SIZE;
    }
    circular_queue[rear] = data;
}
int read_queue() {
    int data;
    if (is_empty()) {
        printf("Queue is empty.\n");
        return -1; // Return -1 to indicate an error
    } else if (front == rear) {
        data = circular_queue[front];
        front = -1;
        rear = -1;
    } else
 {
        data = circular_queue[front];
        front = (front + 1) % MAX_SIZE;
    }
    return data;
}
void clear_queue() {
    front = -1;
    rear = -1;
}
int main() {
    write_queue(10);
    write_queue(20);
    write_queue(30);
    write_queue(40);
    write_queue(50);
        printf("Deleted element: %d\n", read_queue());
    write_queue(60);

    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    clear_queue();

    return 0;
}
#include <stdio.h>
#define MAX_SIZE 5
int circular_queue[MAX_SIZE];
int front = -1, rear = -1;

int is_empty() {
    return (front == -1 && rear == -1);
}
int is_full() {
    return ((rear + 1) % MAX_SIZE == front);
}
void write_queue(int data) {
    if (is_full()) {
        front = (front + 1) % MAX_SIZE;
    } else if (is_empty()) 
{
        front = 0;
        rear = 0;
    }
 else {
        rear = (rear + 1) % MAX_SIZE;
    }
    circular_queue[rear] = data;
}
int read_queue() {
    int data;
    if (is_empty()) {
        printf("Queue is empty.\n");
        return -1; // Return -1 to indicate an error
    } else if (front == rear) {
        data = circular_queue[front];
        front = -1;
        rear = -1;
    } else
 {
        data = circular_queue[front];
        front = (front + 1) % MAX_SIZE;
    }
    return data;
}
void clear_queue() {
    front = -1;
    rear = -1;
}
int main() {
    write_queue(10);
    write_queue(20);
    write_queue(30);
    write_queue(40);
    write_queue(50);
        printf("Deleted element: %d\n", read_queue());
    write_queue(60);

    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    clear_queue();

    return 0;
}
#include <stdio.h>
#define MAX_SIZE 5
int circular_queue[MAX_SIZE];
int front = -1, rear = -1;

int is_empty() {
    return (front == -1 && rear == -1);
}
int is_full() {
    return ((rear + 1) % MAX_SIZE == front);
}
void write_queue(int data) {
    if (is_full()) {
        front = (front + 1) % MAX_SIZE;
    } else if (is_empty()) 
{
        front = 0;
        rear = 0;
    }
 else {
        rear = (rear + 1) % MAX_SIZE;
    }
    circular_queue[rear] = data;
}
int read_queue() {
    int data;
    if (is_empty()) {
        printf("Queue is empty.\n");
        return -1; // Return -1 to indicate an error
    } else if (front == rear) {
        data = circular_queue[front];
        front = -1;
        rear = -1;
    } else
 {
        data = circular_queue[front];
        front = (front + 1) % MAX_SIZE;
    }
    return data;
}
void clear_queue() {
    front = -1;
    rear = -1;
}
int main() {
    write_queue(10);
    write_queue(20);
    write_queue(30);
    write_queue(40);
    write_queue(50);
        printf("Deleted element: %d\n", read_queue());
    write_queue(60);

    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    clear_queue();

    return 0;
}
#include <stdio.h>
#define MAX_SIZE 5
int circular_queue[MAX_SIZE];
int front = -1, rear = -1;

int is_empty() {
    return (front == -1 && rear == -1);
}
int is_full() {
    return ((rear + 1) % MAX_SIZE == front);
}
void write_queue(int data) {
    if (is_full()) {
        front = (front + 1) % MAX_SIZE;
    } else if (is_empty()) 
{
        front = 0;
        rear = 0;
    }
 else {
        rear = (rear + 1) % MAX_SIZE;
    }
    circular_queue[rear] = data;
}
int read_queue() {
    int data;
    if (is_empty()) {
        printf("Queue is empty.\n");
        return -1; 
    } else if (front == rear) {
        data = circular_queue[front];
        front = -1;
        rear = -1;
    } else
 {
        data = circular_queue[front];
        front = (front + 1) % MAX_SIZE;
    }
    return data;
}
void clear_queue() {
    front = -1;
    rear = -1;
}
int main() {
    write_queue(10);
    write_queue(20);
    write_queue(30);
    write_queue(40);
    write_queue(50);
        printf("Deleted element: %d\n", read_queue());
    write_queue(60);

    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    printf("Deleted element: %d\n", read_queue());
    clear_queue();

    return 0;
}
