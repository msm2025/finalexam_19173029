# 20201201 박스오피스 top10 정보 보기

## 프로젝트 구현 방법
### activity_login
어플의 전체적인 컬러는 KOBIS의 로고 컬러와 비슷한 푸른 컬러들을 사용하였고, 중간에 다른 컬러들도 볼 수 있게 다양한 컬러가 있는 이미지를 사용했다.
먼저 로그인 페이지에서 로그인 버튼을 아이디와 패스워드 부분을 orientation를 사용하여 아래로 이동시켰다.
로그인 버튼을 꾸미기 위해 java>res>drawable에서 button_background.xml을 만들어 모서리를 둥글게하고 버튼 색을 변경하였다.

그리고 EditText 아이디 부분에 hint를 사용하여 아이디에 적을 수 있는 것 두가지 방법을 적어두었다.
마지막으로 로그인창에서 없어서 안될 회원가입 텍스트와 비밀번호 찾기 텍스트를 넣었고, 회원가입 텍스트는 bold와 다른 컬러를 사용하여 강조하였다.

### activity_main
orientation(horizontal)을 사용하여 상단에 로고와 검색 버튼 이미지를 삽입하였고, EditText의 검색창과 검색Button 또한 orientation(horizontal)을 사용하여 기존과 배치를 다르게 하였다.
마지막으로 리사이클러뷰로 추출되는 정보의 제목과 같은 것이 없어 이를 만들기 위해 TextView를 사용하여 어떤 것을 추출하는지 볼 수 있게 하였다. 

### movie_item
기존에 추출했던 데이터를 포함하여, rank, rankInten, rankOldAndNew, movieNm, 
openDt, salesAmt, salesChange, salesAcc, audiCnt, audiChange, audiAcc, scrnCnt, showCnt을 사용하여 더 많은 정보를 얻을 수 있도록 하였다.
그중에서도 랭킹진입여부, 순위증감, 순위를 제목근처에 두어 바로 볼 수 있도록 하였고, 스크린과 상영횟수 또한 같은 줄에 두었다.
마지막으로 관객수와 매출액에 padding을 주어 간격을 넓혀주었고, 각각의 일일 관객수와 매출액은 한눈에 볼 수 있도록 색을 다르게 지정하였다.

그동안 배운 것들을 활용하여 배치를 깔끔하게 하고자 하였다. 또한 한눈에 볼 수 있도록 하기위해 심플한 아이콘이나 이미지를 넣었고, 통일된 느낌을 주기위해 전체적으로 푸른 컬러를 사용하였다.
