# <img src="./img/puppeter_icon.png" height="40px" /> Puppeteer Crawler
## 필요한 라이브러리
필요한 Node js 라이브러리 다음과 같습니다.
```
npm install express
npm install puppeteer
npm install mysql
```
## 데이터베이스
크롤링된 데이터를 데이터베이스에 저장하니까 데이터베이스는 crawling_data.sql 파일을 이용하고 가져올 수 있습니다.
## 실행 방법
```
cd Nodejs_Crawling
node crawler.js
```
## 스크린샷
### 실행콘솔
<img src="img/execution_screen.png" />
### DB 슥크린샷
<img src="/img/db_screenshoot.png" />
## 기타
<ul>
  <li>앱은 지금 쿠팡 쿠롤링 하고 있습니다.</li>
  <li>원래, 쇼피와 네이버쇼핑을 지원할 계획이 있었는데 시간이 부족해서 쿠팡까지만 했고 네이버쇼핑과 쇼피를 disable오로 버꿨습니다.</li>
</ul>
