react_study 1

# react란?
  > JavaScript 라이브러리이다.
  "컴포넌트" 코드의 파편을 이용하여 ui를 구성하도록 한다.

#### 컴포넌트란? (Component)
  > 리액트로 만들어진 앱을 이루는 최소한의 단위

- 기존의 웹 프레임워크는 MVC방식으로 분리하여 각 요소의 의존성이 높아? 재활용이 어렵다는 단점이 있으나,
  컴포넌트 MVC방식은 부를 독립적으로 구성하여 재사용을 할 수 있고 이를 통해 새로운 컴포넌트를 쉽게 만들 수 있다.???

  ##### 웹프레임워크의 mvc방식?
  > 각각의 Model, Controller, View 앞글자를 따 mvc방식으로 불린다.

  ![mvc방식](https://github.com/ekals1210/react_test/assets/85346859/2b8016ae-c0cd-491b-860c-f4e4794d09ef)

  => 사용자가  controller를 조작하면, controller는  model을 통해 데이터를 가져오고 그 데이터를 바탕으로 view를 통해 시각적 표현을 제어하여 사용자에게 전달한다.

  ex) 웹 mvc방식 예시
  1. 사용자가 웹사이트에 접속
  2. controller는 사용자가 요청한 웹페이지를 서비스 하기 위해서 모델을 호출
  3. model은 데이터 소스를 제어한 후 그 결과를 return
  4. controller는 model이 리턴한 결과를 view에 반영
  5. 데이터가 반영된 view를 사용자가 봄
 
  (단점)
  
  
      
