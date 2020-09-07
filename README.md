# Landing Page Clone Practice 

**매일 클론코딩** 

>

 - [x] 기본 HTML/CSS/JAVASCRIPT/JQUERY 사용 (한 파일에 저장)
 
 - [x] No CSS FRAMEWORK
 
 - [x] 바쁘더라도 부분적으로 만들기 
 
 - [x] 만들기 어려운 부분은 인터넷을 참고하되 이해하고 넘어가기
 
 - [x] 클론하면서 새로 알게된 기술이나 추후에 쓸만한 조합, 색감, 모양 등 노트

> 

  

## 시작 


 
**1)** 8/31/2020 - Microsoft (영문)

    Flexbox 와 Grid를 복습할수있었다. 딱히 막혔던 곳은 없음 

**2)** 9/1/2020  - 아프리카TV (글로벌) 

	처음 구상할시 재활용할만한 class를 우선으로 생각하고 의미있는 이름을 부여해야겠다.
	다음 클론부턴 자주 쓰이는 색은 root색으로 지정하고 재활용할것. 
  
[FLEXBOX 를 사용해 Input 안에 submit 버튼 넣기](https://stackoverflow.com/questions/15314407/how-to-add-button-inside-input)
	

 - border outline 색: #e5ebf3; 

> 너무 튀지도 않고 적당한 경계선. 살짝 섞인 파랑

**3)** 9/2/2020  - 구글 

	직접적으로 쓰진 않았지만 :focus-within 이란걸 알게됨.
	<form>의 <input> 필드 중 하나가 포커스된 경우 전체 <form>을 강조해야 할 때 유용하게 쓰일듯하다.
	ex) 보통 input을 바로 쓰지않고 wrapper에 감싸고 이미지나 아이콘과 같이 쓸때가 많은데 wrapper를 input인것처럼 보이게할수있을듯.

**4)** 9/3/2020  - BBQ치킨

	Grid를 최대한 활용할수 있었던거 같다. 내일은 메뉴나 슬라이더 이펙트를 구현해보려고 한다.	

- #e9dad9 (핑크계열), #f7f0e8 (옅은 오렌지), #eaeaea (옅은 회색) 이 세가지 색을 사용해 전체적인 레이아웃을 짜보는것도 괜찮을거같다

**5)** 9/4/2020  - BBQ치킨 슬라이더

	항상 슬라이더는 만들어 쓰기보다는 slick같은 라이브러리를 사용했는데 막상 만들어보니 생각보다 손이 많이 갔다. 

[유튜브 강좌 참고](https://www.youtube.com/watch?v=0wvrlOyGlq0)

- radiobox 사용시 보통 input 자체 css를 변경하곤했는데 radiobox는 숨겨두고 label을 담고있는 네비게이션을 따로 만들어 쓰면 훨씬 자유로운 스타일링이 가능할수 있을듯.

**5)** 9/5/2020  - Netflix (part1)

	넷플릭스 이외에도 자주쓰이는 점보트론(jumbotron) 레이아웃을 만들어봤다. 가상클래스 배경에 linear gradient 와 radial gradient를 한번 줬으나 중간에 글씨가 잘 보이지 않아 jumbotron 자체에 boxshadow를 한번 더 넣어줌. 

**5)** 9/6/2020  - Netflix (part2)

	넷플릭스 랜딩페이지의 하단부분과 아코디언 방식의 정보탭.  	

**6)** 9/7/2020  - Netflix (part3)

	모바일에서도 정상적으로 나오도록 수치 변경 및 flex-wrap 사용해 레이아웃 변경. flex-wrap wrap-reverse는 많이 써보지 않았는데 html의 순서가 다름에도 모바일 버전에서는 똑같이 나오게 하고 싶을때 유용한거같다.