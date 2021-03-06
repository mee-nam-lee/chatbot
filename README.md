# Chatbot 샘플

## Custom Component 

```shell
cd bot-start
npm install
node index.js
```

### Simple Custom Component Test
```shell
curl -H "Content-Type: application/json" -d @./spec/store.req.json localhost:4000/components/ListStores
```

### oracle database 연계 샘플 (oracledb.js)

oracle chatbot과 Autonomous Data Warehouse 연계 샘플 입니다. 
상세 가이드는 다음을 참고 하세요.

[Digital Assistant(챗봇)과 Autonomous Data Warehouse(ADW) 연계하기](https://mee-nam-lee.github.io/chatbot/2019/01/21/chatbot_adw.html)

### Conversation Message Model 이용 예 (layout.js)

[챗봇 Layout 예제](https://mee-nam-lee.github.io/chatbot/2019/%EC%B1%97%EB%B4%87-Layout/)

### Oracle Content and Experience(CECS)와 연동 - 챗봇에서 CECS의 컨텐츠 검색하기 예 (searchcecs.js)

[Digital Assistant(챗봇)와 Content and Experience(CECS) 연동하기](https://mee-nam-lee.github.io/chatbot/2019/chatbot_cecs/)

### Custom Component Package
Oracle Node.js SDK


## Oracle Chatbot Webview Sample

* Using
  - Express
  - EJS

* Run Project
```shell
cd bot-webview
npm install
node index.js
```

* 테스트 URL : http://localhost:3000/webview/booking?param1=lg&callbackUrl=c

- [챗봇 Hands-on Lab (9) - WebView 구현 및 챗봇 연계](/chatbot/2019/챗봇-Hands-on-Lab_9/)
