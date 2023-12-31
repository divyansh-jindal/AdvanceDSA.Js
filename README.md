One stop solution to implement algorithms and data structures in JavaScript with ease.

Data Structures : Queue, PriorityQueue, BST, DLL, LinkedList, Stack, HashMap.

Algorithms : BinarySearch, BubbleSort, CountingSort, HeapSort, InsertionSort, MergeSort, QuickSort, SelectionSort.

How to use:
```
const datastructures=require('./DataStructures');
const algorithms=require('./Algorithms');

console.log(datastructures);
console.log(algorithms);

const {Queue,PriorityQueue,BST,DLL,LinkedList,Stack,HashMap}=require('./DataStructures');
const {BinarySearch,BubbleSort,CountingSort,HeapSort,InsertionSort,MergeSort,QuickSort,SelectionSort}=require('./Algorithms');
```

Binary Search:
```
let arr=[2,7,9,3,6,8];
console.log(BinarySearch(arr,9));
```

Counting Sort:
```
let arr=[2,7,9,3,6,8];
console.log(CountingSort(arr));
```

Bubble Sort:
```
let arr=[2,7,9,3,6,8];
BubbleSort(arr);
console.log(arr);
```

Merge Sort:
```
let arr=[2,7,9,3,6,8];
MergeSort(arr,0,5);
console.log(arr);
```

Priority Queue:
```
const pq=new PriorityQueue((a,b)=>a>b);
pq.insert(10);
pq.insert(15);
pq.insert(3);

console.log(pq.get());
```
