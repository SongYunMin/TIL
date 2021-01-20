# 2020년 2월

## 2020.2.1
### 모바일 티켓팅 서비스
- 데이터 베이스에 있는 파일을 android app 으로 전송시키기 위해선, JSON을 사용하는 방법을 생각 할 수 있음.<br>
- JSON(JavaScript Object Notation)은 사람이 읽을 수 있는 텍스트를 사용하여 데이터를 전달할 수 있도록 해주는 개방형 표준 포맷.<br>

## 2020.2.2
### 모바일 티켓팅 서비스
- AsyncTask 의 정확한 이해 필요<br>
- C# 관리프로그램의 필요성? phpMyAdmin 으로 TIcket Value 등을 충분히 관리 할 수있음.<br>
- Code Level에서 존재하는 비효율 성을 제거하는 습관이 필요<br>

## 2020.2.3
### 모바일 티켓팅 서비스
- AsyncTask란? 하나의 Class에서 UI작업을 쉽게 할 수 있게 해주는 메소드<br>
- 1. execute() 명령어를 통해 AsyncTask를 실행<br>
- 2. AsyncTask로 백그라운드 작업을 실행하기 전에 onPreExcuted()가 실행된다, 이 부분에는 이미지 로딩 작업이라면 로딩중 이미지를 띄워 놓기 등, 스레드 작업 이전에 수행할 동작을 구현함<br>
- 3. 새로 만든 스레드에서 백그라운드 작업을 수행, execute()메소드를 호출할 때 사용된 Parameter를 전달 받음<br>
- 4. doInBackground() 에서 중간 중간 진행 상태를 UI에 업데이트 하도록 하려면 publishProgress()메소드를 호출한다.<br>
- 5. onProgressUpdate() 메소드는 publishProgress()가 호출 될 때마다 자동으로 호출 됨<br>
- 6. doInBackground() 메소드에서 작업이 끝나면 onPostExcured()로 결과 Parameter를 Return 하면서 그 Return 값을 통해 스레드 작업이 끝났을 때의 동작을 구현함.<br>
- **여기서 핵심은 onPreExecute(), onProgressUpdate(), onPostExecure() 메소드는 메인 스레드에서 실행 되므로 UI 객체에 자유롭게 접근할 수 있다는 것**<br>
- 헷갈리는 부분은 AsyncTask Generic Type. AsyncTask<Params, Progress, Result> 에서, 인자1,인자2,인자3에 들어갈 값이 무엇이고 어디에 쓰인다는 지 헷갈리는 부분이 있었는데, 방법은 아래와 같음.<br>
- Params : doInBackground Parameter Type이 되며, execute Method 인자 값이 됨.<br>
- Progress : doInBackground 작업 시, 진행 단위의 타입으로 onProgressUpdate Parameter Type임<br>
- Result : doInBeckground Return Value로, onPostExecure Parameter Type임<br>

## 2020.2.5
### 모바일 티켓팅 서비스
#### Android Studio - ArrayList
1. ListView에 넣어줄 초기화 된 DataType을 만듬<br>
2. 초기화 된 Data를 가지고 Adapter를 거쳐 ListView각 Position에 뿌려준다.<br>
3. Adapter는 ListView에 Data를 넣어주는 **중개역할을 해줌**<br>
- SimpleAdapter = 간단하게 ListView에 Data를 넣어주며, 확장이 다소 적음<br>
- CustomAdapter = Data를 넣어주는 방식을 원하는대로 설정 가능, 확장성이 높음<br>
- CustomAdapter 사용을 권장함, SimpleAdapter는 추후에 스크롤간 데이터가 섞이는 현상 발생할 수 있음<br>

## 2020.2.7
### 모바일 티켓팅 서비스
1. SimpleAdapter 는 ListView 를 Custom 해서 사용할 수 없음 -> 즉, Data의 Type을 여러가지 사용할 수 없음,(img,Text,Button)<br>
2. View의 Data는 Holder를 이용해서 따로 관리하는게 편리 함.<br>
3. Adapter 도 마찬가지로, class화 하여 따로 관리하는게 운영상 편리한 부분이 있음, Activity Class에 전부 코드를 작성하면 불편함.

## 2020.2.8
### 정수론
#### 페르마의 소정리
- 페르마의 정리는 다음의 상태를 가진다 : 만약 p가 소수라면 a 는 p 에 의해 나누어지지 않는 양의 정수 이때,<br>
- **a^p-1 ≡ (mod p) 가 성립**<br>
- **증명**<br>
- P:{1,2 ... p-1} 보다 작은 양의 정수의 집합과 a mod p 에 의해 각 원소에 곱해진다면,<br>
집합 X = {a mod p, 2a mod p, ... (p-1)mod p}를 구할 수 있음<br>
- p는 a로 나눠지지 않기 때문에 X의 원소는 0과 같다<br>
- ja ≡ ka(mod p) 에서 1 <= j < k <= p-1을 가정.<br>
- 등식의 양쪽에 a를 제거하면 j ≡ k(mod p)를 얻을 수 있음<br>
#### 페르마 정리의 다른 형태
- 만약 p가 소수이고 a가 양의 정수라면 그때,<br>
- **a^p ≡ a (mod p) 가 성립**<br>
- **a와 p는 서로 소임이 요구 됨**

## 2020.2.16
### 모바일 티켓팅 

## 2020.2.17
### 모버일 티켓팅 서비스

## 2020.2.21
### Micro Service Architecture (MSA)
#### MSA 특징
- 자체 Process에서 실행<br>
- HTTP 기반 API와 통신함<br>
- 비지니스 기능을 중심으로 구축<br>
- 완전 자동화된 배포 머신을 통해 독립배포<br>
- 집중식 관리는 최소화<br>
- 다른 Language로 개발 될 수 있음<br>
- 다른 Data 저장기술을 사용할 수 있음<br>
#### MSA 적용시 장점
- 장애격리와 복구가 쉬움 (분산형 Service 이기 때문)<br>
- 비용 효율적으로 증설 가능 (하나의 Micro Service만 증설하면 되기 때문)<br>
- 서비스 개선 속도증가, 빠른 배포가 가능하다<br>
- 생산성 향상, Code수가 적어서 쉽게 수정 가능<br>
- 신기술 도임이 쉬움 (서비스가 작기 때문에)<br>
- Polyglot 적용 가능 (서비스에 최적화된 개발 언어와 DB를 선택하기 쉽다)<br>
#### MSA 도입시 고려해야 할 것
- 빠르고 잦은 배포를 필요로 하는가?<br>
- 성능에 민감한 서비스인가?<br>
- 분산 트랜잭션이 있는 서비스인가?<br>
- 데이터의 중복성을 허용 해야 함<br>
- 배포 및 릴리즈를 자동화 해야함 자동화 되지 않으면 운영에 큰 부담이 발생<br>
- MSA 서비스에 맞는 팀이 운영되어야 함 (서비스 단위 팀 같은것들)<br>
