# model
MVC
=
Model View Controller의 약자로 하나의 프로젝트를 구성하는 요소를 세가지 역할로 구분한 패턴을 의미
<img src="https://user-images.githubusercontent.com/64243394/106255333-41c76800-625d-11eb-998d-498c7aa8fa53.png" width="50%">   
모델 - 데이터와 비즈니스 로직을 관리   
뷰 - 레이아웃과 화면 인터페이스   
컨트롤러 - 데이터와 비즈니스 로직 간의 상호 작용

MVC1(model1 방식)
=
JSP내 에서 뷰와 컨트롤러를 모두 처리하는 방식

장점 - JSP페이지에서 모두 작성을 하기 때문에 구조가 단순하여 구현이 쉬움   
단점 - JSP에서 뷰와 컨트롤러를 모두 작성하여 코드가 길어져 복잡하고, 프로젝트가 커질수록 유지 보수가 힘듦   


MVC2(model2 방식)
=
JSP에서 뷰, Servlet에서 컨트롤러를 처리하는 방식

장점 - 뷰와 컨트롤러를 분리하여 작성하여 코드 구조가 간단해지고, 유지보수에 유리함   
단점 - 구조가 복잡하여 구조 설계에 시간이 걸림
