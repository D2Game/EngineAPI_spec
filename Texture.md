Texture
====

텍스쳐 클래스

Constants
----

* Type
    * Static : 정적 텍스쳐 - 자주 바뀌지 않음
    * Streaming : 스트리밍 텍스쳐 - 자주 변경됨
    * Target : 렌터 타겟 텍스쳐
  
* MaxSize : 시스템에서 사용할 수 있는 최대 텍스쳐 크기


Public methods
----

* new(width, height, type)<br>

      텍스쳐를 생성한다.<br>
      width : 생성할 텍스쳐의 가로 크기 (Fixnum)<br>
      height : 생성할 텍스쳐의 세로 크기 (Fixnum)<br>
      type : 텍스쳐 타입 (Texture::Type)
    
* dispose

    텍스쳐를 파괴한다.
    
* draw(x,y)

    지정된 위치에 텍스쳐를 그린다.<br>
    x : 그릴 x좌표값 (Fixnum)<br>
    y : 그릴 y좌표값 (Fixnum)<br>
    
Properties
----

* type - r

  텍스쳐의 타입 (Texture::Type)
  
* blendmode - rw

  블렌드 모드 (Blendmode)
  
* size - r

  텍스쳐의 크기 (Size)
