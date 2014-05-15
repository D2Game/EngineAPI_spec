Mouse
====

Constants
----
* __Button__
  * __Left__ : 마우스 왼쪽 버튼
  * __Right__ : 마우스 오른쪽 버튼
  * __Wheel__ : 마우스 휠 버튼

Public methods
----
* __new__

  Mouse 오브젝트를 생성합니다.
  
* __update__

  Mouse 오브젝트의 상태를 갱신합니다.
  
* __pressed?(btn)__

  마우스 버튼이 눌려있는 상태인지 조사합니다.<br>
  __btn__ : 조사할 마우스 버튼 (Mouse::Button)<br>
  __return__ : true or false
  
Properties
----
* __x__[R]

  현재 마우스 커서의 위치 x좌표 (Fixnum)
  
* __y__[R]

  현재 마우스 커서의 위치 y좌표 (Fixnum)
