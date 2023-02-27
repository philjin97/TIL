## Positioning 
#### CSS Position = Normal Flow에서 요소를 끄집어내서 다른 위치로 배치하는 것
#### Normal flow = CSS를 적용하지 않았을 경우 웹페이지 요소가 기본적으로 배치되는 방향 
#### Position 유형 
#### static, relative, absolute, fixed, sticky 
#### static: 기본값, Normal Flow에 따라 배치
#### relative: Normal Flow에 따라 배치, 자기 자신을 기준으로 이동, 요소가 차지하는 공간은 static일 때와 같음
#### absolute: Normal Flow에서 제거, 가장 가까운 relative 부모 요소를 기준으로 이동, 문서에서 요소가 차지하는 공간이 없어짐 
#### fixed: Normal Flow에서 제거, 현재 화면 영역을 기준으로 이동, 문서에서 요소가 차지하는 공간이 없어짐 
#### sticky: Normal Flow에 따라 배치, 가장 가까운 block 부모 요소를 기준으로 이동, 요소가 특정 임계점에 스크롤될 때 그 위치에서 고정됨, 만약 다음 sticky 요소가 나오면 다음 sticky 요소가 이전 sticky 요소의 자리를 대체