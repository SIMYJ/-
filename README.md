# 자료구조란

## 자료구조 = 데이터구조 = Data structure
- 대량의 데이터를 효율적으로 관리 할 수 있는 데이터의 구조
- 코드상에서 효율적으로 데이터를 처리하기 위해, 데이터 특성에 따라 체계적으로 데이터를 구조화한다.(현실 세계의 데이터를 어떤 데이터 구조로 자료로 만드는가?)


## 효율적인 데이터 관리 예시
- 1)우편번호: 5자리 우편번호(앞3자리 시,군,자치구를 표기, 뒤 2잦리는 일련번호 구성)
       [지역을 어떤 데이터로  표현해서 저장할 것인가?]

- 2)학생관리 (대학생) : 학과, 학번, 이름
      [수 많은 학생들의 데이터를 어떻게 저장할 것인가?] 

데이터의 구조에 따라 프로그래밍의 성능 달라질수 있다. 특히 데이터의 특성에 따라 여러가지 구조가 있는데 기존에 많이 쓰였던 자료구조는 기본적으로 알고 있어야된다. 알고리즘에 많이 사용하고, 현업에서 대표적인 자료구조를 알고 있어야 성능이 있는 프로그래밍을 할수 있다.

## 대표적인 자료구조.
- 배열, 스택, 큐 ,링크드 리스트, 해쉬 테이블, 힙 등
- 자료구조는 저장되는 데이터 구조에 따라 선형구조와 비선형구조로 나뉜다.
- 선형 구조는 데이터가 일렬로 나열되어있고, 비선형 구조는 특정한 형태로 데이터가 저장된다.

![](https://i.imgur.com/VJhsdCp.png)



## 우리의 마음자세
```
처음부터 코드로 자료구조나 알고리즘을 구현하기 어렵다!
모방을 하면서 스킬을 익히자. 대표적인 자료구조(스택,큐,링크드리스트,해쉬 테이블)를 이해하면서  새로운 자료구조를 만들수 있는 역량을 키우자.
자료구조는 알고리즘에 사용되고, 기술면접에서도 나오는 내용이다.
```





# 알고리즘(algorithm)
- 어떤 문제를 풀기 위한 절차/방법
- 어떤 문제에 대하여, 특정한 입력을 넣으면, 원하는 출력을 얻을수 있도록 만드는 프로그래밍

---


# 개발 환경

## 아나콘다 
 - 가상환경을 만들어 필요한 패키지들을 설치하고, 가상환경 안에서 자기 입맛에 맞게 개발환경을 조성할 수 있다.
 - 아나콘다에서는 파이썬에서 중요 사용되는 라이브러리가 자동으로 설치 되어 있다.
 - 데이터사이언스(수학과 과학 분야)에서 사용되는 여러 패키지(넘파이,사이파이)들을 가지고 있는 종합적인 플랫폼( 패키지를 묶어 놓은 파이썬 배포판)
 - 일반적으로 아나콘다(Anaconda)를 설치하면 Jupyter Notebook이 함께 설치되어 Jupyter를 사용할 수 있다.
 

## JUpyter notebook( 쥬피터)

- 파이썬으로 프로그래밍을 할 때 사용하는 개발 환경 / 기존 파이썬의 통합 개발 환경은 명령 프롬프트, IDLE

- ‘주피터 노트북’은 오픈 소스 기반의 웹 애플리케이션으로, 파이썬을 비롯한 40여 개의 프로그래밍 언어로 코드를 작성하고 실행하는 개발 환경을 제공한다.

- 실시간으로 데이터를 조작하고 시각화 할수 있다.

- 프로그래밍 언어로 작성한 코드는 HTML, 이미지, 동영상 파일, LaTeX 등 다양한 타입으로 변환 가능하다.

- 데이터 과학분야 프로그래밍언어 지원(Python, R, Julia, Scala 등)

- 이메일, 드롭박스, 깃허브 공유가능



이미지 참조 : https://wayhome25.github.io/cs/2017/04/17/cs-18/
