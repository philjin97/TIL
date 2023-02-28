## Flexible box 
#### 요소를 행과 열 형태로 배치하는 1차원 레이아웃 방식 
#### interactive layout 
#### flex container - display, flex-direction, flex-wrap, justify-content, align-items, align-content 
#### flex item - align-self, flex-grow, flex-shrink, flex-basis, order
#### display: flex => flex item은 행으로 나열 
#### flex-directionL column; flex item이 나열되는 방향을 지정
#### flex-wrap: wrap; 다른 행에 배치할지 여부 설정 
#### justify-content: center; 주축을 따라 
#### align-content: center; 교차축을 따라 
#### align-items: center; 교차축을 따라 
#### align-self: 교차축을 따라 
<br/>

#### 목적에 따른 분류 
#### 배치 설정: flex-direction, flex-wrap 
#### 공간 분배: justify-content, align-content 
#### 정렬: align-items, align-self 
#### justify - 주축, align - 교차축 
#### flex-grow: 남는 행 여백을 비율에 따라 각 flex item에 분배 
#### flex-grow: 1; flex-grow: 2; flex-grow: 3; 
#### flex-basis flex item의 초기 크기 값을 지정 
<br/>

#### 반응형 레이아웃 
#### flex-wrap을 사용해 반응형 레이아웃 작성 
#### flex-wrap: wrap; 