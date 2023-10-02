# algorithm_js

https://code.plus/course/41

백준 node.js로 푸는 곳

# 10/2

### 2164 카드 2

1. 일반적인 push, shift로 풀면 시간 초과가 난다. 앞에 것을 뺴주면 모든 배열이 움직여야하기 때문이다.
2. BFS를 이해하기 전에 큐 문제를 푸는데 더 연습이 필요할 것 같다.
3. class를 활용하여 push, shift를 하지않고 각 객체에 다음 값과 이전 값을 저장하는 식으로 풀어야한다. 그리고 이 것을 LinkedList라고 부른다.

# 9/27

### 2309 일곱 난쟁이

1. 브루트 포스 문제에 어려움을 겪어서 쉬운 문제를 좀 풀었다.
2. 경우의 수를 만들기 위해 순열, 재귀, 비트마스크 방법을 알아보고, 여러가지 문제를 해결해봅니다. 라고하는데 순열에 가까운 것 같다. 재귀에 익숙해지는 게 관건이라고 생각한다. 이 파트는 좀 반복을 많이 해야할 듯

# 9/26 

### 15649 N 과 M (1)

1. 잘 모르겠음....
2. 이해도 안됨;
3. 다시 풀어야 함.

# 9/25

### 1654 랜선 자르기

1. 로직을 똑같이 작성했는데 하나는 맞고 하나는 틀리다고 한다.
2. 이유 확인 후 작성할 것

# 9/23

### 2156 포도주 시식

1. 실버 1 문제까지 풀어서 DP에 대한 자신감 상승
2. 다음 알고리즘으로 넘어야가야할 차례

### 17413 단어 뒤집기 2

1. 정규식을 알면 쉽게 풀이 가능
2. 스택이라는 말에 휩쓸려서 스택으로 풀려했지만 그렇게 풀면 산으로 간다.
3. reverse()라는 메소드가 있다.

# 9/22

### 1158 요세푸스 문제

1. 배열 함수에 대해서 잘 알고 있다고 생각했는데 풀지 못했다.
2. shift() 맨 앞의 원소 삭제 후 반환값으로 줌
3. 출력 어떤 양식인지 확인!
4. `let arr = [...new Array(parseInt(n))].map((_, i) => i + 1)` \_는 기존 있는 원소를 무시하고 i + 1로 넣음. 이게 for 문보다 빠를 줄 알았는데 아니었다.

### 11052 카드 구매하기

1. 푸는 방법을 거의 찾았다. dp 문제임을 알고 점화식을 써야한다는 것이 매우 중요하다.
2. 끝에 조건을 잡는 부분에서 헤맸다. 그냥 한 묶음으로 사는건 이전 원소에 없기 때문에 따로 추가 해야 한다.
3. min, max도 잘 기억해둘 것.
4. unshift를 쓰고 콘솔을 찍으면 원소가 추가된 후에 배열의 길이를 반환하기 때문에 바뀐 배열의 모습을 보고 싶다면 따로 콘솔을 찍어줘야한다.

# 9/20

### 2512 예산

1. 이진 탐색 문제를 처음 풀었는데 잘 이해가 않았다.
2. 어떤 느낌인지는 알겠으나 답을 보고도 이해가 잘 안되었다. 케이스가 잘 안떠오름.
3. 다시 풀어야함.

# 9/19

### 11726 2xn 타일링

1. dp에 대해 이해 중
2. 규칙을 찾고 점화식을 세우는 것이 우선 순위
3. 답보고 이해함

### 11727 2xn 타일링 2

1. 어차피 점화식이라서 규칙을 파악하는게 중요하고 그 이전에 dp 문제임을 파악해야한다.

# 9/18

### 1748 수 이어 쓰기 1

1. 맨 처음에는 배열로 만들어서 길이를 반복문을 통해서 더해주는 방식으로 했다가
   string도 길이를 잴 수 있으니 이 걸로 했는데 여전히 시간 초과...
   그래서 반복문 사용을 줄여야겠다고 생각했고 공식이 있겠거니 생각했다.
   찾아보면 수학 공식이 있겠지만 그냥 쳐보면서 패턴을 익히고 한 번에 계산하는 함수를 작성해서
   통과하였다.
2. 숫자는 split 함수를 쓸 수 없다.

### 1463 1로 만들기

1. 답을 보고 이해했음
2. dp의 아주 기초적인 문제같아 이를 기반으로 심화 문제를 접근해야될 것 같다.
3. 인덱스 0에 인자가 필요하면 직접 넣어주면 됨

# 9/16

### 10799 쇠파이프

1. 문제를 보고 겁이 났는데 이해하고 찾으니 생각 외로 쉬웠다.
2. 스택 문제는 비슷비슷한 것 같다.
3. 더 이상 스택 문제는 안 풀어도 될듯...
4. 자료 구조 문제는 규칙을 찾으려고 노력하자.

###

# 9/14

### 1493 박스 채우기

1. 문제를 어떻게 접근해야할지는 알겠는데 구현을 못함;
2. 풀듯말듯 못 풀겠음.
3. 못풀었음

### 11509 회문

1. 문제를 어떻게 접근해야할지는 알겠는데 구현을 못함;
2. 답을 보면 알겠는데 안봤음.
3. 못풀었음

# 9/13

### 9009 피보나치

1. 어찌저찌 구현은 했지만 틀림.
2. 다시 풀어야함
3. 맞왜틀....

### 19939 박 터뜨리기

1. 케이스를 잘 나눠서 첫 시도에 성공
2. 팩토리얼 함수를 만든 것도 긍정적

# 9/12

### 11509 풍선 맞추기

1. 패캠 답안도 통과를 못함
2. 어려운 코드는 아닌데 로직이 이해가 안감
3. 맨 위에부터 없애면서 하면 될 것 같은데... 일단 다시 풀어봐야함

# 9/8

### 1931 회의실 배정

1. =와 == 좀 구별하자...!
2. 못풀었음.
3. 왜 시작하는 시간을 신경써야하는지 모르겠음; 어렴풋하게 알 것 같음;

# 9/7

### 13305 주유소

1. cost[i] = Math.min(cost[i], minCost) 이게 안되었다. 한 번 변수에 담아서 다시 넣어야했음.
2. 문제 풀이법은 찾았으나 구현을 어떻게 해야하는지 몰랐음.
3. 새로운 문제 스킬을 알았음. min의 활용.
4. BigInt를 배웠음.
5. 못풀고 답을 봤음 -> 나중에 다시 풀어야함.

# 9/6

### 1789 수들의 합

1. 조금만 더 차분하게 문제를 살펴보자. 충분히 풀 수 있다.

# 9/5

### 1541 잃어버린 괄호

1. reduce 함수에 대해 정확히 알아야겠다.
2. 예전에는 손도 못대던 문제를 이해해서 다행이다.

### 2839 설탕 배달

1. 예전에는 왜 못 풀었을까 의문이 드는 문제.
2. 등호를 안써줘서 계속 실패했는데 세심하게 문제를 살펴야겠다.

---

# 9/4

### 1427 소트인사이드

1. 쉬운 문제였는데 에러가 나서보니 백준에서 string뒤에 trim을 붙여야하는 경우가 있다고 한다. 근데, 출력 결과에서 개행이 있다면 \n가 있을텐데 그 원소가 없어서 뭐지 싶었다.

### 10814 나이순 정렬

1. 오랜만에 풀어서 기억을 되살리기 좋았다.

---

# 8/20

### 1181 단어 정렬

1. sort 함수를 완벽하게 사용하기 위해서는 compare를 잘 활용해야한다.
2. set 생성자 함수를 잘 활용하자.

### 18870 좌표 압축

1. new Map 생성자 함수 뿐만 아니라 생성자 함수에 대해 다시 공부할 필요성을 느꼈다.
2. 여기에 사용되는 set, get도 공부가 필요하다.
3. 제일 중요한 것은 시간복잡도에 대한 개념을 다시 세울 필요성이 크다.

---

# 8/19

### 11651 좌표 정렬하기 2

1. y축 정렬이라 이전 문제와 같았다.

---

# 8/18

### 11650 좌표 정렬하기

1. 왜 코테를 js로 안푸는지 느낄 수 있었다.
2. function을 만들어 sort 변수로 넣는 것은 생각하지 못했다. 꼭 기억해야한다.
3. 엘리스트랙 입학 테스트 문제였는데 그 때는 맞추고 지금은 못 풀었다.

---

# 8/14

### 11047 동전 0

1. 나누고 몫을 더하면 되었는데 코드로 어떻게 구현해야할지 헤맸다.

---

# 7/31

### 11399번 ATM

놓친 부분

1. 문자열 sort

-만약 1, 2, 3, 1000 이라면?

---

# 8/2

### 27961번 고양이는 많을수록 좋다

놓친 부분

1. 빠진 케이스는 없는지 살펴야한다.

-만약 고양이 0마리 원한다면?

---

# 8/6

### 5073번 삼각형과 세 변

1. 구구절절 조건을 다 써주었는데 이게 맞는지 싶다.

---

# 8/13

### 2757 세수정렬

1. sort 함수를 잘 사용하자!

### 2750 수 정렬하기

1. slice 배열 함수를 기억할 것!

- slice(1, 2) 인덱스는 값 앞에서 잘린다.

### 2751 수 정렬하기 2

1. console.log 시간초과를 일으킨다. 문자열도 따로 만들어줘서 콘솔을 한 번 찍도록 만든다.

### 11004 K번째 수

1. 코드를 너무 난잡하게 썼다. 그렇다보니 어디가 잘못되었는지 못 찾았고 깔끔한 코드의 중요성을 깨달았다. 두 줄로 길게 입력값이 있을 경우 어떻게 처리해야하는지 배웠다.
