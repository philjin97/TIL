## Heap
#### 일반적인 Queue는 **순서**를 기준으로 가장 먼저 들어온 데이터가 가장 먼저 나감. 
#### 우선순위 큐는 **우선순위**를 기준으로 가장 우선순위가 높은 데이터가 가장 먼저 나감.
#### => 우선순위 큐 구현: 배열 (Array), 연결 리스트(Linked List), 힙(heap)
<br/>

#### heapq -> 연산의 속도가 리스트보다 빠르다. 
#### 최댓값 또는 최솟값을 빠르게 찾아내도록 만든 데이터 구조. 
#### 느슨한 정렬형태. 
#### min heap -> 제일 작은 수가 자동으로 위의 노드로 감. 
#### heapq.heapify(), heapq.heappop(heap), heapq.heappush(heap, item)
<br/>

#### 최소 힙
'''
import heapq
numbers = [0, 12345678, 1, 2, 0, 0, 0, 0, 32]

heap = []

for n in numbers:
    if n != 0:
    heapq.heappush(heap,n)
else:
    if heap:
        print(heapq.heappop(heap))
    else:
        print(0)
'''



