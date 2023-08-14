# 14. 폼(form) Part2. 폼 태그
이전 13과 이어지는 부분

## form

- form은 입력 요소를 감싸며, 입력 값을 서버 측으로 제출(submit) 가능

```
<form>
    <input type="text" placeholder="아이디">
    <br>
    <input type="text" placeholder="비밀번호">
</form>
```

## form의 내용을 제출

- form의 내용(입력값)을 제출하기 위해 input 태그의 submit 타입 사용 가능
```
<form>
    <input type="text" placeholder="아이디">
    <br>
    <input type="text" placeholder="비밀번호">
    <br>
    <input type="submit" valuse="로그인">
</form>

'로그인' 버튼을 누르면 입력된 아이디와 비밀번호가 서버로 전송되고(요청),
서버측에서 데이터를 처리한 결과를 클라이언트에게 보내준다(응답)
```

## form의 속성

- action : 입력값을 전송할 서버의 url
- method : 클라이언트가 입력한 데이터를 어떤 식으로 전송할지(GET or POST)

```
<form action="example.php" method="POST"></form>
- example.php라는 서버 프로그램으로 입력값을 전송하여 요청할 것.
- POST 방식으로 전송
```

## GET vs POST

- GET : 서버에 요청을 보내어 응답을 받아냄, 서버로부터 정보를 '가져오는' 성격의 요청
- POST : 서버에 요청을 보내어 작업을 수행, 서버에 있는 데이터를 추가/수정/삭제 한 후에 응답을 받음, 서버의 정보를 '조작'의 요청
- 더 자세한 이야기는 HTML을 공부한 이후라도 늦지 않음.

## 내용 정리

- form은 사용자가 입력 요소에 입력한 데이터를 서버로 전송
- 서버란 데이터를 제공하는 호스트
- 클라이언트란 데이터를 제공받아 이용하는 고객(사용자)
- form은 입력요소(input, select, textarea 등)를 감싸고 데이터를 제출(submit)
- form의 action은 서버 측 주소를 지정하는 속성
- form의 method는 데이터 전송 방식을 지정하는 속성