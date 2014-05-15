SpriteSheet
====

Singleton methods
----
* __load(file)__

  스프라이트 시트를 불러오고 시트에 맞는 스프라이트들을 생성합니다.<br>
  __file__ : 로드할 파일 이름 (String)<br>
  __return__ : 스프라이트들 (Hash<String,Sprite>)
  

Usage
----

```Ruby
  frames = SpriteSheet.load("player.json")
  
  # 특정한 스프라이트 객체 가져오기 
  frames["player_run_1.png"]
  
  # 시트 내의 모든 스프라이트 객체 가져오기
  frames.each do |name, sprite|
    sprite
  end
```
