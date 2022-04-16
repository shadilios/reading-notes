[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)

# Linked List

![Image](https://www.alphacodingskills.com/imgfiles/linked-list.PNG)

<br><hr><br>

### What is an Interface?
It's something like a class, but completley different.
A building look that's used like a mold to shape our classes, but never contain Function details or variables.
Only declerations are allowed.


<br><hr><br>

### Big O:

A way to measure the time performance while taking into consideration worst case scenario.
Example: If we loop through each element of an array, then the worst case scenario will be O(n) where N is the number of elements inside the array.



### Terminology:

* Node: A single element inside our linked list that holds our data, think of it as an element inside the array that holds a string or an integer.
* Singly Linked List: Singly means how many references each node has, in a singly linked list, it only has 1 reference which points to the next Node.
* Doubly Linked List: Doubly means that each node has 2 references, first one points to the next Node & the second one points to the previous Node.
* Head: Always points to the first Node inside a List, it can be used to start our iteration from, or to check if it holds any data or not to see if our Linked list is empty or not.


<br><hr><br>


### How to Iterate a linked list?

1. We create a temporary node that aims to the head node.
2. In a while loop, as long as the next value isn't empty, we set the temporary Node to the Next Node.

Code example:
```
    Node temp = headNode;

    while (temp.next != null)
    {
        temp = temp.next;
    }

```




