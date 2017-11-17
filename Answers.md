1. What are the order of insertions/removals for the following data structures?
   - **Stack** Stacks abide by the last-in, first-out principle (LIFO). That is, insertions/removals can only happen from the top of the stack. The 'push' function is used to add elements into the stack, whereas the 'pop' function is used to remove elements from the stack.
   - **Queue** Queues generally abide by the first-in, first-out principle (FIFO). Enqueuing is the process of adding an element to the end of the queue, whereas dequeuing removes the first element at the front of the queue.
2. What is the retreival time complexity for the following data structures?
   - **Linked List** O(n)
   - **Hash Table** O(1)
   - **Binary Search Trees** BigO(n)
2. What are some advantages to using a Hash Tables over an array in JavaScript?
Performance: Hash tables on average perform O(1) vs. arrays' O(n) (linear in time).
Hash function: Promotes efficiency and expediency by elminating the need to iterate through a list. Constant search time is all that's needed to insert or remove an item.