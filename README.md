# Flex-Grid

## Flex 와 Grid의 차이점
* Flex 는 한방향 구현을 위함
* Grid 는 두방향 구현을 위함
* 전체 페이지는 grid / 부분적으로는 flex를 쓰는 경우가 많음

[Flex](#Flex)
[Grid](#Grid)

## Flex
* **Container** 에 적용하는 속성
    * container 가 block / inline-block 효과
    * `display`
        * flex
        * inline-flex
    * `flex-direction`
        * row (default)
        * row-reverse
        * column
        * column-reverse
    * `flex-wrap`
        * container 가 더 작아졌을때 item들이 떨어질것인지 그대로 팽팽한 속성을 유지할것인지
        * nowrap (default)
        * wrap
        * wrap-reverse
    * `flex-flow`
        * flex-direction 과 flex-wrap 을 동시에 사용할 수 있는 속성 (축약형)
        * flex-flow: flex-direction flex-wrap;
    
* **Item** 에 적용하는 속성

## Grid
* Grid Container `display: grid`
* Grid Track : 행 / 열
* Grid Cell : 각 칸
* Grid line : 그리드 칸을 구분하는 선
* Grid Number : 그리드 칸을 구분하는 선의 번호
* Grid Gap : 그리드 셀 사이의 간격
* Grid Area : 그리드 셀의 집합
* **Container** 에 적용하는 속성
* **Item** 에 적용하는 속성
