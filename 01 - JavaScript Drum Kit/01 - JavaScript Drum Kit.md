## 01 - JavaScript Drum Kit

### 1. HTML

#### key code

* 모든 키보드의 키는 key up 이나 Key down 이벤트를 일으킬 때 그 키와 관련된 키 코드를 갖게 된다.
* cf. keykode.info



#### data-* attribute

- data-key, data-something 등 data 뒤에 원하는 단어를 붙여 자신만의 attribute를 만들 수 있다. 추가적인 정보를 위해 사용한다.



### 2. JS

```javascript
audio.currentTime = 0; // rewind to the start
audio.play();
```

* 이미 실행중인 audio에 play()를 다시 호출하게 되면 이미 실행중인 audio가 끝날 때까지 기다린다.
* 연속적으로 key를 누를 때마다 audio를 실행시키고 싶다면 `audio.currentTime = 0;` 을 통해 audio의 시작 위치를 바꿔준다.

