# 힙 정렬(heap_sort)  
- 최악의 경우 시간복잡도 O(logn) 밑2  
- 추가 배열 불필요  
- 이진 힙(binary heap) 자료구조를 사용  
## Heap  
- 힙은 최대값 및 최솟값을 찾아내는 연산을 빠르게 하기위해 고안된 완전이진트리(complete binary)를 기본으로한 자료구조로서 다음과 같은 힙속성을 만족한다.   
### heap property  
1. max heap property: 부모는 자식보다 크거나 같다  
2. min heap property: 부모는 자식보다 작거나 같다  
<img src="https://user-images.githubusercontent.com/41607872/84743388-d5109d80-afec-11ea-91ee-11467298b39e.PNG" width="600" height="400">

### complete binary  
![full binary tree](https://user-images.githubusercontent.com/41607872/84743412-de016f00-afec-11ea-86c4-882dd3a5d255.PNG)
