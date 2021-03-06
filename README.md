# DataStructure_C
## 열혈자료구조 공부한 C-code모음
---
- 컴퓨터공학 포토폴리오 김지우
- 한줄 한줄 따라 쳐가며 자료구조의 흐름을 이해하려 노력하였습니다.
- 사용한 책은 윤성우의 열혈 자료구조 책을 사용하였습니다.
- 포토폴리오 용으로 제출할거라고는 생각하지 못했어서 공부할때 주석으로 가끔 혼잣말로 궁시렁 거린것들이 있는대 가볍게 읽어주시면 감사하겠습니다 ㅎㅎ
---
### Chapter 01. 자료구조와 알고리즘의 이해

### Chapter 02. 재귀(Recursion)

### Chapter 03. 연결 리스트(Linked List) 1

** 배열을 이용한 리스트의 구현 **
- ArrayList.c
- ArrayList.h
- ArrayListMain.c

### Chapter 04. 연결 리스트(Linked List) 2

** 노드를 이용한 리스트의 구현 **
- DLinkedList.h
- DLinkedList.c
- DLinkedListMain.c

### Chapter 05. 연결 리스트(Linked List) 3

** 원형 연결 리스트 **
- CLinkedList.h
- CLinkedList.c
- CLinkedListMain.c

** 양방향 연결 리스트 **
- DBLinkedList.h
- DBLinkedList.c

### Chapter 06. 스택(Stack)

** 스택의 배열 기반 구현 **
- ArrayBaseStack.h
- ArrayBaseStack.c
- ArrayBaseStackMain.c

** 스택의 연결 리스트 기반 구현 **
** 계산기 프로그램 **
- ListBaseStack.h
- ListBaseStack.c
- ListBaseStackMain.c

### Chapter 07. 큐(Queue)

** 큐의 배열 기반 구현 **
- CircularQueue.h
- CircularQueue.c
- CircularQueueMain.c

** 큐의 연결 리스트 기반 구현 **
- ListBaseQueue.h
- ListBaseQueue.c
- ListBaseQueueMain.c

** 덱(Deque) **
- Deque.c
- Deque.h
- DequeMain.c

### Chapter 08. 트리(Tree)

** 이진 트리 **
- BinaryTree.c
- BinaryTree.h
- BinaryTreeMain.c

** 수식 트리 **
- ExpressionTree.h
- ExpressionTree.c
- ExpressionTreeMain.c

### Chapter 09. 우선순위 큐(Pririty Queue)와 힙(Heap)

** 힙 **
- SimpleHeap.h
- SimpleHeap.c
- SimpleHeapMain.c
- UsefulHeap.h
- UsefulHeap.c
- UsefulHeapMain.c

** 우선순위 큐 **
- PriorityQueue.h
- PriorityQueue.c
- PriorityQueueMain.c

### Chapter 10. 정렬(Sorting)

** 단순한 정렬 알고리즘 **
- 버블 정렬: BubbleSort.c
- 선택 정렬: SelectionSort.c
- 삽입 정렬: InsertionSort.c

** 복잡하지만 효율적인 정렬 알고리즘 **
- 힙 정렬: HeapSort.c
- 퀵 정렬: QuickSort.c
- 기수 정렬: RadixSort.c

### Chapter 11. 탐색(Search) 1

** 이진 탐색(Binary Search) **
- RecursiveBinarySearch.c

** 보간 탐색(Interpolation Search) **
- InterpolSearch.c

** 이진 탐색 트리 **
- BinaryTree2.h
- BinaryTree2.c
- BinarySearchTree.h
- BinarySearchTree.c
- BinarySearchTreeMain.c

### Chapter 12. 탐색(Search) 2

** AVL 트리 **
- BinaryTree2.h
- BinaryTree2.c
- BinarySearchTree3.h
- BinarySearchTree3.c
- AVLRebalance.h
- AVLRebalance.c
- AVLTreeMain.c

### Chapter 13. 테이블(Table)과 해쉬(Hash)

** 배열을 이용한 Table의 이해 **
- UnderstandTable.c

** 어느 정도 갖춰진 테이블과 해쉬 **
- Person.h
- Person.c
- Slot.h
- Table.h
- Table.c
- SimpleHashMain.c

** 충돌 문제의 해결을 위한 체이닝(Chaining)의 구현 **
- DLinkedList.h
- DLinkedList.c
- Person.h
- Person.c
- Slot2.h
- Table2.h
- Table2.h
- ChainedTableMain.c

### Chapter 13. 그래프(Graph)

** 인접 리스트 기반의 그래프 **
- DLinkedList.h
- DLinkedList.c
- ALGraph.h
- ALGraph.c
- ALGraphMain.c

** 깊이 우선 탐색(DFS) **
- DLinkedList.h
- DLinkedList.c
- ArrayBaseStack.h
- ArrayBaseStack.c
- ALGraphDFS.h
- ALGraphDFS.c
- DFSMain.c

** 너비 우선 탐색(BFS) **
- DLinkedList.h
- DLinkedList.c
- CircularQueue.h
- CircularQueue.c
- ALGraphBFS.h
- ALGraphBFS.c
- BFSMain.c

** 크루스칼 알고리즘 **
 
