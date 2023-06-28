# linked-lists-properties
A linked list is a data structure that consists of a sequence of nodes, where each node contains a value and a reference (or link) to the next node in the sequence. Here are descriptions of some basic operations performed on a linked list:

Insertion at the Beginning:
To insert a new node at the beginning of a linked list, you create a new node, assign the new node's value, and make its "next" pointer point to the current head node. Finally, you update the head pointer to the new node, making it the new head of the list.

Insertion at the End:
To insert a new node at the end of a linked list, you traverse the list until you reach the last node (the node whose "next" pointer is NULL). Then, you create a new node, assign the new node's value, make the "next" pointer of the last node point to the new node, and update the new node's "next" pointer to NULL.

Deletion from the Beginning:
To delete the first node of a linked list, you update the head pointer to point to the second node and deallocate the memory occupied by the original head node.

Deletion from the End:
To delete the last node of a linked list, you traverse the list until you reach the second-to-last node. Then, you update its "next" pointer to NULL and deallocate the memory occupied by the last node.

Traversal:
To access and process each node in a linked list, you start from the head node and follow the "next" pointers until you reach the end of the list. During traversal, you can perform various operations on the nodes, such as printing their values or modifying them.

Search:
To search for a specific value in a linked list, you start from the head node and compare the target value with each node's value while traversing the list. If the value is found, you can return the node or indicate its position in the list.

It's worth noting that these operations assume a singly linked list, where each node has a reference to the next node. There are also other variations, such as doubly linked lists, where each node has references to both the next and previous nodes.






