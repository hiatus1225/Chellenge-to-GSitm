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

-- **코딩컨벤션** 
  '''
   // 세미콜론 규칙
   // 주석도 꼭 필요한 요소이면서 중요함.
   // 권장하지 않음
    var n = 10
    
    // 권장
    var n = 10;
    
    // 권장하지 않음
    var n = 10; var sum = 0;
    
    // 권장하지 않음
    var num=2;
    var sum=num+10;
    
    //권장
    var num = 2;
    var sum = num + 10;

  '''

 -- **변수명은 의미있게 작성할것.**





 **## 3일차**

 -- var 특징



  \* 호이스팅 -> '끌어 올린다'를 뜻한다.

  변수의 선언과 할당을 분리해서 선언부를 스코프의 가장 위쪽으로 끌어올린다.



  \* 재선언과 재할당

  재선언과 재할당이 가능하다.



-- let 특징

  

  \* var는 함수 영역(레벨)의 스코프(범위)

  \* 블록 영역의 스코프

  \* 재할당은 가능, 재선언은 불가능

  \* 호이스팅 불가



-- const 특징



  \* 상수변수를 의미함

  \* 재할당, 재선언 불가

  \* 블록 레벨의 스코프



 -- **변수사용시 주의점 

  

   \* 전역 변수는 최소화.

   \* var는 함수의 시작 부분에서 선언

   \* for문의 카운터 변수는 var를 사용하지 않을 것을 고려

   \* ES6를 고려하여 var보다 let을 사용.



-- 이벤트 처리기(이벤트 핸들러)



  웹 에서 발생하는 이벤트를 처리하는 함수.



-- DOM



  \* document object model

  \* 자바스크립트를 이용하여 웹 문서에 접근하고 제어할 수 있도록 객체를 사용해 웹 문서를 체계적으로 정리하는 방법

  \*  HTML요소의 계층 관계

![image-20210826081958183](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fun3dj%2FbtqQfLtcRBE%2F20wtcaUm5kgxx2fxZkuD50%2Fimg.png) 



자세한 설명과 사진 : https://chpofo.tistory.com/28   


 **## 4일차(2021-08-30)**

 -- html추가
    
    \* html 구조
    
![image-20210826081958183](https://t1.daumcdn.net/cfile/tistory/2143994B5783067120)


    \* layout
![image-20210826081958183](https://sangyeon96.gitbooks.io/do-it-html5-css3/content/assets/semantic_tag.png) 

자세한 설명과 사진 : https://sangyeon96.gitbooks.io/do-it-html5-css3/content/Chapter10-2.html


 -- CSS

  HTML이 브라우저에 보여질 틀이었다면 CSS는 해당 틀의 디자인, 정렬.

  css소스 경량화 툴 -- cssminifier.com

  우선순위 ::: 사용자 스타일 >> 제작자 스타일 >> 브라우저 기본 스타일
  적용범위 ::: !important >> 인라인 스타일 >> id 스타일 >>  클래스 스타일 >> 타입 스타일

  스타일 상속 :: 부모 태그에 포함된 자식 요소들은 별도의 스타일 지정이 없을 경우 부모 태그의 스타일을 따른다.

  \* 박스 모델
  ![image-20210826081958183](http://tcpschool.com/lectures/img_css_boxmodel.png) 
  

  마진 중첩 (마진 상쇄) :: 요소가 세로로 배치될 경우 각 요소의 마진과 마진이 서로 만나면 마진값이 큰 쪽으로 겹쳐지는 현상.

  \* 레이아웃
     
     disply : 배치 방법 결정
     