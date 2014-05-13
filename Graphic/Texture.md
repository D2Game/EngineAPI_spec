Texture
====

텍스쳐 클래스

Constants
----

* __Type__
    * __Static__ : 정적 텍스쳐 - 자주 바뀌지 않음
    * __Streaming__ : 스트리밍 텍스쳐 - 자주 변경됨
    * __Target__ : 렌터 타겟 텍스쳐
  
* __MaxSize__ : 시스템에서 사용할 수 있는 최대 텍스쳐 크기


Public methods
----

* __new(width, height, type)__<br>

      텍스쳐를 생성한다.<br>
      width : 생성할 텍스쳐의 가로 크기 (Fixnum)<br>
      height : 생성할 텍스쳐의 세로 크기 (Fixnum)<br>
      type : 텍스쳐 타입 (Texture::Type)
    
* __dispose__

    텍스쳐를 파괴한다.
    
* __draw(x,y)__

    지정된 위치에 텍스쳐를 그린다.<br>
    x : 그릴 x좌표값 (Fixnum)<br>
    y : 그릴 y좌표값 (Fixnum)<br>
    
Properties
----

* __type__[R]

  텍스쳐의 타입 (Texture::Type)
  
* __blendmode__[RW]

  블렌드 모드 (Blendmode)
  
* __size__[R]

  텍스쳐의 크기 (Size)
