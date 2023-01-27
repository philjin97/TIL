## 코딩 테스트 정복을 위한 데이터 구조와 알고리즘 
#### Array, Linked List, Hash 
#### Stack, Queue 
#### Priority Queue, Heap, Tree, Graph 
# => 왜 만들어졌고, 언제 써야 하는지 알기 위해 
<br/>

## Stack
#### 데이터를 한쪽에서만 넣고 빼는 자료구조 
#### 가장 마지막에 들어온 데이터가 가장 먼저 나감
#### *push* 삽입 - *pop* 가져오기 
#### 언제: 이전 작업의 기억 (ex. ctrl+z)
#### 파이썬은 List 로 간편하게 사용
<br/>

## Queue
#### 한쪽 끝에서 데이터를 넣고, 다른 한쪽에서만 데이터를 뺼 수 있는 자료구조
#### 가장 먼저 들어온 데이터가 가장 먼저 나감
#### 언제: 순서와 대기 
#### List - *pop(0)* 가장 오래된 데이터 - *append()* 가장 최신의 데이터
<br/>

## *queue? deque?*
#### *from collections import deque*
#### *from queue import Queue*
#### **속도** 

#### 올바른 괄호 문자열인지 판단 - using stack
'''
 string = "(()())((()))"
 left_bracket = [] *왼쪽 괄호를 저장하고 제거할 스택(리스트)*

 for bracket in string: 
    if bracket == "(":
        left_bracket.append(bracket)
    if bracket == ")":
        if len(left_bracket) == 0:
            print("올바른 문자열이 아닙니다")
        else:
            left_bracket.pop()
 if len(left_bracket) > 0:
    print('올바른 괄호 문자열이 아닙니다')
 else:
    left_bracket.pop()
        pass
'''
##### for-else => for 반복문이 break로 끝나지 않으면 else 벌럭을 실행. for 반복문이 정상적으로 순회했다면 else 블럭 실행 X. 