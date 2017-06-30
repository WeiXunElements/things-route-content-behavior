# things-route-content-behavior

## 메뉴를 통해 라우팅된 화면의 동작을 정의하는 Behavior

  메뉴가 선택이 되는 순간 자신의 라우팅 정보와 메뉴에서 선택된 라우팅이 일치하는지 체크하여 화면 초기화를 진행한다.

  Things.RouteContentBehavior를 상속하는 컴포넌트에서는 반드시 this.getMyRoute()와 initializeContent() 함수를 구현해야 한다.

  getMyRoute() 함수는 자신의 route 정보를 리턴해야 하고 initializeContent() 함수는 화면 초기화를 진행하는 함수이다.


*****
</br></br>


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-route-content-behavior/`, where `things-route-content-behavior` is the name of the directory containing it.
