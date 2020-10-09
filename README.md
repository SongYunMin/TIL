# TIL
Today I  Learned, 매일 무엇을 배웠는지 정리하고 기록합니다.

## 규칙
- 개발자로서 꾸준한 성장을 위해 학습경험을 기록합니다.<br>
- 쓸모없는 내용은 지양하고 모든 내용은 본인이 직접 작성합니다.<br>

# 2019년 11월
## 2019.11.30
### 선후배 스터디
- 배운 내용 : 
  - Github
  - Notion
  - Slack
- 안녕하세요

# 2019년 12

## 2019.12.06
OS Term Project 다시한번 도전!!

## 2019.12.16
### 방학동안 해야할 일들
- 캡스톤 디자인
- 자료구조 Remind
- 1일 1커밋 습관화
- 알고리즘
- Wild Idea 경진대회 1등 !!<br><br>
#### 이번 방학은 꼭 알차게 보내자 ..!

## 2019.12.17
### Wild Idea 창업 경진대회 최종 발표연습
- 최종 Idea Logic 추가
- 예상 질문 연습

## 2019.12.18
### 제주도 여행 준비!

## 2019.12.23
### 블로그 이전 실패..
- 여러가지 사유가 있지만,, 우선 기존 Data를 옮기는 과정이 매우힘듬..<br>
- 일단은 그냥 기존 네이버를 사용하는 것으로..

## 2019.12.25
### Capston Desing Data Transfer Protocol Structure Redesing
- 기존 App -> Server 방식<br>
- 변경 Server -> App 방식 변경 예정<br>
- 방학 계획을 실행하려면 우선적으로 변경해야하는 부분..

## 2019.12.26
### 미팅 PPT 재설계
- 캡스톤 디자인 1,2차 발표 진도 기반으로 방학 중 구현내용 재 설계 예정<br>
- C# 을 이용한 Management Program 설계 진행 해야 

## 2019.12.28
### 캡스톤 디자인 재설계 구현시작
- 구현중이던 프로젝트 파일 새로 만들 계획
- Android Studio 사용 <br>
- C# Language 이용하여 Management Program 개발 <br>

# 2020년 1월

## 2020.1.1
### 새해가 밝았습니다!
- 새해목표 수립!!<br>
- 1 day 1 commit 목표 시작!<br>

## 2020.1.2
### 암표방지를 위한 모바일 티켓팅 시스템
- Data 전송방식 변경 구현 시작<br>
- 학회 MT 장소조사 시작

## 2020.1.3
### 캡스톤 디자인
- Code의 원하는 부분을 변경을 해야한다. 하지만 Class를 제대로 설계 못했는지, 어떠한 부분에서 많은 점들을 변경해야만 했다.<br>
하지만 캡스톤 디자인 프로젝트 <암표방지를 위한 모바일 티켓팅 서비스> 를 잠시 중단한지 꽤 오랜 시간이 흘렀기 때문에 무작정 <br>
변경하기 보다는 기존의 Code를 완벽하게 다시 이해한 후에 수정하기로 결정했다. 하지만 역시나 쉬운작업은 아니였고 꽤 오랜 <br>
시간이 소요될 것 같다.. 빠르게 마무리하고 수정하려고 했던 부분을 수정해야겠다!

## 2020.1.4
### 결혼식 및 신년회 참석
- 오늘은 결혼식과 연구실 신년회가 둘다있어서 제대로된 TIL을 올리지 못할것 같다.<br>
TIL의 조건은 두가지 밖에 안되지만 생각보다 정말 지키기 힘들다.. 그래서 내일은 정말 열심히 할 생각이다

## 2020.1.6
### 암호학 세미나
#### 블록암호 운용모드<br>
- 전자 코드북 모드<br>
- 암호 블록 연결 모드<br>
- 출력 피드백 모드<br>
- 계수기 모드<br>

## 2020.1.7
### FIDO 인증 시스템
- Fast IDentity Online<br>
- 비 대면 인증 방식<br>
- 지문 인증 결과를 서버로 전송하지 않음<br>
- 위, 변조 불가 - > 부인방지 제공<br>
- 현재 Samsung Pay, Kpay등 FIDO 인증 사용 중이며 결제 부인방지가 가능하다, 또한 Onetouch만으로 신속한 결제를 제공한다.

## 2020.1.8
### Visual Studio 환경에서 Stack Memory 사용
- Int Type Data 2개를 생성, 각 Memory Address 확인시에 **주소값이 떨어져 있는 이유**<br>
- **Debug모드**로 빌드 되면 Local Variable이 Stack Area에 순차적으로 Allocation 되지만, 변수와 변수 사이 빈 공간이 추가된다.<br>
이것은 Visual C가 Debug 작업을 할 때 사용하려고 비워둔 공간.<br>
- 이 빈 공간은 "Debug" 모드에서만 제공되기 떄문에 "Release" Mode로 변경하고 솔루션을 다시 빌드 해보면 빈공간이 사라지는 것을 알 수 있다.<br>
- 또 한, 32비트(x86) 에서는 지역 변수가 선언되면 나중에 선언된 변수의 주소가 감소되는 형태이지만 64비트에서는 나중에 선언된 변수의 주소가 더 크다는 차이점이 있으니 주의.

## 2020.1.9
### 리눅스 세미나 

## 2020.1.12
### 캡스톤 디자인
#### 캡스톤 디자인 코드 재 설계 분석
- **Android Studio** LinearLayout 보다 조금더 편리하게 Layout을 배치하려면 관계형 레이아웃(Relative Layout)이 조금 더 편함.<br>
- 관계형 레이아웃은 먼저 배치했던 버튼이나 텍스트 등의 왼쪽, 오른쪽, 위, 아래 등등 으로 관계를 지어서 배치할 수 있다.<br>
- 또한 Linear Layout 은 한줄, 혹은 한열에 하나의 자식만 올 수 있다.<br>
- 코드가 워낙 길어서 전체 코드를 분석하는데 좀 오랜 시간이 걸릴 것 같다.

## 2020.1.13
### 암호학 세미나 - 의사난수 생성과 스트림 암호
#### 난수의 조건
- **임의성** : 통계학적 관념상 수의 순서가 임의적<br>
- 균일 분포 : 수열의 비트의 분포가 균일 해야함<br>
- 독립성 : 수열의 어느 부분의 수열을 다른 부분 수열로 부터 추정 불가 (일부분의 수열에 의존 X)
#### 의사 난수 (유사 난수)
- 암호학적 응용에서는 난수 생성에 알고리즘 기법 사용<br>
- 알고리즘은 입력에 출력이 결정적<br>
- 이와 같은 수를 의사 난수라고 부름<br>
- **진난수 생성기** : Entropy Source 가 Input으로 들어가서 Binary File로 변환해줌<br>
- **의사 난수 생성기** : Seed가 결정적 알고리즘의 Input으로 들어가서 의사 난수 비트 열을 만듬, 이는 대칭 스트림 암호의 입력값 등으로 사용<br>
- **의사 난수 함수** : 의사 난수 생성기와 비슷하다. 단, 결정적 알고리즘의 입력으로 특정 값이 추가된다. 이는 의사 난수 값으로, 암호화 키, 그리고 비표에 사용된다.<br>
#### PRNG(의사 난수 생성기) 요구사항
- Seed 값으로 모든 출력 값을 추론 가능<br>
- 때문에 Seed 값은 예측이 불가능 해야함<br>
- Seed 값은 대부분 **TRNG에 의해 생성된다**

## 2020.1.14
### 캡스톤 디자인
- 코드 분석 과정에서 코드의 길이가 꽤 되는데, App에서 Server로 전송해주는 방식 때문에 프로그램 전체가 꼬여버린 느낌이기 때문에 처음부터
다시 시작하기로 했음! 

## 2020.1.15
### 가트너 10대 기술동향
- 연구실 일정으로 미루어 짐.

## 2020.1.16
### 리눅스 세미나
- 실습실 컴퓨터가 작동하지 않는다,, 리눅스만 깔다가 시간 다보냈다..<br>

## 2020.1.17
### 캡스톤 디자인
- Code 분석 과정에서 결국 처음부터 다시하기로했다.. <br>
- App을 설계하는 과정이 얼마나 중요한지 다시한번 느낀다..<br>

## 2020.1.24
### 학회 업무 - mt 준비 및 학위수여식 준비

## 2020.1.25
### 소프트웨어 마에스트로 준비
- 소프트웨어 마에스트로 모집 공고가 올라왔다, 그동안 학회 업무때문에 코딩공부를 열심히 하지 못했는데, 이번 일을 계기로 열심히 알고리즘을 공부해야겠다. <br>
- 우선적으로 백준 알고리즘 문제를 쉬운단계부터 차근차근 풀고, LAB실 내에있는 알고리즘 책을 학습할 예정.<br>
- 작년에는 최종에서 떨어졌지만 이번에는 꼭 최종 합격하고 싶다.

## 2020.1.28
### 모바일 티켓팅 서비스
- 라떼판다를 다시 활성화하고 WEB 서버를 재구축했다. 라떼판다에 연결된 공유기의 포트가 열려있지 않아서, DMZ설정을 한 후에 재 연결을 진행했다. <br>
- 처음부터 다시 설계를 해야하는 문제점과, 학회일로 바빠서 코딩에 신경을 많이 못썼다는게 느껴졌다.. <br>

## 2020.1.29
### 모바일 티켓팅 서비스
- PHP 활용능력을 조금더 키워야 할 것 같다.. 지금까지 개발할 때는 구글링의 영향이 매우 컸지만,, 검색하다가 시간이 너무 많이 소요된다.<br>
- 관리프로그램은 C#을 이용할 예정인데, 어떻게하면 조금더 효율적으로 Android 와 DB 서버상에서의 유연한 연동을 시킬 수 있을지 고민된다..!
- DabaBase를 자꾸 한가지 Table로 해결하려 하는데, 좋지 않은 습관이다, 분류별로 Table을 잘 설계하는 습관을 들이자!

## 2020.1.30
### 모바일 티켓팅 서비스
- img 파일을 DataBase에 삽입하는 일반적인 방법은 img 파일을 삽입하는것이 아니라 img의 경로를 삽입하는것.<br>
- img파일을 서버에 올리고, 그 경로를 php로 불러와서 웹서버를 이용하여 출력시킨 후에 android로 받아오는 방법이 있음.<br>

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

## 2020.03.22
### Notion을 꾸준히..

## 2020.03.23
### 키 관리와 키 분배

## 2020.03.26
### 임베디드 소프트웨어
## 수업 유의사항

아두이노 키트를 활용한 팀별 수업 및 과제를 진행할 예정

이론 강의실을 이용하기 때문에 팀별 노트북 준비 필요

팀별이지만 평가는 개별로 진행 될 예정

## 임베디드란 무엇인가?
- 다양한 일을 하는 전자기기의 총칭
- 아주 작은 형태의 전자회로를 갖고있는 컴퓨터
- 다양한 사물에 내장
- 임베디드 장비
    - 횡단보도의 신호등, 지하철 및 버스 결제수단 등
- 임베디드 개발이란?
    - 다양한 사물에 전자기기를 내장해 개발하는 방식

### 오픈소스 소프트웨어

- 리눅스
- 파이어폭스
- IDE(Integrated Development Environment)

## 2020.04.03
### Data Structure

## 2020.04.14

# [암호학]1장 - 컴퓨터 보안 개요

---

# 1. 컴퓨터 보안 개념

---

> 컴퓨터 보안이란?

정보 시스템 자원(하드웨어, 소프트웨어, 펌웨어, 정보/데이터, 통신)에 대한 무결성과 가용성, 기밀성 유지와 같은 목적 달성을 위해 자동화된 정보 시스템에 적용되는 보호

**이 정의는 컴퓨터 보안의 핵심인 다음과 같은 세 가지 주요 목적을 제시하고 있음**

- **기밀성(Confidentiality)** : 기밀성은 다음과 같은 두 가지 개념을 의미한다.
    - **데이터 기밀성** : 개인적이거나 비밀스러운 정보를 권한이 없는 자에게 노출되거나 소유할 수 없도록 함
    - **프라이버시** : 개인과 관련된 어떤 정보가 수집 및 저장되는지, 그리고 누구에 의해 누구에게 해당 정보가 노출되는지를 통제하거나, 영향력을 발휘할 수 있도록  함.
- **무결성(Integrity)** : 무결성은 다음과 같은 두 가지 개념을 의미한다.
    - **데이터 무결성** : 정보와 프로그램이 오직 특정 인가된 방법에 의해서만 변경될 수 있도록 보장함
    - **시스템 무결성** : 시스템이 원하는 기능을 손상되지 않은 형태로 수행되거나 고의적 혹은 우연에 의해 시스템에 대한 비인가 조작 없이 원하는 기능을 수행할 수 있도록 보장함
- **가용성(Availability)** : 시스템이 적절한 시점에 동작 할 수 있도록 하며, 인가된 사용자에게는 서비스가 잘 제공되도록 보장함.

**이러한 3가지 개념은 보안의 3요소라고 알려진 형태를 구성한다**

## 보안의 3요소

- **기밀성** : 권한이 있는 경우에만 개인 프라이버시와 사설 정보보호를 포함하는 정보에 대한 접근과 노출을 허용함, 기밀성 손실은 정보에 대한 불법적 노출을 의미함.
- **무결성** : 정보에 대한 부인방지와 인증성(authenticity) 뿐만 아니라 부적절한 정보 수정 및 파괴를 방지하는 것을 의미함. 무결성 손실은 메시지에 대한 불법적 수정과 파괴를 의미한다.
    - **허가된 사용자 이외에 정보를 변경할 수 없어야 함**
- **가용성** : 정보를 적시에 그리고 안정 된 접근 및 사용을 보장함 가용성 손실은 정보 혹은 정보 시스템에 대한 접근 실패 혹은 사용 실패를 의미한다.
    - **어떤 사용자가 원할때 정보를 사용할 수 있어야 함**

보안 분야를 잘 이해하기 위해서는 몇 가지 개념이 추가로 정의될 필요가 있음

- **인증성** : 이것은 진짜라는 것 그리고 검증 될 수 있음, 신뢰할 수 있음을 의미함,
    - 예) 메세지 전송과 메시지 내용 그 자체, 그리고 메시지 송신자에 대한 확신 등
    - 어떤 시스템에 도착한 입력이 신뢰할 수 있는 곳으로부터 왔다는 것을 확신하는 것이 포함
- **책임 추궁성** : 어떤 개채(entitiy)의 행위는 추적될 수 있으며, 그 해당 개체의 행위라는 것도 만족하는 요구조건을 만족시키는 것이 보안목표이다. 이는 부인방지, 예방, 결함격리, 침입탐지/대응, 사후복구, 법적조치를 지원함 실제 완벽하게 안전한 시스템이라는 것은 현실적으로 이룰 수 없는 목표이므로, 보안 위반행위를 추적하여, 위반 책임자를 찾아내야 함

## 보안의 3요소 예제

### 기밀성 예제

학생 성적정보는 학생에게는 매우 중요한 정보로서 기밀성이 제공되어야 할 자원임, 미국에서는 이러한 정보의 제공이 가족교육권리 및 사생활 보호법에 의해 보호된다.

즉, 성적정보는 해당 학생과 그 학생의 부모, 그리고 학생이 직장을 구할 경우에 직장 관계자에게만 접근이 허용된다.

### 무결성 예제

병원에 데이터베이스에 저장되어 있는 알레르기 환자 정보를 예로 설명하기로 함. 의사는 데이터베이스에 저장되어 있는 정보가 정확한 정보이며, 최신 정보라고 신뢰할 수 있어야 한다. 만약 간호사와 같이 병원 관계자가 고의적으로 해당 정보를 위조하여 병원에 손실을 주려는 상황을 생각해보면, 이런 경우 데이터베이스는 가급적 빠르게 신뢰할 수 있는 상태로 복구되어야 하며, 오류를 추적하여 누가 범인인지 찾아낼 수 있어야 한다.

### 가용성 예제

구성요소나 서비스의 중요성이 높을수록 요구되는 가용성도 높다.

매우 중요한 시스템이나 응용 서비스, 디바이스에 대한 인증 서비스를 제공하는 시스템을 생각해보면 , 이 시스템이 중단 된다면 고객이 컴퓨팅 자원에 대한 접근을 할 수 없도록 하거나, 직원이 중요한 일을 할 수 없도록 함. 서비스 손실은 바로 직원의 생산성 저하와 고객 손실과 같은 금전적인 손실과 직결됨.

# 2. OSI 보안 구조(The OSI Security Architecture)

---

OSI 보안 구조 권고안 X.800은 그와 같은 체계적인 접근 방법을 규정하고 있음.

이 구조는 국제적인 표준으로 개발되었기 때문에 컴퓨터와 통신업체들이 제품개발과 서비스를 위한 보안기능을 설게하는데 구조적인 서비스 및 기법으로 참조할 수 있다. 또한 이구조는 보안에 대한 서비스, 기법 및 공격들에 초점을 두고있음.

1. **보안 공격 (Security Attack)** : 조직이 소유한 정보의 안정성을 손상시키는 제반 행위
2. **보안 기법 (Security Mechanism)** : 보안 공격을 탐지, 예방하고 그로부터 복구하기 위한 제반 기법
3. **보안 서비스 (Security Service)** : 조직의 데이터 처리 시스템 및 정보 전송에 대한 보안을 강화하기 위한 제반 서비스, 이서비스들은 보안공격을 방어하기 위한 것이며, 하나 또는 그 이상의 보안기법을 사용하여 서비스를 제공한다.

# 3. 보안 공격(Security Attacks)

---

보안공격을 분류하는 효과적인 방법은 소극적 공격(Passive Attack)과 적극적 공격(Active Attack)으로 나누는 것

**소극적 공격** : 시스템의 정보를 알아내거나 악용하지만, 시스템 자원에 영향을 주지는 않는다.

**적극적 공격** : 적극적공격은 시스템의 자원들을 변화 시키거나, 시스템 운영에 영향을 주려는 시도들이다.

## 소극적 공격

소극적 공격은 전송 정보에 대한 **도청**이나, **감시**를 의미한다. 공격자의 목적은 전송중인 정보를 취득하는 것이다. 이 유형에는 메시지 내용 공개 및 트래픽 분석이 있음

### 메시지 내용 공개

메시지 내용 공개는 쉽게 이해할 수 있다.

전화통화, 전자우편 메시지, 전송 파일 등에는 기밀 정보가 포함돼 있을 수 있으며, **적이 이들 전송 내용을 탐지하지 못하도록, 예방해야 한다.**

### 트래픽 분석

트래픽 분석은 더욱 교묘함 

공격자는 암호 메시지의 유형을 관찰할 수도 있을것, 공격자는 통신자의 장소와 실체를 파악하고, 메시지 교환 횟수와 길이를 알아낼 수도 있다. **이와 같은 정보는 통신의 성격을 추측하는데 유용하게 이용될 수 있다.**

## 적극적 공격

**적극적 공격?**
데이터 스트림의 **불법수정**, **거짓 데이터 스트림 생성**을 수반하며, **신분 위장, 재전송, 메시지 불법수정, 서비스 거부** 4가지 범주로 나뉠 수 있음

1. **신분위장** : 하나의 실체가 다른 실체로 행세를 할 때 발생, 대개 적극적 공격의 다른 유형 중 하나를 포함한다.
2. **재전송** : 데이터를 수동적으로 흭득하여, 비인가된 효과를 얻기 위해 재전송한다.
3. **메시지 수정** : 단순히 적법한 메시지의 일부가 불법 수정되거나 메시지 전송이 지연되어 순서가 바뀜으로서 비인가 된 결과를 만들어 내는 것
예) **존 스미스에게 회계 기밀문서를 읽을수 있도록 인가함** 이 **프레드 브라운이 회계 기밀 문서를 읽을 수 있도록 인가함** 으로 불법 수정 되는 것
4. **서비스 거부** : 통신 설비가 정상적으로 사용 및 관리가 되지 못하게 방해하는 것을 의미, 이러한 공격은 특정  목표물을 대상으로 함

적극적 공격은 소극적 공격에 반대되는 특성이 있음, **소극적 공격**의 경우에는 **탐지가 어렵지만 예방은 가능**하다, 반면 **적극적 공격**의 경우는 **완전 예방이 어려운데 이는 다양한 물리적인 취약점과 소프트웨어 및 네트워크상의 취약점 때문**, 적극적 공격은 완전하게 에방하기 보다는 공격을 탐지하고, 붕괴나 지연등으로부터 복구하는 것을 목표로 함

# 4. 보안 서비스(Security Service)

---

X.800은 개방형 통신시스템의 프로토콜 계층에서 제공되는 하나의 서비스로써 보안기능을 정의하고 있으며 시스템 혹은 데이터 전송에 대한 적절한 보안성을 보장한다.

> X.800은 이들 서비스를 5개의 영역과 14개의 세부 서비스로 분류하고 있다

## 인증

- **대등 개체 인증** : 연결된 실체의 신원에 대한 확신을 제공하기 위하여 논리 연결과 연관되어 사용
- **데이터 근원 인증** : 비 연결형 전송에서 수신된 데이터에 대한 송신지의 주장을 보증함

## 접근 제어

- 자원에 대한 권한이 없는 사용을 방지(즉, 이 서비스는 누가 자원에 접근할 수 있고, 어떠한 조건하에서 접근이 이루어지며, 자원의 접근동작에 무엇이 허용되는지를 제어)

## 데이터의 기밀성

**데이터의 권한이 없는 누출을 방지**

- **연결형 기밀성**
    - 연결 상의 모든 사용자데이터를 보호
- **비연결형 기밀성**
    - 단일 데이터 블럭내의 모든 사용자 데이터를 보호
- **선택 영역 기밀성**
    - 연결이나 단일 데이터 블럭의 사용자 데이터 내의 선정 범위 기밀성
- **트래픽 흐름 기밀성**
    - 트래픽 흐름 관찰로부터 유도될 수 있는 정보를 보호

## 데이터의 무결성

**수신된 데이터가 정확히 권한이 있는 실체가 송신한 것임을 확신(즉 수정,삽입,삭제,또는 재전송이 없음)**

- **복구기능이 있는 연결형 무결성**
    - 연결 상의 모든 사용자 데이터의 무결성을 제공하며, 전체 데이터 순서상의 모든 데이터 삽입, 삭제, 또는 재전송을 탐지하여 복구를 시도함
        - 메시지 스트림의 불법 변경과 서비스 부인 문제 모두를 해결할 수 있음
- **복구기능이 없는 연결형 무결성**
    - 복구형 연결 기밀성과 같으나, 탐지만하고 복구는 하지 않음.
        - 개별 메시지 대상으로만 진행, 일반적으로 불법 수정에 대해서만 보호 제공
- **선택 영역 연결형 무결성**
    - 연결 상의 전송 데이터 블럭의 사용자 블럭 내에 영역범위의 무결성을 제공하고, 선정된 범위가 수정, 삽입, 삭제, 또는 재전송 되었는지 결정
- **비연결형 무결성**
    - 단일 비연결형 데이터 블럭의 무결성을 제공하고 데이터의 수정을 탐지, 제한된 형태의 재전송 탐지가 추가로 제공될 수 있음
- **선택 영역 비연결 무결성**
    - 단일 비연결형 데이터 블럭 내의 영역범위의 무결성을 제공하고, 선정된 범위가 수정되었는지 결정

## 부인 방지

통신의 전부 또는 일부에 참여했던 통신에 한 주체에 의한 부인을 방지

- **출발지 부인 방지**
    - 메시지가 지정된 당사자에 의해 송신되었음을 증명
- **목적지 부인 방지**
    - 메시지가 지정된 당사자에 의해 수신되었음을 증명

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

## 2020.08.08
### Web Server와 WAS의 차이점
## Static Pages

- Web Server는 파일 경로 이름을 받아 경로와 일치하는 File Contents를 반환한다.
- 항상 동일한 페이지를 반환한다.
- Ex) Image, html, css, javascript파일과 같이 컴퓨터에 저장되어 있는 파일들

## Dynamic Pages

- 인자의 내용에 맞게 동적인 contents를 반환한다.
- 즉, 웹 서버에 의해서 실행되는 프로그램을 통해서 만들어진 결과물 
*Servlet: WAS위에서 돌아가는 Java Program
- 개발자는 Servlet에 doGet()을 구현한다.

# Web Server와 WAS의 차이

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0dcda02c-5f4e-4661-9638-1c4602869396/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0dcda02c-5f4e-4661-9638-1c4602869396/Untitled.png)

## Web Server

- Web Server의 개념
    - 소프트웨어와 하드웨어로 구분된다.
    - 1) 하드웨어
        - Web 서버가 설치되어 있는 컴퓨터
    - 2) 소프트웨어
        - 웹 브라우저 클라이언트로부터 HTTP 요청을 받아 **정적인 컨텐츠 (.html.jpeg.css 등)** 를 제공하는 컴퓨터 프로그램
- Web Server의 기능
    - **HTTP 프로토콜을 기반으로 하여 클라이언트(웹  브라우저 또는 웹 크롤러)의 요청을 서비스 하는 기능**을 담당한다.
    - 요청에 따라 아래의 두 가지 기능 중 적절하게 선택하여 수행한다.
    - 기능 1)
        - 정적인 컨텐츠 제공
        - WAS를 거치지 않고 바로 자원을 제공한다.
    - 기능 2)
        - 동적인 컨텐츠 제공을 위한 요청 전달
        - 클라이언트의 요청(Request)을 WAS에 보내고, WAS가 처리한 결과를 클라이언트에게 전달(응답, Reponse)한다.
        - 클라이언트는 일반적으로 웹 브라우저를 의미한다.
    - Web Server의 예
        - Apache Server, Nginx, IIS(Windows전용 Web 서버) 등

## WAS(Web Application Server)

- WAS의 개념
    - DB 조회나 다양한 로직 처리를 요구하는 **동적인 컨텐츠**를 제공하기 위해 만들어진 Application Server
    - HTTP를 통해 컴퓨터나 장치에 애플리케이션을 수행해주는 미들웨어(소프트웨어 엔진)이다.
    - **"웹 컨테이너 (Web Container)"혹은 "서블릿 컨테이너(Servlet Container)"**라고도 불린다.
        - Container란 JSP, Servlet을 실행시킬 수있는 소프트웨어를 말한다.
        - 즉, WAS는 JSP, Servlet 구동 환경을 제공한다.
- WAS의 역할
    - **WAS = Web Server + Web Container**
    - Web Server 기능들을 구조적으로 분리하여 처리하고자하는 목적으로 제시되었다.
        - 분산 트랜잭션, 보안, 메시징 ,쓰레드 처리 등의 기능을 처리하는 분산 환경에서 사용된다.
        - 주로 DB서버와 같이 수행된다.
    - 현재는 WAS가 가지고 있는 Web Server도 정적인 컨텐츠를 처리하는 데 있어서 성능상 큰 차이가 없다.
- WAS의 주요 기능
    - 프로그램 실행 환경과 DB접속 기능 제공
    - 여러 개의 트랜잭션(논리적인 작업 단위)관리 기능
    - 업무를 처리하는 비지니스 로직 수행
- WAS의 예
    - Ex) Tomcat JBoss,Jeus,Web Sphere 등

# Web Server와 WAS를 구분하는 이유

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d7200cb9-89e5-479b-94d0-058b8d19fa67/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d7200cb9-89e5-479b-94d0-058b8d19fa67/Untitled.png)

## Web Server가 필요한 이유?

- 클라이언트(웹 브라우저)에 이미지 파일(정적 컨텐츠)을 보내는 과정을 생각해보자.
    - 이미지 파일과 같은 정적인 파일들은 웹 문서(HTML 문서)가 클라이언트로 보내질 때 함께가는 것이 아니다.
    - 클라이언트는 HTML문서를 먼저 받고 그에 맞게 필요한 이미지 파일들을 다시 서버로 요청하면 그때서야 이미지 파일을 받아온다.
    - Web Server를 통해 정적인 파일들을 Application Server까지 가지 않고 앞단에서 빠르게 보내줄 수 있다.
- 따라서 Web Server에서는 정적 컨텐츠만 처리하도록 기능을 분배하여 서버의 부담을 줄일 수 있다.

## WAS가 필요한 이유?

- 웹 페이지는 정적 컨텐츠와 동적 컨텐츠가 모두 존재한다.
    - 사용자의 요청에 맞게 적절한 동적 컨텐츠를 만들어서 제공해야 한다.
    - 이때, Web Server만을 이용한다면 사용자가 원하는 요청에 대한 결과값을 모두 미리 만들어 놓고 서비스를 해야한다.
    - 하지만 이렇게 수행하기에는 자원이 절대적으로 부족하다.
- 따라서 WAS를 통해 요청에 맞는 데이터를 DB에서 가져와서 비즈니스 로직에 맞게 그때 그때 결과를 만들어서 제공함으로써 자원을 효율적으로 사용할 수 있다.

## 그렇다면 WAS가 Web Server의 기능도 모두 수행하면 되지 않을까?

1. **기능을 분리하여 서버 부하 방지**
    - WAS는 DB 조회나 다양한 로직을 처리하느라 바쁘기 때문에 단순한 정적 컨텐츠는 Web Server에서 빠르게 클라이언트에 제공하는 것이 좋다.
    - WAS는 기본적으로 동적 컨텐츠를 제공하기 위해 존재하는 서버이다.
    - 만약 정적 컨텐츠 요청까지 WAS까지 처리한다면 정적 데이터 처리로 인해 부하가 커지게 되고, 동적 컨텐츠의 처리가 지연됨에 따라 수행 속도가 느려진다.
    - 즉, 이로 인해 페이지 노출 시간이 늘어나게 될 것이다.
2. **물리적으로 분리하여 보안 강화**
    - SSL에 대한 암복호화 처리에 Wev Server를 사용
3. **여러 대의 WAS를 연결 가능**
    - Load Balancing을 위해서 Web Server를 사용
    - fail over(장애 극복), fail back 처리에 유리
    - 특히 대용량 웹 어플리케이션의 경우(여러 개의 서버 사용) Web Server와 WAS를 분리 하여 무중단 운영을 위한 장애 극복에 쉽게 대응할 수 있다.
    - 예를 들어, 앞 단의 Web Server에서 오류가 발생한 WAS를 이용하지 못하도록 한 후 WAS를 재 시작함으로써 사용자는 오류를 느끼지 못하고 이용할 수 있다.
4. **여러 웹 어플리케이션 서비스 가능**
    - 예를 들어, 하나의 서버에서 PHP Aplication과 Java Application을 함께 사용하는 경우
5. **기타**
    - 접근 허용 IP관리, 2대 이상의 서버에서 세션 관리 등도 Web Server에서 처리하면 효율적이다.
- 즉, 자원 이용의 효율성 및 장애 극복, 배포 및 유지보수의 편의성을 위해 Web Server와 WAS를 분리한다.
- **WEB Server를 WAS앞에 두고 필요한 WAS들을 Web Server에 플러그인 형태로 설정하면 더욱 효율적인 분산 처리가 가능하다.**

## 2020.08.09
## 소프트웨어 생명 주기 (Software Life Cycle)

소프트웨어 생명 주기는 소프트웨어 개발 방법론의 바탕, 소프트웨어를 개발하기 위해 정의하고 운용, 유지보수 등의 과정을 각 단계별로 나눈 것

- 소프트웨어 생명 주기는 소프트웨어 개발 단계와 각 단계별 주요 활동, 그리고 활동 결과에 대한 산출물로 표현 함, **소프트웨어 수명 주기라고도 함**
- 생명 주기를 표현하는 형태를 **생명 주기 모형이라고 함**
- 일반적으로 사용되는 소프트웨어 생명 주기 모형에는 **폭포수 모형, 프로토타입 모형, 나선형 모형, 애자일 모형 등이 있음**

## 폭포수 모형(Waterfall Model)

폭포에서 한번 떨어진 물은 거슬러 올라갈 수 없듯이 소프트웨어 개발도 이전 단계로 돌아갈 수 없다는 전제하에 각 단계를 확실히 매듭짓고 다음 단계를 진행하는 개발 방법론

- 고전적 생명 주기 모형이라고도 함
- 개발 과정의 한 단계가 끝나야만 당므 단계로 넘어갈 수 있는 순차적 모형
- 제품의 일부가 될 메뉴얼을 작성해야 함
- 각 단계가 끝난 후에는 다음 단계를 수행하기 위한 결과물이 명확하게 산출되어야 함
- 두개 이상의 과정이 병행하여 수행되지 않아야 함

> Ex) 타당성 검토 → 계획 → 요구분석 → 설계 → 구현 → 시험 → 유지보수

## 프로토 타입 모형(Prototype Model, 원형 모형)

사용자의 요구사항을 정확히 파악하기 위해 실제 개발될 소프트웨어에 대한 견본품을 만들어 최종 결과물을 예측하는 모형

- 시제품은 사용자와 시스템 사이 인터페이스에 중점을 둠
- 시스템의 일부 혹은 시스템의 모형을 만드는 과정, 추후 구현 단계에서 사용될 골격 코드
- **개발이 완료된 시점에서 오류가 발견되는 폭포수 모형의 단점을 보완하기 위한 모형**

## 나선형 모형(Spiral Model, 점진적 모형)

나선형 모형은 보헴이 제안, 폭포수, 프로토 모형의 장점에 위험 분석 기능을 추가한 모형

- 나선을 따라 돌듯이 여러 번의 소프트웨어 개발 과정을 거쳐 점진적으로 완벽한 최종 소프트웨어를 개발하는 것, **점진적 모형이라고도 함**
- **점진적으로 개발 과정이 반복되므로 누락되거나 추가된 요구사항을 첨가할 수 있고, 정밀하며 유지보수 과정이 필요없음**

## 애자일 모형(Agile Model)

'민첩한', '기민함' 이라는 의미, 고객 요구사항 변화에 유연하게 대응할 수 있도록 일정한 주기를 반복하면서 개발과정 진행

- 어느 특정 개발방법론이 아니라 좋은 것을 빠르고 낭비없게 만들기 위해 **고객과의 소통에 초점을 맞춘 방법론을 통칭함**
- 애자일 모형은 스프린트(Sprint)또는 이터레이션 (Iteration)이라고 불리는 짧은 개발주기를 반복, 주기마다 결과물에 대한 고객의 평가와 요구를 적극 수용함
- 애자일 모형을 기반으로 하는 소프트웨어 개발 모형에는 **스크럼, XP, 칸반(Kanban), Lean, 크리스탈, ASD, FDD DSDM, DAD 등이 있다.**

## 2020.08.16
### 데이터베이스 보안 - 접근통제
### 임의 접근통제 (Discretionary Access Control)
- 신원에 따라 권한 부여
- 주체가 통제권한을 지정 및 제어한다
- DAC는 객체를 생성한 사용자가 생성 객체의 모든 권한을 부여 받고, 부여된 권한을 다른 사용자에게 허가 할 수도 있다.
- EX) GRANT, REVOKE
### 강제 접근통제
- 주체와 객체의 등급을 비교, 권한 부여 함
- 제 3자가 접근통제 권한을 지정함
- 데이터베이스 객체별로 보안 등급을 부여할 수 있고, 사용자별로 인가 등급을 부여할 수 있다.
- 주체는 자신보다 보안 등급이 높은 객체에 대해 읽기, 수정, 등록이 모두 불가능
- 보안 등급이 같은 객체에 대해서는 읽기, 수정, 등록이 가능하고, 보안 등급이 낮은 객체는 읽기가 가능하다.

## 2020.08.17
### MVC Pattern (Model-View_Controller Pattern)
모델-뷰-컨트롤러 패턴은 서브시스템을 3개의 부분으로 구조화하는 패턴이며, 각 부분의 역할은 다음과 같다.
- 모델(Model) : 서브시스템의 핵심 기능과 데이터를 보관
- 뷰(view) : 사용자에게 정보를 표시한다.
- 컨트롤러(Controller) : 사용자로부터 받은 입력을 처리한다.
#### 특징
- 모델 - 뷰 - 컨트롤러 패턴의 각 부분은 별도의 컴포넌트로 분리되어 있으므로 서로 영향을 받지 않고 개발 작업을 수행할 수 있다.
- 모델 - 뷰 - 컨트롤러 패턴에서는 여러 개의 뷰를 만들 수 있으므로 한 개의 모델에 대해 여러 개의 뷰를 필요로 하는 대화형 애플리케이션에 적합하다.

## 2020.08.19
### Pipe-Filter Pattern
데이터 스트림 절차의 각 단계를 필터 컴포넌트로 캡슐화하여 파이프를 통해 데이터를 전송하는 패턴
#### 특징
- 필터 컴포넌트는 재사용성이 좋고, 추가가 쉬워 확장이 용이하다.
- 필터 컴포넌트들을 재배치하여 다양한 파이프라인을 구축하는 것이 가능하다
- 파이프-필터 패턴은 데이터변환, 버퍼링, 동기화 등에 주로 사용 됨
- 대표적으로 UNIX의 쉘이 있다.

## 레이어 패턴(Layers Pattern)

레이어 패턴은 시스템을 계층으로 구분하여 구성하는 고전적인 방법

- 레이어 패턴은 각각 서브시스템들이 계층 구조를 이루며, **상위 계층은 하위 계층에 대한 서비스 제공자가 되고 하위 계층은 상위 계층의 클라이언트가 된다.**
- 서로 마주보는 **두 계층 사이에서만 상호작용**이 이루어진다. = 변경 작업이 용이
- **특정 계층만을 교체해 시스템을 개선**하는 것이 가능하다.

## 클라이언트-서버 패턴(Client-Server Pattern)

**하나의 서버 컴포넌트**와 **다수의 클라이언트** 컴포넌트로 구성되는 패턴이다.

- 사용자는 클라이언트와만 의사소통을 한다.
- 사용자가 클라이언트를 통해 서버에 요청하고, **클라이언트가 응답을 받아 사용자에게 제공**하는방식으로 서비스를 제공
- 서로 동기화 되는 경우를 제외하고는 **서로 독립적**

## 2020.08.20
### Design Pattern
디자인 패턴은 각 모듈의 세분화된 역할이나 모듈들 간의 인터페이스와 같은 코드를 작성하는 수준의 세부적인 구현 방안을 설계할 때 참고할 수 있는 전형적인 해결 방식 또는 예제를 의미한다
- 디자인 패턴은 한 패턴에 변형을 가하거나, 특정 요구사항을 반영하면 유사한 형태의 다른 패턴으로 변화되는 특징이 있다.
- GoF의 디자인 패턴은 유형에 따라 생성 패턴 5개, 구조 패턴 7개, 행위 패턴 11개 총 23개의 패턴으로 구성된다.

## 2020.10.09
### JSP & Servlet

> JSP, Servlet 은 자바로 웹 어플리케이션을 만들기 위한 도구, 웹을 조금 더 쉽게 다룰 수 있도록 해주는 확장 기능이라고 생각하면 됨

#### JSP

- 확장자가 .jsp인 파일
- Java Server Page
- HTML 문서 안에 JAVA 언어를 삽입해 사용할 수 있도록 해줌

#### Servlet(서블릿)

- 확장자가 .java인 파일
- 자바의 일반적인 클래스와 동일한 개념
- 웹을 다룰 수 있도록 해주는 "HttpServlet" Class를 상속받은 클래스를 의미

JSP와 Servlet은 완전 다른 개념이 아니며, Servlet을 사용해 웹을 만들 경우 화면 인터페이스 구현이 워낙 까다로운 단점을 보완하기 위해 만든 스크립트 언어가 JSP

#### 웹 어플리케이션의 일반적인 구조

> WEB, WAS, DB 서버는 물리적인 서버가 아닌 논리적인 구조
물리적인 구성은 Server Spec, 사용자 수, 보안 및 네트워크 구조에 맞춰서 설계

1. 사용자가 URL(또는 IP)을 통해 WEB 서버를 호출하고 요청사항을 객체(request)에 담아 전송
2. WEB 서버는 요청 객체(request)를 받아서 바로 처리하거나 어플리케이션 서버(WAS)로 객체 전달
3. WAS 서버는 요청에 대한 내용과 요청 객체(request)를 받아 적절히 처리(필요시 DB작업 진행)
4. WAS 서버는 처리 후 결과를 응답 객체(response)에 담아 WEB 서버로 회신
5. WEB 서버는 응답 객체(response)를 다시 사용자에게 회신
6. 사용자의 브라우저는 WEB 서버가 보내준 코드를 해석해 화면을 구성하도록 출력

#### WEB Server 단일 구성

1. 개발자는 미리 모든 페이지를 다 만들어 두고 웹서버에 올려둠
2. 사용자가 URL을 입력하거나 하이퍼링크가 걸린 글/ 그림등을 클릭
3. 웹서버가 해당하는 페이지를 사용자에게 보내줌
4. 브라우저는 페이지를 받아서 화면으로 만든 뒤 사용자에게 시각화하여 보여줌

##### 특징

- 페이지는 주로 html, CSS, JavaScript 로 이루어져 있음
- JavaScript는 동적 스크립트로 상황에 따라 다른 결과를 출력할 수 있는 동적인 스크립트 언어, 쉽게말해 html에서는 if문을 사용할 수 없는데 JavaScript는 이게 가능,
- html, CSS 만으로 이루어진 웹페이지는 그냥 PDF 파일을 보여주는것과 크게 다르지 않음
- 세가지 언어 모두 웹서버에서 코드를 보내주면 브라우저가 해석해서 실행 함

