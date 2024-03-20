# Linked List Implementation in Python

## Overview
This Python code implements a basic linked list data structure using two classes: `Node` and `LinkedList`. The `Node` class represents each node in the linked list, while the `LinkedList` class provides methods for manipulating the list.

## Node Class
The `Node` class defines a single node in the linked list. Each node contains a value and a reference to the next node in the list.

```python
class Node:
    def __init__(self, value, next_node=None):
        self.value = value
        self.next_node = next_node
