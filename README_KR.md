# things-route-content-behavior

## 이는 메뉴를 통해 라우팅된 화면의 동작을 정의하는 Behavior이다.

  메뉴가 선택되는 순간, 자신의 라우팅 정보와 메뉴에서 선택된 라우팅이 일치하는지 체크하여 화면 초기화를 진행한다.

  Things.RouteContentBehavior를 상속하는 컴포넌트에서는 반드시 this.getMyRoute()와 initializeContent() 함수를 구현해야 한다.

  getMyRoute() 함수는 자신의 route 정보를 리턴하고 initializeContent() 함수는 화면 초기화를 진행한다.


*****
</br></br>


## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install

## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-route-content-behavior`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-route-content-behavior/`를 통해 이를 미리 확인할 수 있다. 
