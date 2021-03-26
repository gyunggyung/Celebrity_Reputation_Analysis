<h1 align="center">Celebrity Reputation Analysis</h1>

인터넷 기사, 블로그 글, 트위터, 페이스북 등에 있는 유명인들에 관련된 글을 크롤링하여 유명인들의 평판을 분석하는 프로젝트입니다.  
> 참고 : https://github.com/gyunggyung/Reputation_analysis

## 개발파트
한 명 당 메인 1, 서브 1~2로 다양한 분야를 체험해볼 수 있습니다.

### Front end
- 역할 : 분석한 데이터들을 Back end 와 함께 웹페이지 표시하는 부분입니다.
- 수행내용 : Back end에게 받은 데이터로 그래프 제작, 화면 디자인 등  
- 사용언어 : HTML, CSS, JavaScript, jQuery ...

### Back end, DB
- 역할 : DB 구축 및 데이터를 저장, 관리를 하며 
- 수행내용 : 크롤링과 데이터 분석 쪽에서 나온 데이터를 DB에 저장, 검색 기능 구현, DB 디자인 등
- 사용언어 : SQL, ...

### 크롤링
- 역할 : 기사, 블로그, 트위터, 페이스북 등에서 유명인과 관련된 글을 크롤링하는 부분입니다.
- 수행내용 : [크롤러](https://ko.wikipedia.org/wiki/%EC%9B%B9_%ED%81%AC%EB%A1%A4%EB%9F%AC) 제작, [데이터 정제](http://opendatahandbook.org/glossary/ko/terms/data-cleaning/), DB에 데이터 저장 등
- 사용언어 : Python, SQL, ...

### 데이터 분석
- 역할 : 크롤링한 데이터를 기반으로 유명들의 평판을 분석하는 부분입니다.
- 수행내용 : 평판 분석 알고리즘 제작 및 실행, 분석한 내용을 DB에 저장 등
- 사용언어 : Python, ...

## 개발 순서
1. 페이지 디자인 구체화, 평판 분석을 할 유명인 정하기 및 크롤링할 데이터 정의(~뉴스, 트위터 등등), DB 디자인

2. 페이지 개발 시작, 크롤러 제작, 데이터 분석 알고리즘 제작

3. DB 연동, DB에 크롤링한 데이터 저장

4. 페이지 1차 완료, 호감도 분석 및 DB에 저장

5. 검색 기능 구현(원하는 유명인을 볼 수 있게)

## 예제

- [Front end 프로토타입](https://github.com/gyunggyung/finger)  
>제가 제작한 간단한 페이지 입니다. (Front end)

- [정치인 호감도 분석](https://github.com/gyunggyung/Reputation_analysis)  
>서울대학교 빅데이터 아카데미에서 진행한 간단한 평판분석 프로젝트입니다. (크롤링, 데이터 분석)

- [그래프 제작 예제](https://www.zingchart.com/)  
>(Front end)

- [긍정 부정 분석](https://www.lucypark.kr/docs/2015-pyconkr/#1)
>네이버 영화 리뷰를 기반으로 긍부정을 알아내는 예제. (데이터 분석)
>※ 상당히 어려움

- 
