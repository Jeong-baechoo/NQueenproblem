# 22-2 어드벤쳐디자인 중간레벨 프로젝트

## N-Queen Problem
### 개발목표
N개의 입력이 주어졌을때 N-queen 알고리즘을 설계하고 구현

## 프로젝트 설명
__개발 언어__ : JAVA 11  
자바는 대표적인 객체 지향 프로그래밍 언어로써 클래스 객체간의 관계를 보다 쉽게 표현할 수 있고, 미리 구현되어있는 라이브러리를 통해 개발시간을 단축시킬 수 있다.   
또한 GUI 프로그래밍이 자바의 FX,Swing과 같은 GUI라이브러리를 통해 조금 더 쉽게 GUI 프로그래밍이 가능할 것으로 예상되어 본 프로젝트의 구현 언어로 선택하였다.   


-체스판의 크기를 4에서 8사이로 입력 받고, 입력된 크기에 대한 여왕 문제의 해를 구한다.

-각 열에는 오직 하나의 여왕만 존재 
-각 행에는 오직 하나의 여왕만 존재 
-각 여왕의 대각선 위치에는 다른 여왕이 존재해서는 안 됨

-입력 : 체스보드의 크기를 입력(4~8 사이의 수), 체스보드의 크기는 사용자가 입력하며 4x4 ~ 8x8 크기 내에서 입력하도록 함
-출력 : 다음과 같은 양식으로 출력(4개의 여왕 문제 예)

| Row 1 - Col 2 |   | Q |   |   |
|---------------|---|---|---|---|
| Row 2 - Col 4 |   |   |   | Q |
| Row 3 - Col 1 | Q |   |   |   |
| Row 4 - Col 3 |   |   | Q |   |

## 아이디어 및 접근방법  
__스택과 백트래킹__  
문제의 해답을 검색하는 과정에서 스택과 백트래킹을 활용하여 순차적으로 해결한다.   
검색 과정에서 문제의 답이 성립되지 않을 경우 스택에 저장된 정보를 통해 뒤로 돌아가 다른 경우의 수로 문제의 해답을 다시 검색한다.







