1] A Heap is a complete binary tree-based data structure

2] complete binary tree is a fully binary tree till n-1 level + all the elements at the nth level are filled from left.

3] Heaps are not sorted. types of heap: min heap & max heap

4] min heap : /_\   lowest value at the root. Every node will have value less than its parents.

5] max heap : \-/   highest value at the root. Every node will have value greater than its parent.

6] Heaps are useful when highest/lowest priority element need to be removed/picked. This can be done at O(1) time. Common use is to implement priority queue.

7] Binary heaps are implemented in arrays, it saves cost of saving pointers to child nodes.

8] Heaps are not useful when we want to search other elements. it takes O(n) times since heap is not sorted.

9] Insertion will be at the bottom, means last element in the array. From there we need to heapify.
Heapify means swaping child node with the parent if the heap property not met. and Continue this process till we satisfy the condtion or reach the root(top). At worst case we need to heapify the length of the heap. O(Log(n)).

10] In case of deletion, we need to move complete heap upwards. To do this, we will take the last element and replace the root. From root will start the process of bubbling down. We compare the root with its childrens and swap with smaller child. And we continue do the bubbling down process till we attain heap property.

11] To convert a unordered array to a heap, we can use the same bubbling up process. But we need to repeat it multiple times from root till we reach the heap property.

12] 
