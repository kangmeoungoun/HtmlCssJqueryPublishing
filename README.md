### box-sizing: border-box; -> 패딩 마진 보더 로 인해 div 크기가 늘어나도 초기값 width,height 유지
### float:left 붕떠있는상태 부모는 자식의 값을 잃어버림 그래서 부모에 overflow:hidden 먹인다.

### 인라인(inline) 요소 : 한줄에 여러개 배치 , 크기값을 가질수 없음, 상하마진은 가질수 없음
- span, a,small,big,em,u,s,del,br,q,b,strong,mark,sub,sup,video,audio
###  블록(block) 요소 : 한줄에 한개 비치, 크기값을 가질수 있음, 상하좌우 마진 가질수 있음
- div,table,figure,figcaption,caption,header,nav,fotter,section,articel,aside,p,
  blockqutoe,ul,ol,li,td,th,form,hr,h1~h6
###  인라인 블록(inline-block) 요소 - 한줄에 여러개 배치, 크기값을 가질 수 있음,상하 마진은 가질수 있음
- img,input 태그들, button, fontawesome


### 자기자신의 중앙으로 전달할때는 블록 요소는 margin:auto;
### 부모밑에 자식이 인라인 요소이면 부모한테 text-align:center;

### css로 html 가로 배치하기(float,overflow, clear, inline-block)
### 부모요소 position : relative
### 자식요소 position : absolute

### 어떤 요소든 간에 position:absolute 를 주는 순간 블록이던 인라인이더 인라인블록 속성을 가진다.
