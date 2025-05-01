The Comparison of structure between two Languages(c++ & python) are given below:
 1.Fixed Dynamic
C++: We create an array with a known size at runtime using int arr[size];. It's fixed once declared. Memory is typically allocated on the stack but decided during runtime.
Python: We use a list like arr = [0] * size to allocate a fixed-length array. It’s easy and flexible.

2.Stack Dynamic
C++: The array is declared inside a function like int arr[5];, and memory is automatically managed by the stack.
Python: Lists are always on the heap, but when defined inside a function, we can simulate stack-like behavior.

3.Fixed Heap Dynamic
C++: We allocate memory on the heap using malloc and later free it using free().
Python: We use the array module to create fixed-size arrays stored in heap memory. Python handles memory cleanup for us.

4.Heap Dynamic
C++: We use vector<int> which can grow and shrink at runtime. It's a flexible dynamic array.
Python: The built-in list type works the same way—easy to grow using append().
