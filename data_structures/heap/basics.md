1] A Heap is a complete binary tree-based data structure

2] complete binary tree is a fully binary tree till n-1 level + all the elements at the nth level are filled from left.

3] Heaps are not sorted. types of heap: min heap & max heap

4] min heap : /_\   lowest value at the root. Every node will have value less than its parents.

5] max heap : \-/   highest value at the root. Every node will have value greater than its parent.

6] Heaps are useful when highest/lowest priority element need to be removed/picked. This can be done at O(1) time. Common use is to implement priority queue.

7] Binary heaps are implemented in arrays, it saves cost of saving pointers to child nodes.

8] Heaps are not useful when we want to search other elements. it takes O(n) times since heap is not sorted.
