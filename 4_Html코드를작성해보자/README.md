## HTML 문서의 구조

- 기본구조
    
    ```html
    ~<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        
    </body>
    </html>
    ```

```
<!DOCTYPE html>

- 문서의 첫 부분에서 문서 유형을 지정하는 단일 태그
- 이 문서의 대한 유형을 메세지 전달
- 여러 html 버전을 사용하기 위해 적어주는 타입이 바로 ‘html’
```

```
<html></html>

- 실제  문서가 시작되고 끝나는 것을 나타내는 코드
- 이 태그의 내부에 다양한 태그들이 포함되어 문서의 내용을 구성
- <html>에서 시작하여 </html>에서 모든 태그가 들어감
```

```
<head></head>

- 웹 브라우저 화면에는 보이지 않지만 웹 브라우저가 알아야 할 정보들은 모두 이 태그가 들어감
- <mata charset=”urf-8>
    - 문자 인코딩 및 문서 키워드 등에 대학 요약 정보를 기입하는 단일 태그
    - 문자 인코딩이란 한글을 표시하기 위해 utf-8사용
- <title></title>
    - 브라우저 새창 화면에 뜨는 글
```
```
<body></body>

- 제일 중요한 부분
- 여기서 User Interface가 보임
- 주로 보여지는 태그들을 여기서 사용함.
```

## 내용정리

- Html 코드를 작성할 때는 기본 문서 구조를 마련한 다음 작성한다
- 들여쓰기를 통해 태그 간의 포함관계를 나타낸다. 이는 가독성에 도움이 되지만 필수사항은 아니다.
- <head> 태그에는 문서의 정보가, <body> 태그는 표시할 내용이 포함된다.
- 태그의 콘텐츠로 또 다른 태그가 포함될 수 있다.
