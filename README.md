# corona_view

- 오픈 API를 활용한 '실시간 코로나 19 국내 현황' 웹 사이트

- 2020.07.08 - 2020.07.24 (약 2주)
- 개발인원 : 2명



## Development Environment


- **Web Application Server** - Tomcat 9.0
- **Language** - JAVA, JSP, JavaScript, Jquery, HTML, CSS
- **Tool** - Spring Tool Suite4, GitHub
- **Open API** - Corona19-API, Youtube Data API, Naver News API, Kakao Map API



### GITHUB project

------

GITHUB project 일정 관리 시스템을 이용해 To do, Doing, Done을 각각 작성하여 체계적인 일정관리를 함



<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/github.png?raw=true" style="zoom:67%;" /></left>



## Web

- **숫자 자동증가 애니메이션**

jQuery의 함수를 작성하여 웹 페이지가 처음 로드될 때 숫자가 0부터 각 수치대로 자동증가 됨

- **스크롤 애니메이션**

부트스트랩 "page-scroll" 클래스를 사용하여 버튼을 누르면 각 페이지로 스크롤

- **더보기 버튼**

버튼을 클릭하면 출력되지 않은 모든 지역이 출력되고 숨기기 버튼으로 변경 됨

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git1.png?raw=true" style="zoom:50%;" /></left>



- **Corona19 API**

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git4.png?raw=true" style="zoom:50%;" /></left>

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git8.png?raw=true" style="zoom:50%;" /></left>



- **Kakao Map API**

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git5.png?raw=true" style="zoom:60%;" /></left>



- **네이버 뉴스 api**
  - 네이버 뉴스 API를 사용하여 Json 형식의 데이터로 받아옴
  - 키워드에 맞는 뉴스를 6개 가졍로 수 있게 설정
- **Json 데이터 파싱**
  - Json 형태의 뉴스데이터를 함수를 사용하여 map형태로 변환시켜 저장
  - "코로나 확진" 키워드에 관련된 뉴스의 제목, 내용, 시간의 데이터를 List에 저장
  - List에 저장시킨 데이터를 ModelAndView로 보냄
- **데이터 출력**
  - forEach 반복문을 사용하여 코로나19 NEWS 데이터를 출력
  - SimpleDateFormat을 이용해 "yyyy년 MM월 dd일" 형식으로 출력

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git2.png?raw=true" style="zoom:50%;" /></left>

- **유튜브 api**
  - 구글 유튜브 API를 사용하여 Json 형식의 데이터로 받아옴
  - 키워드에 맞는 유튜브를 5개 가져올 수 있게 설정
- **Json 데이터 파싱**
  - Json 형태의 유튜브 데이터를 함수를 사용하여 map형태로 변환시켜 저장
  - "코로나" 키워드에 관련된 유튜브 제목, 내용, 시간, 출처의 데이터를 List에 저장
  - List에 저장시킨 데이터를 ModelAndView로 보냄
- **데이터 출력**
  - forEach 반복문을 사용하여 코로나19 YouTube 데이터를 출력
  - SimpleDateFormat을 이용해 "O시간 전" 형식으로 출력

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git3.png?raw=true" style="zoom:50%;" /></left>



- 코로나19 예방 행동 수칙

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git6.png?raw=true" style="zoom:50%;" /></left>



- 확진자 상세 정보

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git9.JPG?raw=true" style="zoom:50%;" /></left>



- 입국제한조치 현황

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git7.JPG?raw=true" style="zoom:50%;" /></left>

