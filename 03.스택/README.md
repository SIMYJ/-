# 1. 스택(Stack)
- 가장 나중에 쌓은 데이터를 가장 먼저 빼낼 수 있는 데이터 구조
- LIFO(Last In, Fisrt Out) 또는 FILO(First In, Last Out)방식
- 큐(Queue)와 꺼내는 순서가 반대
- 메모리 안 데이터들을 효율적으로 다루기 위해 만드어진 데이터 참조 방식


# 2. 스택 용어
```
- push : 데이터를 스택에 넣기
- pop  : 데이터를 스택에서 꺼내기
- peek : 스택의 top에 있는 원소 반환

```
스택 시연해보기 : https://visualgo.net/en/list

## 푸시(push),팝(pop) 동작
<img src = "https://i.imgur.com/D02ySLP.gif" width="500px">




# 3. 스택는 어디에서 사용되는가?
- 프로세스 스택
- 재귀 함수
- 웹 브라우저 방문기록 (뒤로가기)
- 실행 취소 (undo)
- 수식의 괄호 검사 (연산자 우선순위 표현을 위한 괄호 검사)
- 후위 표기법 계산
- 깊이 우선 탐색(DFS,Depth first Search)


## 스택 구조와 프로세스 스택
- 스택 구조는 프로세스 실행 구조의 가장 기본
- 함수 호출시 프로세스 실행 구조를 스택과 비교해서 이해 필요
```python
#재귀 함수
def recursive(data):
    if data < 0:
        print ("ended")
    else:
        print(data)
        recursive(data - 1)
        print("returned", data) 
recursive(4)
```
```python
#출력
4
3
2
1
0
ended
returned 0
returned 1
returned 2
returned 3
returned 4
```

<img src = "https://i.imgur.com/dZzTXK2.png" width="700px">

## 4. 자료 구조 스택의 장단점
- 장점
  - 구조가 단순해서, 구현이 쉽다.
  - 데이터 저장/읽기 속도가 빠르다.
- 단점 (일반적인 스택 구현시) 
  - 데이터 최대 갯수를 미리 정해야 한다. 
    - 파이썬의 경우 재귀 함수는 1000번까지만 호출이 가능함
  - 저장 공간의 낭비가 발생할 수 있음
    - 미리 최대 갯수만큼 저장 공간을 확보해야 함


# 5. 스택 메서드 구현하기(리스트변수 사용)
- [0.2큐(Queue).ipynb파일참조](.ipynb)

       
   
    
참조사이트    
: https://www.faceprep.in/data-structures/stack-basic-operations/    
: https://gmlwjd9405.github.io/2018/08/03/data-structure-html.stack
  
