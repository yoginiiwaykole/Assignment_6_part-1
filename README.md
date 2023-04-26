# Assignment_6 - part 1

This is a simple implementation of a stack in Java, which provides two types of stacks: a fixed size stack (implemented with an array) and a growing stack (implemented with a Vector). The stack interface provides basic operations such as push, pop, peek, isEmpty, isFull, clear, size, and display.

The fixed stack has a maximum size of 5, and will throw an error if an element is pushed onto a full stack or popped from an empty stack. The growing stack, on the other hand, does not have a maximum size, and will simply return 0 if an element is popped from an empty stack.

The Main class provides a simple recursive menu for choosing which type of stack to use and which operation to perform on the stack. Each choice in the menu corresponds to a specific method in the Fixed_stk or Growable_stk classes. The recursiveMenu() method is called after each operation is performed to return to the main menu.

Overall, this is a basic implementation of a stack in Java that can be used for simple applications. 
