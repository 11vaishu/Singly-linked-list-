# Singly-linked-list-
Insertion at the beginning, end, and specific positions.  Deletion from the beginning, end, and specific positions
# Singly Linked List in Java

This project demonstrates the basic implementation of a **Singly Linked List (SLL)** in Java. It includes standard operations such as insertion, deletion, and display.

## Features

- Insert at the beginning
- Insert at the end
- Insert at a specific position
- Delete from the beginning
- Delete from the end
- Display the linked list

## Code Structure

### `Node` Class
A helper class that represents a single node in the linked list, containing:
- An integer `value`
- A reference to the next node (`next`)

### `SLL` Class
Contains the head of the linked list and methods to manipulate the list.

#### Methods:
- `InsertAtBeginning(int value)` – Adds a new node at the beginning
- `InsertAtEnd(int value)` – Adds a new node at the end
- `insertAtSpecificPosition(int value, int position)` – Inserts a node at a given position
- `deleteatbeg()` – Deletes the first node
- `deleteatend()` – Deletes the last node
- `display()` – Prints the linked list

## Sample Output
If you run the `main` method, it will:

- Create a linked list
- Perform a few insertions and deletions
- Display the final linked list

