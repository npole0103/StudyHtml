# HTML

HTML SUMMARY

---
## Tag

강조 Strong : `<strong>내용</strong>`

밑줄 UnderLine : `<u>밑줄</u>`

제목 headings h1 ~ h6 : `<h1>제목</h1>`

줄바꿈 line break : `<br>`  
(`<br>` tag는 따로 감싸주지 않음)

단락 paragraph : `<p>단락나눔</p>`

CSS : `<p style="margin-top:100px;">`

이미지 태그 img : `<img src="coding.jpg" width="100%">`

속성 : 태그가 태그 이름만으로 정보가 부족할 때 속성을 사용함.
위 이미지 태그에서 `"coding.jpg"` `width="100%"` 이런 것들을 속성(Attribute)이라 부름. 속성 내 순서가 바껴도 코드에 영향을 주지 않음.

부모태그 자식태그 : `<parent> <child></child></parent>`

Unordered List 순서가 없는 리스트 : `<ul>리스트</ul>`  
(ul은 li의 부모 태그)

Ordered List 번호가 붙는 리스트 : `<ol>리스트</ol>`
(ol은 li의 부모 태그)

List : `<li>리스트</li>`

Title 타이틀 설정 : `<title>타이틀</title>`

meta 한글 설정할 때 : `<meta charset="utf-8">` 

head 바디를 설명하는 태그 : `<head>바디 설명</head>`

body 본문 : `<body>본문</body>`

html 소스 : `<html>html소스</html>`

html 문서 표시 : `<!doctype html>`

anchor 링크 태그 : `<a href="링크"></a>`

링크 새 탭 : `<a href="링크" target="_blank"></a>`

링크 툴팁/말풍선 : `<a href="링크" title="내용"></a>`

---
## etc

[전 세계 모든 웹 분석 태그 사용 빈도 통계](https://www.advancedwebranking.com/html)

[Unsplash.com 저작권 없이 이미지 사용가능](https://unsplash.com)

통계를 기반으로 무엇을 공부해야할 지 분석한 후 공부하라

검색 엔진에게 페이지가 우선 순위가 되고 싶다면 태그를 활용해야한다  
(제목을 h1태그로 안하고 글자 굵게 크기 늘린다면 검색엔진에 보여질 때 우선순위에서 제외됨. 이미지로 제목을 넣는 것 또한 마찬가지)

인터넷은 1960년 핵전쟁에서 안전한 통신을 하기 위해 개발되었다.

Web Client : Server에 Request를 보냄

Web Server : Client에 Response를 보냄

Ubuntu 기준 `sudo apt-get install apache2` 아파치 설치

호스트 네임 확인 : `hostname -I`

index.html 설정 : `/var/www/html` 안에서 `ls -al`로 확인

Public IP 공인아이피 : 인터넷에게 자신의 위치를 알리는 전 세계 하나 뿐인 고유 IP-Address를 말한다. 127대역은 루프백 주소.

- A Class / 0.0.0.0 ~ 126.255.255.255 / 시작 Bit 0000 0000 ~
- B Class / 128.0.0.0 ~ 191.255.255.255 / 시작 Bit 1000 0000 ~
- C Class / 192.0.0.0 ~ 223.255.255.255 / 시작 Bit 1100 0000 ~
- D Class / 224.0.0.0 ~ 239.255.255.255 / 시작 Bit 1110 0000 ~
- E Class / 240.0.0.0 ~ 255.255.255.255 / 시작 Bit 1111 0000 ~



Private IP 사설아이피 : 내부 네트워크 냐에서 불리우는 주소. 인터넷 상에서는 확인할 수 없고 내부 네트워크에서만 사용 가능하다.
Public IP에 NAT라는 기술을 사용하여 내부의 주소를 확장시키는 용도로 사용.

- 10.0.0.0 ~ 10.255.255.255
- 172.16.0.0 ~ 172.31.255.255
- 192.168.0.0 ~ 192.168.255.255

포트 : 네트워크를 통해 데이터를 주고받는 프로세스를 식별하기 위해 호스트 내부적으로 프로세스가 할당받는 고유한 값이다.

- 20 : FTP(data)
- 21 : FTP(제어)
- 22 : SSH
- 23 : 텔넷
- 53 : DNS
- 80 : 월드 와이드 웹 HTTP
- 119 : NNTP
- 443 : TLS/SSL 방식의 HTTP

netstat 로컬 머신에서 활성화된 네트워크 연결 표시 : `netstat -ntlp`

ip 조회 : `ifconfig`

nat brige host only

---