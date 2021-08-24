# Chellenge-to-GSitm

## 1일차
### 오늘 목표
1. HTML 튜토리얼 
2. 교재 Chapter2까지 완독 및 실습 따라하기

## 첫째마당
 ### 웹 개발 시작
 #### 웹사이트 분류
   - 정적 사이트(static site)
     작성자가 미리 작성한 내용을 웹사이트에 올려놓으면 방문자가 정보를 확인하는 방식
     즉, 서비스, 기능이 없음.
   - 동적 사이트(dynamic site)
     웹 브라우저에 보여지는 모습 뿐만 아니라 제공할 기능, 서비스를 포함하고 있음.
 #### 서버와 클라이언트
   - 서버(server)
     웹 사이트에 작성된 기능, 텍스트, 이미지, 동영상등 웹 요소와, 사용자 정보, 상품 정보등의 여러가지 정보를 저장하고 있음.
   - 클라이언트(client)
     웹 사이트에 접근하려고 사용하는 단말(PC, 스마트폰, 태블릿PC 등)
     
     <img width="814" alt="server-client" src="https://user-images.githubusercontent.com/38834702/130520658-2bf9cf18-388e-4aeb-a213-fc3e32fbfacf.png">
     
 #### 웹 개발을 위한 스택
 
    - 기본
      HTML
      CSS
      javascript
      git/github
    
    - front-end
      * 다양한 라이브러리
        +제이쿼리, D3.js, 부트스트랩 등
      * 프레임워크
        +리액트, 앵귤러, 뷰 등
       
     - back-end
       linux server, network, database
       * 서버 언어
         + 파이썬, 자바, PHP, dotnetFramework
       * 프레임워크
         + 노드제이에스, 스프링, 장고, 코드이그나이터 등
 
 
 #### HTML 구조
    - 기본구조
      * 
      '''
      
        <!doctype html> <--웹 문서 유형 지정 선언문-->
        <html></html> <--웹 문서의 시작-->
        <head></head> <--웹 브라우저에 문서정보를 알려주는 태그--> <meta> <--문서 정보--> <title></title> <--문서 제목-->
        <body></body> <--웹 브라우저에 내용 표시-->
      
      '''
 #### 시맨틱 태그
    - html의 태그들은 이름만 봐도 의미를 알수 있어 시맨틱 태그라고 불리움.
      * <header>
      * <nav>
      * <main>
      * <article>
      * <section>
      * <aside>
      * <footer>
       등등

## 2일차
### 오늘 목표 
1. 교재 Chapter5 완독, css 훑어 보기, 자바스크립트 입문 및 실습
2. 개인 프로젝트, 팀 프로젝트 화면정의서 작성
3. 개인 프로젝트, 팀 프로젝트 레이아웃 작성

### Chapter5 입력 양식 

 사용자에게서 무엇인가를 입력받을수 있도록 만든것으로 form 이라고함.
 
 * form tag속성
  - method
    - get   ->  url에 입력값이 그대로 드러나는 단점이 있음  전송 용량은 256 ~ 4096 byte 까지 
    - post  ->  길이에 제한이 없고, 사용자가 입력한 값이 그대로 드러나지 않음
 
 * input tag
   다양한 폼에서 사용자가 입력한 정보를 넣는 공간.
   - type이 상당히 많이 존재한다.
   - 타입에 따라 입력을 받는 공간의 형태와 받을수 있는 값의 형태가 달라지기도 함.
   
   -hidden type
     화면에 표시되지 않음
     보여줄 필요는 없지만 관리자가 알아야 하는 정보를 히든 필드로 입력
   
  * 속성
    - required = 필수 입력 필드



## 셋째 마당

- css의 역할은 각 객체들을 정렬하거나 꾸미는데 쓰임.
- 추후에 사용하며 익혀갈 예정.


## 넷째 마당
### 자바스크립트
#### 자바스크립트의 기능, 용어, 기본 입출력

 * 자바스크립트는 웹의 요소를 제어함
   고정적이었던 웹 스타일을 동적이게 바꿀수 있음
 * 웹 어플리케이션 작성
   지도, 게임등등
 * 다양한 라이브러리 사용가능
 * 서버 개발 가능(Node.js)
