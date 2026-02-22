Queue Implementation in C (Using Array)

This project demonstrates how to implement a Queue Data Structure in C using an array.

The program includes the following queue operations:

✅ Initialize Queue

✅ Enqueue (Insert element)

✅ Dequeue (Remove element)

✅ Get Front Element

✅ Check if Queue is Full

✅ Check if Queue is Empty

The queue follows the FIFO (First In, First Out) principle.

🧾 Program Description

The queue is implemented using:

A fixed-size array (MAX = 5)

Two integer variables:

front → points to the first element

rear → points to the last element

Elements are inserted from the rear and removed from the front.

🧠 Concepts Used

Structures in C

Arrays

Queue Data Structure

FIFO Principle

Functions

Conditional Statements

Basic Error Handling

📚 Queue Operations Explained
🔹 Initialize

Sets front = -1 and rear = -1 to indicate an empty queue.

🔹 Enqueue

Check if queue is full.

If inserting the first element, set front = 0.

Increment rear.

Insert the new element at rear.

🔹 Dequeue

Check if queue is empty.

Return the element at front.

Increment front.

🔹 Front

Returns the element at the front without removing it.

📤 Sample Output
10 enqueued to queue
20 enqueued to queue
30 enqueued to queue
Front element is 10
10 dequeued from queue
20 dequeued from queue
Front element is 30
🚀 How to Run
🔹 Compile the Program
gcc main.c -o output
🔹 Run the Program
./output

(For Windows)

output.exe
📂 Project Structure
📁 queue-using-array
 ├── main.c
 └── README.md
⚠️ Limitations

Queue size is fixed (MAX = 5).

This is a simple linear queue (not circular).

Memory is not dynamically resized.

🔧 Possible Improvements

Implement Circular Queue.

Make queue size dynamic.

Create menu-driven version.

Implement queue using linked list.

👨‍💻 Author

on
