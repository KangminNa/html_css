# 12. select 그리고 textarea
input 외 입력 요소들

## 보기중에 골라보자

- select는 다수의 옵션(선택지)을 포함할 수 있는 선택 메뉴
- 메뉴 안에 포함되는 옵션은 option 태그를 사용해 표시

```
<select>
    <option>스타벅스</option>
    <option>커피빈</option>
    <option>이디야</option>
    <option>파스쿠찌</option>
</select>

result -> 드랍다운 박스 형태의 선택지가 나옴.
```

## 이름과 값

- select에는 input과 마찬가지로 name을 지정할 수 있으며, option에는 value 속성을 지정 가능
- value는 실제로 처리될 값을 나타낸다.

```
<select>
    <option value="starbucks">스타벅스</option>
    <option value="coffeebean">커피빈</option>
    <option value="ediya">이디야</option>
    <option value="pascucci">파스쿠찌</option>
</select>

result -> 'cafe의 입력 값은 coffeebean이다' 라는 결론!
```

## textarea

- textarea는 여러 줄의 일반 텍스트를 입력할 수 있는 입력 요소
- textarea 역시 name을 추가하여 구별해줄 수 있는 입력 요소

```
<textarea name="letter"></textarea>

result:
input에서는 한 줄밖에 쓸 수 없지만, textarea는 다름.
```

## 내용정리

- select는 선택 메뉴를 나타내는 태그
- select의 각 선택지는 option 태그를 통해 표시
- 각각의 option에는 value를 지정하여 추후 처리를 준비한다.
- 자바스크립트를 통한 입력 값 처리에 value가 사용될 수 있다.
- textarea는 여러 줄의 일반 텍스트를 입력하는 요소를 나타낸다.
