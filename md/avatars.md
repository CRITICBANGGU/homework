# 2주차 과제 (Float, Flex layout 실습)

## HTML 구조

- 같은 요소가 하나로 줄지어져 있기 때문에 list tag
- 순서가 상관 없기 때문이 unordered list tag
- section을 사용하여 flex layout과 float layout을 구분함.
- 리스트 요소에 사용자 사진을 표시하는 img tag와 online 여부를 표시하는 span tag를 사용함.

## CSS

- overflow : hidden을 사용하여 ul안에 있는 li요소만 한줄로 표시함.
- float속성을 inline-start를 사용하여 시작점부터 float되도록 설정함.
- position : relative와 absolute 속성을 사용하여 online 여부 뱃지를 위치시키킴
- figma에 뱃지 border가 있기 때문에 속성 추가함.
- 요소간 간격이 20px이기 때문에 margin 을 10px로 지정함.
- active, unactive 클래스를 구분하여 사용중일 때 색상과, 사용중이지 않을 때 색상을 구분함
