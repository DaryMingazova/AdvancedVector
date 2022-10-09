An advanced vector
-----------------

Implementation of the basic functionality of the Vector class.

The **Reserve** method is designed to reserve memory in advance for vector elements when their approximate number is known.
Algorithmic complexity: O(vector size).

The **Resize** method changes the number of elements in the vector, **Reserve** changes only the amount of reserved memory.

The **PushBack** method adds a new value to the end of the vector.

The **PopBack** method destroys the last element of the vector and reduces the size of the vector by one.

**EmplaceBack** is a more efficient method to insert elements into a vector. The method must be executed in time O(1).
Similar to the **PushBack** method, the time complexity of the **EmplaceBack** is an amortized constant. The method accepts any number of arguments of any type. The method accepts its arguments by Forwarding link.

The **PushBack**, **EmplaceBack**, and **PopBack** methods add and remove an element at the end of the vector.

The RawMemory template class is responsible for storing a buffer that holds a specified number of elements, and provides access to elements by index.

