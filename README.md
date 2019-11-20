# stack_test

## This branch
This branch is to:
- develop a test script that tests all the stack functions/methodes
    - Regardless what the programming language of the stack_class/functions
- Measure the time the functions/methodes take

## Normal stack class
A stack class/functions should contain:
- Constructor
    - Allocate memory
    - Initialize atributes
- is_empty
    - Return wheter the stack is empty
- push
    - Push an item on top of the stack
- pop
    - Return and remove an item from the top of the stack
- peek
    - Return the item on top of the stack without removing it
- get_size
    - Return the number of elements in the stack


## Advanced part of stack

The advance part will inherit the normal stack class.

The advanced part will add:
- Efficient storage for seeking, pushing and popping/peeking, method overloading
- seek
    - Returns if the item was found
- seek_and_destroy
    - Returns if the item was found and removes it from the stack
