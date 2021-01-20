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

# MVC Pattern

- M(Model) : Logic(연산 등) 수행(Data Task 포함)을 담당
- V(View) : User 화면 출력을 담당
- C(Controller) : 중앙에서 Model과 View의 제어를 담당

**MVC Pattern이란?**

Web Application Server 안에서의 역할을 3가지로 나눠서 구성하는 Design Patten 을 의미함.

일반 Java Program을 작성할 때, 기능별로 Modularization 하는 것과 다르지 않음. Web App도 Java에서 확장되어 나온 기능이기 때문에 기본적인 원리는 같음


## Controller

- 모든 요청은 Controller로 모임, 사용자가 직접 URL을 입력해서 접근하건 View → View를 호출하건 Model → Model을 호출하건 모두 Controller를 거치게 됨, **일종의 작업 분배기**
- Tomcat Server에서 구동되는 가장 핵심적인 역할이기 때문에 Servlet(HttpServlet) Class를 상속받아서 Servlet이 됨.
    - 특히 사용자의 요청 내용과 Connection 정보 등을 내장 Object 형태로 가지고 있어 이를 적절히 처리할 수 있는 기능을 가지고 있음
- 이 정보를 Model에게 넘겨서 Logic을 수행하게 하고, 다시 Result를 받아 View에게 전달해 최종 화면을 User에게 넘겨 줌
- 또는 바로 View를 Call해서 User에게 화면을 보여줄 수도 있음

## Model

- 실제 Logic을 수행하는 Java Class.
- Command는 Logic을 수행하는 기능을 가진 Class를 의미, DAO/DTO 는 DB와 연동되어 Data Task를 담당하는 기능의 Class
- 일반적인 Java Programming 과 동일한 구조

## View

- 최종 작업 결과물을 가지고 적절한 화면을 구성해서 User에게 전달하는 기능
- 화면 구성은 JSP가 편리하기 때문에 대부분 JSP를 사용해 View를 구성
- Tomcat Server는 Controller가 최종적으로 실행시킨 JSP File을 Servlet으로 변환해서 Compile한 뒤 실행
- 결과적으로 사용자에게 도달하는 Data는 html형태의 Code가 됨
- Browser는 Result Code를 받아 화면 구성을 하여 User에게 보여줌

MVC Pattern을 꼭 지켜야 하나?

개발자가 필수적으로 MVC Patten을 지켜야 하는 것은 아님. 하지만 많은 Framework 들이 MVC Patten을 사용하고 있고, 운영 및 유지보수, 협업이라는 측면에서 가장 효율적인 Patten중 하나이기 때문에 항상 이 구조를 염두해 두고 개발하는 것이 좋음.

# 빅데이터 처리 기술
## Hadoop
- 여러 컴퓨터로 구성된 클러스트를 이용, 방대한 양의 데이터를 처리하는 분산처리 프레임워크
- 엔진 형태로 되어있는 미들웨어와 소프트웨어 개발 프레임워크로 구성되어 있음
- 즉시 응답해야 하는 트랜잭션 처리보다는 데이터를 모은 후 처리하여 작업을 완료해야 응답을 주는 방식으로 설계되었음
- 어느 정도의 시간이 소요되는 방대한 양의 데이터 처리에 적합함
- 맵 리듀스의 분산 처리 구조를 사용하며 맵리듀스는 하나의 큰 데이터를 여러개의 조각으로 나누어 처리하는 맵 단계와 처리된 결과를 하나로 모아서 취합한 후 결과를 도출해내는 리듀스 단계로 구성되어 있음
