# 5. display 속성 & border 속성 
인라인이냐 블록이냐 - display & border

## 블록 레벨 요소 vs 인라인 요소

- 블록 레벨 요소 : 자기가 속한 영역의 너비를 모두 차지하여 블록을 형성
- ex) div, p, h1
- 인라인 요소 : 자기에게 필요한 만큼의 공간만 차지한다.
- ex) span, a

## display

- display 속성은 요소를 블록과 인라인 요소 중 어느 쪽으로 처리할지 정의한다.
```
/*
블록 레벨 요소인 div 요소를 인라인으로 처리하고 싶다면
div{display : inline;}
*/

/*
인라인 요소인 a 요소를 블록 레벨로 처리하고 싶다면
div{display : block;}
*/
```
## display 속성값

- display에는 미리 정의되어 있는 키워드를 속성값으로 지정한다.
- inline : 인라인으로 처리한다.
- block : 블록 레벨로 처리한다.
- inline-block : 인라인으로 배치하되, 블록 레벨 요소의 추가할 수 있도록 처리한다.
- none : 디스플레이(표시)하지 않는다.
- 기타 등등

## border 속성

- border 속성을 사용하면 요소가 차지하고 있는 영역에 테두리를 그릴 수 있다.
- border 속성에는 속성값으로 테두리의 두께, 모양, 크기 등을 함께 지정할 수 있다
- 이러한 속성을 '단축속성'이라 한다.
```
span{border: 2px solid green;}

두께가 2px인 직선 모양(solid)의 초록(green) 테두리를 만들어줘!
```

## border 속성의 하위 속성

- border 속성에 지정하는 값들을 따로 지정할 수도 있다.
- border-color : color 정의 방식과 동일
- border-width : thin, medium, thick 등의 키워드 또는 px, em, rem 등의 단위
- border-style : none(기본값), solid(직선), dotted(점선), dashed(긴 점선) 등

## 내용정리

- display 속성은 요소의 블록 레벨, 인라인 여부를 변경 처리할 수 있다.
- display 속성은 요소를 배치할 때 레이아웃을 결정할 때도 사용될 수 있다.
- border 속성은 요소가 차지하는 영역에 테두리를 그릴 수 있다.
- border는 여러가지 속성을 함께 정의할 수 있는 '단축속성'이다.
- border의 하위 속성은 border-style, border-width, border-color이다.
