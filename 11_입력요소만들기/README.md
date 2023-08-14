# 11. 입력 요소 만들기
이제는 입력도 해보자 - input 태그

## input

- 사용자로부터 값을 입력받을 수 있는 대화형 컨트롤(또는 '필드")을 나타낸다.
- 기본적으로 인라인 요소이며, 단일 태그이다.
```
<input/>
```

## input의 핵심, type 속성

- type의 값에 따라 입력 요소의 형태나 입력 데이터 유형 등이 달라진다.
- 사용 가능한 tpye은 20여가지이며, 기본 값은 text이다.
![]("https://github.com/KangminNa/html_css/blob/main/11_%EC%9E%85%EB%A0%A5%EC%9A%94%EC%86%8C%EB%A7%8C%EB%93%A4%EA%B8%B0/readme%EC%B0%B8%EC%A1%B0.png")

## input의 핵심, type 속성

- type의 값이 달라짐에 따라 적용할 수 있는 추가 속성의 종류도 조금씩 차이를 보인다.
- 참조 링크 https://developer.mozilla.org/ko/docs/Web/HTML/Element/Input

## 이름을 지어주세요

- input 태그에는 name 식별자를 추가할 수 있다.
- 이는 각각의 입력 항목에 대한 이름이다.
```
<input type="text" name="nickname" />
<input type="text" name="job" />

결과 -> nickname 항목에는 '유노코딩'이, job 항목에는 '프리랜서'가 입력된 상태
```

## 내용정리

- input 태그는 입력 요소를 만드는 태그이다.
- input 태그는 type 속성을 통해 형태와 입력 값 유형을 결정한다.
- type 값에 따른 사용 방법이 다양하다(웹페이지 내에서의 역할, 추가 속성 등)
- name 속성으로 input 요소를 구별할 수 있다.