# Linked Lists
notes taken from CF article
### A linked list is a series of Nodes that are linked to each other.  Each one references the next Node in the link.

## Terminology:
- Linked List - A data structure that contains nodes that links/points to the next node in the list.  
- Singly - Singly refers to the number of references that node has.  A *Singly* linked list means that there is only on reference, and the reference points to the Next node in a linked list.
- Doubly- *Doubly* refers to there being two (double) references within the node.  A *Doubly* linked list means that there is a reference to both the Next and previous node.  
- Node - Nodes are the individual items/links that live in a linked list.  Each node contains the data for each link.  
- Next - Each node contains a property called *Next*. This property contains the reference to the next node.  
- Head - The *Head* is a reference type of type Node to the first node in a linked list.  
- Current - The *Current* reference is a reference type of type Node that is currently being looked at.  This node is traditionally used when traversing through a full linked list. When traversing, you typically reset the current to the head to guarantee you are starting from the beginning of the linked list.  

### Linked Lists can not be traversed with a for-each or for loop.  Instead we depend on the *Next* value in each node.  

## Big O
### The Big O is O(n) because we may have to check all the nodes before we find the one we are looking for.  'n' represents the number of Nodes in the list. 

### The Big O for space is O(1) because there is no additional space being used than what is already given to us with the linked list input.  