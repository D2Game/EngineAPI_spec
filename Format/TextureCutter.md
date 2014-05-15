TextureCutter
====

Singleton methods
----
* __load(texture, wSlice,hSlice)__
  
  텍스쳐를 일정한 크기의 가로, 세로 조각으로 잘라서 스프라이트를 생성합니다.<br>
  __texture__ : 자를 텍스쳐 (Texture)
  __wSlice__ : 자를 가로 조각의 갯수 (Fixnum)
  __hSlice__ : 자를 세로 조각의 갯수 (Fixnum)
  __return__ : 스프라이트의 리스트 (Array<Sprite>)
  

Usage
----
```Ruby
  frames = TextureCutter.load("player.png", 4,4)
  
  # 특정한 스프라이트 객체 가져오기
  frames[0]
  
  # 모든 스프라이트 객체 가져오기
  frames.each do |sprite|
    sprite
  end
```
