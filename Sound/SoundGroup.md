SoundGroup
=====

SoundGroup은 여러개의 Sound객체를 일괄적으로 관리할 수 있도록 도와줍니다.

Public methods
----

Usage
----
```Ruby
  se_gun = Sound.new("gun.wav")
  se_hit = Sound.new("hit.wav")
  se_bomb = Sound.new("bomb.wav")
  
  # 기존 Sound객체들로부터 사운드 그룹 만들기
  se_group = SoundGroup.new(
    [se_gun, se_hit])
    
    
  # 그룹에 새 Sound객체 추가하기
  se_group.add se_bomb
  
  # 볼륨 조절
  se_group.volume = 50
  
  # 정지
  se_group.stop
```
