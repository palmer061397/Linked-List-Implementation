# Linked List Implementation in Python

## Overview
This Python code implements a basic linked list data structure using two classes: `Node` and `LinkedList`. The `Node` class represents each node in the linked list, while the `LinkedList` class provides methods for manipulating the list.

## Node Class
The `Node` class defines a single node in the linked list. Each node contains a value and a reference to the next node in the list.

## LinkedList Class
The `LinkedList` class represents the linked list itself. It has a head node, which points to the first node in the list.

## Methods
* `insert_beginning(new_value)`: Inserts a new node with the given value at the beginning of the list.
* `stringify_list()`: Converts the linked list into a string representation.

## Usage
1. Create a new instance of the `LinkedList` class.
2. Use the `insert_beginning` method to add elements to the beginning of the list.
3. Use the `stringify_list` method to print the elements of the list.

## Example
```python
ll = LinkedList(5)
ll.insert_beginning(70)
ll.insert_beginning(5675)
ll.insert_beginning(90)
print(ll.stringify_list())
```
