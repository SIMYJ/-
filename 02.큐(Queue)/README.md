# 1. 큐(Queue)
- 가장 먼저 넣은 데이터를 가정 먼저 꺼낼 수 있는 구조
- FIFO(First-in, First-out) 또는 LILO(Last-in, Last-Out)방식
- 스택과 꺼내는 순서가 반대

# 2. 큐 용어
```
- 인큐(Enqueue) : 큐에 데이터를 넣는 기능
- 데큐(Dequeue) : 큐에서 데이터를 꺼내는 기능
- Head(Font)   : 데이터를 꺼내는 쪽
- Tail(Rear)   : 데이터를 넣은 쪽
```
큐 시연해보기 : https://visualgo.net/en/list

### 인큐(Enqueue)
![](https://i.imgur.com/aU7j4JC.gif)

### 데큐(Dequeue)

![](https://i.imgur.com/JybLETU.gif)

# 3. 파이썬 구현
- 다양한 종류의 큐 : Queue(), LifoQueue(), PriorityQueue()
- Queue() : 가장 일반적인 자료구조 큐    

![](https://i.imgur.com/dAg5XCD.png)
###
- LifoQueue() : 나중에 입력된 데이터가 먼저 출력되는 구조 (스택 구조와 같다.)     
![](https://i.imgur.com/26R4Tf4.png)
###
- PriorityQueue() : 데이터마다 우선순위를 넣어서, 우선순위가 높은 순으로 데이터 출력     
![](https://i.imgur.com/sqKzYZB.png)
###

## 큐는 어디에서 사용되는가?

- 운영체제에서 멀티 태스킹을 구현하기 위해서 프로세스 스케쥴링 할때 많이 사용된다. (운영체제 사용)
    - 큐의 경우 장단점보다는 큐의 활용 예로 프로세스 스케쥴링 방식을 함께 이해하는것이 좋다.


# 4. 인큐,데큐 기능 구현하기(리스트변수 사용)
- 0.2큐(Queue).ipynb파일참조
