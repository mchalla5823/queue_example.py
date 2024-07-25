# queue_example.py
import queue

   # Create a Queue object
   my_queue = queue.Queue()

   # Add an element to the queue
   my_queue.put(5)

   # Pop an element from the queue
   popped_element = my_queue.get()

   # Show the output
   print("Popped element:", popped_element)
