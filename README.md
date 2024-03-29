# Landing Page Clone Practice 

**매일 클론코딩** 

사용된 리소스는 클론 사이트 대상의 소유주에게 있으며, 저작권 침해 의도는 없이 학습 용도로만 사용되었습니다.


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

**7)** 9/8/2020  - Bootstrap 

	자주 사용하는 부트스트랩 프레임워크를 부트스트랩을 안쓰고 만들어보았다. 점점 속도가 붙는거 같다.

**8)** 9/9/2020  - Youtube (part1)

	유튜브의 기본 레이아웃을 잡아봤다 (반응형 x). 생각보다 아이콘 작업하는데 시간이 많이 걸린거같다. 아이콘이 자주 쓰이는 웹은 <i>태그에 텍스트를 넣어두고 한꺼번에 교체해줘야겠다.

**9)** 9/10/2020  - Youtube (part2)

	1000, 700, 500 에 반응하도록 변경.

**10)** 9/11/2020  - NPM 공식사이트 (part1)

	전체적인 레이아웃을 잡는데 article, section, nav등 시멘틱 마크업을 주로 사용함. 

[시멘틱 마크업의 종류/중요성](https://www.daleseo.com/html-semantic-markup/)

**11)** 9/12/2020  - NPM 공식사이트 (part2)

	세부적인 수치 (max-height, font-size등 변경) + 반응형 추가. 폰트사이즈를 px로 작성해 하나하나 다 바꿔줘야했음. 다음부턴 em, rem 만 사용해서 root값만 바꿔줄 예정.

**12)** 9/13/2020  - NAVER (part1)

	네이버의 nav 부분과 footer 부분 레이아웃을 잡아봤다. font-size는 rem으로 작성했고 아이콘 부분은 세부적인 구현을 위해 font-awesome 대신 네이버 svg아이콘 모음을 배경으로 지정해 필요한 부분을 position으로 지정해 잘라 써보았다.
	보통 아이콘은 프레임워크 아이콘모음이나 이미지를 쓰곤했는데 svg는 벡터아이콘이라 깨짐도 없으니 앞으로도 자료가 있다면 이 방법을 애용해야겠다.


**13)** 9/14/2020  - NAVER (part2)

	Grid Cell을 사용해 main의 레이아웃을 잡아봤다. 세부적인 디자인은 (박스 내부의 버튼이나 글자 등) 다 치려면 시간이 오래걸릴거같아 스크린샷으로 대체했다.


**14)** 9/15/2020  - Instagram
**15)** 9/16/2020  - Instagram (part2) 
**16)** 9/17/2020  - Instagram (part3) - 반응형 추가

**17)** 9/18/2020  - FastCampus (코딩스쿨) (part1) - 네비게이션 및 헤더추가

	한달뒤 다니게 될 코딩스쿨을 클론 해보았다.

**18)** 9/19/2020  - FastCampus (코딩스쿨) (part2) - 카드, 배너 추가 
**19)** 9/20/2020  - FastCampus (코딩스쿨) (part3) - 카드 html css 추가 및 전체 웹 반응형 추가

**20)** 9/21/2020  - Github - navbar, tab 추가

	자주 쓰이는 sticky navbar를 구현해봤다. 항상 --webkit (파이어폭스, 인터넷 익스플로러 지원) 다음에 position: sticky를 지정할것!

**21)** 9/22/2020  - Github (part2) - 전체적인 레이아웃 완성
**22)** 9/23/2020  - Github (part3) - 모바일 반응 추가

**23)** 9/24/2020  - Microsoft Learn (part1) - 네비게이션 및 헤더 추가
**24)** 9/25/2020  - Microsoft Learn (part2) - 카드추가 및 모바일 반응 추가

**25)** 9/26/2020  - MongoDB (part1) - sticky 네비게이션 및 헤더
**26)** 9/27/2020  - MongoDB (par2) - svg추가 폰트, 세부레이아웃 조정 및 모바일 반응 추가

**27)** 9/28/2020  - Melbourne University (part1) 

		대학시절 자주쓰던 모교 웹 클론을 시작 해보았다. 내용이 많아 헤더를 필요한 중요한 부분만 구현해보려고한다. 
		header안에 text가 화면 크기에 따라 위치 변경을 해야하기 때문에 부모요소에 relative를 주고 text-container 요소에 
		left: calc(50% + 3.5rem) 값을 줬다.

**28)** 9/29/2020  - Melbourne University (part2) 

		card부분 추가 및 hover 이펙트. transition 과 transform 이용해 매끄러운 이펙트 구현.


**29)** 9/30/2020  - Melbourne University (part3) 

		모바일 반응 추가 (카드 모양, 네이게이션, 폰트 크기)

**30)** 10/1/2020  - Apple (part1)

		보통 nav를 만들때 ul 이나 li에게는 클래스를 주지않고 child selector로 css를 입혔는데 (.navbar > ul > li) 가독성이 많이 떨어지고 코드 수정에 어려움이 있읅수 있다는 지적을 받아
		앞으로는 nav-link nav-item 이런식으로 클래스를 주려고한다. 이런 구조는 bootstrap 같은 css framework에서도 자주 보였던거 같다.
		
**31)** 10/2/2020  - Apple (part2) 

		애플 제품 이미지 배너들을 구하기가 어려워 그냥 배경색만 입혔다. 소스를 구하기가 어려워 모바일 반응만 추가해주고 빠르게 마무리했다.

**32)** 10/3/2020  - Bang Oflusen (part1) 

		배경화면에 비디오가 자동 실행되는 웹을 클론해보았다.

**33)** 10/4/2020  - Bang Oflusen (part2) 

		모바일 반응 및 일정량 스크롤시 element의 opacity가 감소하며 결국엔 사라지도록 jquery추가 (scrollTop 사용)

**34)** 10/5/2020  - Udemy  네비게이션 추가
**35)** 10/6/2020  - Udemy  (part2) 헤더 섹션 추가
**36)** 10/7/2020  - Udemy  (part3) 카드 및 모바일 반응추가

**37)** 10/8/2020  - NIKE (part1) 네비게이션 + 메인 섹션 
**38)** 10/9/2020  - NIKE (part2) 모바일 반응 추가


10/10/2020 ~ --- 패스트 캠퍼스 수강으로 잠시 중지 ----




				









	





	

	
