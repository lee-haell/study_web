# 생활코딩 - WEB<br>

<a href="https://it-study-site.super.site/web/%ec%83%9d%ed%99%9c%ec%bd%94%eb%94%a9-web1-html-internet" target="_blank">1. WEB1 - HTML & Internet</a><br>
<a href="https://it-study-site.super.site/web/%ec%83%9d%ed%99%9c%ec%bd%94%eb%94%a9-web2-css" target="_blank">2. WEB2 - CSS</a><br>
<a href="https://it-study-site.super.site/web/%ec%83%9d%ed%99%9c%ec%bd%94%eb%94%a9-web2-javascript" target="_blank">3. WEB2 - JavaScript</a><br>

<br>

My Computer - 코드를 작업한 내 컴퓨터<br>
Hosting - 서비스를 대신해서 제공하는 호스팅<br>
Viewer - 내 웹 사이트를 방문하는 방문자<br><br>

1. 내 컴퓨터로 웹 사이트의 기반이 되는 코드(ex. index.html)를 작성한다.
2. 호스팅 업체에 내 코드를 업로드하면, 코드가 웹 포스팅으로 업로드 된다.
3. 호스팅 업체는 웹 포스팅에 설치되어 있는 웹 서버를 활성화한다.
4. 호스팅 업체는 컴퓨터에 도메인 이름을 부여한다.
5. 방문자가 해당 도메인으로 접속하면, 웹 서버가 코드(ex. index.html)를 읽는다.
6. 웹 서버는 방문자에게 코드 파일을 전송한다.
7. 방문자의 컴퓨터에 해당 웹 페이지가 표시된다.

<br>

![Untitled](https://github.com/user-attachments/assets/17a7e6c1-3188-4cda-972a-ea0f1a7802f4)

<br><br>

<b>원시웹</b>
<hr>
Q. 인터넷과 웹은 같을까, 다를까?<br>
A. 다르다.<br>
인터넷 = 도시 / 운영체제<br>
웹 = 도로 위 달리는 자동차 / 운영체제 속 프로그램<br><br>

Q. 웹의 고향은?<br>
A. 스위스<br>
스위스 제네바에는 유럽 입자 물리 연구소가 있음.<br>
인류의 현미경과 같은 존재.<br>
1980년, 팀 버너스 리가 비정규직의 프로그래머로 취직.<br>
Enquire라는 프로그램을 만듦.<br>
10년 동안 웹의 중요한 전신들을 만듦.<br>
1990년 최초로 웹 페이지를 만드는 편집기를 만듦. <br>
(*primitive web : 원시웹)<br><br>

Q. 인터넷이 동작하는 원리<br>
A. 웹 브라우저 & 웹 서버를 팀 버너스 리가 만듦.<br>
1. 웹 브라우저에 [info.cern.ch/index.html]을(http://info.cern.ch/index.html%EC%9D%84) 검색<br>
2. 웹 브라우저는 인터넷을 통해 전기적인 신호를 보냄.<br>
3. 그 신호에는 '나는 index.html 파일을 원합니다.' 라는 정보가 담겨 있음.<br>
4. info.cern.ch에 해당되는 컴퓨터에 설치된 웹 서버라는 프로그램이 하드디스크에서 index.html 파일을 찾아서 웹 브라우저가 설치되어 있는 컴퓨터에게 다시 보내줌. 전기적 신호, 코드로 바꿔줌.<br>
5. 웹 브라우저가 설치된 컴퓨터에 index.html 파일이 도착함. 도착한 코드를 웹 브라우저가 읽어서 해석, 화면에 표시<br><br>

<br>
<b>인터넷을 여는 열쇠, 서버와 클라이언트</b>
<hr>
Q. 웹 브라우저가 깔려 있는 컴퓨터는 정보를 요청하고 있을까, 응답하고 있을까?<br>
A. 정보를 요청하고 있다. 따라서 request<br>
반대로 웹 서버가 설치된 컴퓨터는 정보를 응답하고 있기 때문에 response이다.<br><br>

Q. 이 2대의 컴퓨터를 각 역할에 따라 맞게 부르고 싶어했다. 따라서 붙인 이름은?<br>
A. 자본주의 사회에서 가장 자주 사용되는 관계, client와 server<br>
게임하는 컴퓨터나 휴대폰을 game client, 그 게임 회사에 있는 서버가 game server라고 할 수 있다.<br><br>

Q. 웹 브라우저는 물질일까?<br>
A. 웹 브라우저는 논리적인 시스템, 추상적인 대상<br>
하지만 우리는 매일 웹 브라우저를 쓰고 얘기하기 때문에 물질이라고 생각함.<br>
웹 서버는 웹 브라우저와 같이 인터넷에서 다운로드 받아서 컴퓨터에 깔고 사용하면 되는 프로그램.<br> 
우리가 써본 적이 없기 때문에 추상적으로 느끼는 것.<br><br>
