# 7. 박스모델 2편 margin padding 다루기
상하좌우 여백 다르게 지정하기 - 박스모델 2편

## padding 과 margin

![이미지](https://github.com/KangminNa/html_css/blob/main/CSS/7_%EB%B0%95%EC%8A%A4%EB%AA%A8%EB%8D%B82%ED%8E%B8_margin_padding_%EB%8B%A4%EB%A3%A8%EA%B8%B0/img.png?raw=true)

## 다양한 경우의 수

- 여백은 상하좌우 네 개의 면에 존재
- 작성자는 각 면에 개별적으로 두께를 정의 가능
- 이를 위해 두 가지 방법 사용
1. 하위 속성 정의
2. 여러 값을 한 번에 정의

## 하위 속성 정의하기

- 상하좌우 여백을 정의할 수 있는 개별 속성들이 있다.
![이미지2](https://github.com/KangminNa/html_css/blob/main/CSS/7_%EB%B0%95%EC%8A%A4%EB%AA%A8%EB%8D%B82%ED%8E%B8_margin_padding_%EB%8B%A4%EB%A3%A8%EA%B8%B0/img2.png?raw=true)
- margin에도 동일한 접미사를 붙여 개별 정의할 수 있음

## 여러 값을 한 번에 정의하기

- padding과 margin은 네 면의 여백에 대한 단축속성이다.
![이미지3](https://github.com/KangminNa/html_css/blob/main/CSS/7_%EB%B0%95%EC%8A%A4%EB%AA%A8%EB%8D%B82%ED%8E%B8_margin_padding_%EB%8B%A4%EB%A3%A8%EA%B8%B0/img3.png?raw=true)

## 내용정리

- 여백은 상하좌우 네 면에 존재하는 영역
- 상하좌우 개별 속성을 사용하면 여백 두께를 개별 정의할 수 있다.
- padding과 margin 속성에 여러 면의 여백을 함께 정의할 수 있다.
- 어떤 방법을 사용할지는 사용자(개발자) 마음
- 하지만 무조건 개별 속성을 사용하여 개발 하는 것이 좋음.(가독성 부분)
