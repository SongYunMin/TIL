## 2020.05.07
### 네트워크 세미나
**IGRP** : Interior Gateway Routing Protocol 내부 게이트웨이 라우팅 프로토콜은 시스코가사 발명한 거리 벡터 내부 게이트웨이 프로토콜임. 자율 시스템 내의 라우팅 데이터를 교환할 목적으로 라우터가 사용된다.
**AS(망식별번호) :**  동일한 라우팅 정책으로 하나의 관리자에 의하여 운영되는 네트워크, 즉 한 회사나 단체에서 관리하는 라우터 집단을 자율 시스템(AS : Autonomous System)이라 하며 각각의 자율 시스템을 식별하기 위한 인터넷 상의 고유한 숫자를 망식별번호(AS번호)라 함.

## 2020.05.10
### 희소행렬
희소행렬(sparse matrix)은 행렬의 값이 대부분 0인 경우를 가리키는 표현이다. 그와 반대되는 표현으로는 밀집행렬(dense matrix), 조밀행렬이 사용된다. 개념적으로 희소성은 시스템들이 약하게 연결된 것에 해당한다. 한 줄로 나열된 공과 공이 스프링으로 양 옆으로 하나씩 연결되었을 때 이것은 희소 시스템이다. 그와 반대로 한 줄의 공들이 여러 방향의 공들과 스프링으로 연결되었을 때 이 시스템은 밀집 행렬이 될 수 있다. 희소의 개념은 조합론과 네트워크 이론 등과 같은 응용분야에서 유용하다.

## 2020.05.20
### Data Structure
- **순환 Recursion**
- 함수 호출시 Return Address가 Ststem Stack에 저장되고 호출되는 함수를 위한 Parameter, Local variable를 Stack으로부터 할당받음
- 이러한 함수를 위한 시스템 스택에서의 공간을 활성 레코드(Activation Record)라고 한다.
- 이러한 준비가 끝나면 호출된 함수의 시작 위치로 점프하여 수행을 시작함, 만약 호출된 함수가 자기 자신이라면 자기 자신의 시작 위치로 점프하게된다. 
- 호출된 함수가 끝나게 되면 Ststem Stack에서 Return Address를 추출하여 호출한 함수로 되돌아가게 됨 

## 2020.05.30
### Data Structure
- ** Deque **
- Queue의 전단과 후단에서 모두 삽입과 삭제가 가능한 큐를 의미
- 중간 삽입 삭제는 불가
### Deque ADT
- Object : n개의 element형 요소들의 순서 있는 모임
- Operation : 
- create () :: = Deque 생성
- init (dp) :: = Deque 초기화
- is_empty(dq) :: = 공백 상태인지 검사
- is_full(dp) :: = 포화 상태인지 검사
- add_front(dp, item) :: = Deque의 앞에 요소 추가
- add_rear(dq, item) :: = Deque의 뒤에 요소 추가
- delete_front :: = Deque의 앞에있는 요소를 반환한 뒤 삭제함
- delete_rear :: = Deque의 뒤에있는 요소를 반환한 뒤 삭제함
- get_front :: = Deque의 앞에서 삭제하지 않고 앞에 있는 요소 반환
- get_rear :: = Deque의 뒤에서 삭제하지 않고 뒤에 있는 요소 반환
