# CoronaView

- 사용자에게 코로나 관련 편의를 제공하고 다양한 Open API를 사용해 보기 위해 제작

- 2020.07.08 - 2020.07.24 (약 2주)
- 개발인원 : Backend 2명







# Development Environment


- Spring 4.0, Apache Tomcat 9.0, Tiles3, BootStrap
- Java, Jquery, GitHub, MVC Pattern
- **Open API** - Corona19-API, Youtube Data API, Naver News API, Kakao Map API







# View

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/CoronaView-gif.gif?raw=true"  width="800" height="400" /></left>






# main

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git1.png?raw=true"  width="400" height="400" /></left>

- **숫자 자동증가 애니메이션**

jQuery의 함수를 작성하여 웹 페이지가 처음 로드될 때 숫자가 0부터 각 수치대로 자동증가 됨

- **스크롤 애니메이션**

부트스트랩 "page-scroll" 클래스를 사용하여 버튼을 누르면 각 페이지로 스크롤

- **더보기 버튼**

버튼을 클릭하면 출력되지 않은 모든 지역이 출력되고 숨기기 버튼으로 변경 됨






## News

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git2.png?raw=true" width="450" height="450" /></left>

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






## Youtube

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git3.png?raw=true" width="450" height="450" /></left>

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






## 확진자 상세 정보

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git9.JPG?raw=true" width="900" height="150" /></left>






## 입국제한조치 현황

<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/git7.JPG?raw=true" width="500" height="300" /></left>







## GITHUB project


GITHUB project 일정 관리 시스템을 이용해 To do, Doing, Done를 통한 일정관리


<left><img src="https://github.com/jeongsoha/Corona_View/blob/master/src/main/webapp/resources/images/github.png?raw=true" width="500" height="300" /></left>


