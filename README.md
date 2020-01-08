# TIL
Today I  Learned, 매일 무엇을 배웠는지 정리하고 기록합니다.

## 규칙
- 개발자로서 꾸준한 성장을 위해 학습경험을 기록합니다.<br>
- 쓸모없는 내용은 지양하고 모든 내용은 본인이 직접 작성합니다.<br>

## 2019.11.30

### 선후배 스터디

- 장소 : GFC
- 배운 내용 : 
  - Github
  - Notion
  - Slack
- 안녕하세요

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
- 현제 Samsung Pay, Kpay등 FIDO 인증 사용 중이며 결제 부인방지가 가능하다, 또한 Onetouch만으로 신속한 결제를 제공한다.

## 2020.1.8
### Visual Studio 환경에서 Stack Memory 사용
- Int Type Data 2개를 생성, 각 Memory Address 확인시에 주소값이 떨어져 있는 이유<br>
- **Debug모드**로 빌드 되면 Local Variable이 Stack Area에 순차적으로 Allocation 되지만, 변수와 변수 사이 빈 공간이 추가된다.<br>
이것은 Visual C가 Debug 작업을 할 때 사용하려고 비워둔 공간.<br>
- 이 빈 공간은 Debug 모드에서만 제공되기 떄문에 "Release" Mode로 변경하고 솔루션을 다시 빌드 해보면 빈공간이 사라지는 것을 알 수 있다.<br>
- 또 한, 32비트(x86) 에서는 지역 변수가 선언되면 나중에 선언된 변수의 주소가 감소되는 형태이지만 64비트에서는 나중에 선언된 변수의 주소가 더 크다는 차이점이 있으니 주의.
