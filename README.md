# Doubly Linked List

Skills: Proteus 7, Digital Electronics, Data Structures

- I am Mehul Kumar Sahoo pursuing B.Tech in Electronics Enginerring from IIT(BHU), Varanasi.
- I have made a Digital Circuit for the traversal of a DOUBLY LINKED LIST and finding the node with minimum data value as a solution for PS1 of DIGISM an event in UDYAM'23.

## Explanation of Problem Statement

- We have been given a doubly linked list which has been stored as an array of elements in a binary file which will be stored in a ROM (IC 2732).
- Now, every node of the list has 3 parts:
    - At address X => 8-bit data.
    - At address X+1 => 5-bit address of the next node.
    - At address X+2 => 5-bit address of the previous node.
- We have been given a 5 bit starting point address of the starting node in the list through logic-states.(Not necessarily head of the list)
- If the address of the next node/previous node is 255 then it signifies the tail and head of the list respectively.

## Solution of the Problem Statement

- I have provided the following circuit as the solution for the problem.
- [The complete approach to the problem statement is given here]()

  <img width="821" alt="image" src="https://github.com/Mehul-Kumar-Sahoo/Doubly-Linked-List/assets/93527557/fe208362-b277-4bcd-9516-a99e72e33c74">
