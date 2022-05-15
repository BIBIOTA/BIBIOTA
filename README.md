### Hi I'm BiBiOTA 👋

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=BIBIOTA&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

##  🖥 Skills:

### Backend:
    PHP (Laravel)
    Node.js
    TypeScript (NestJs)
    RDBMS (MySQL)
    Redis
    Queue

### Environment:
    Linux
    Docker(docker-compose, k8s)

### Cloud Service:
    GCP
    AWS
    Heroku

### Unit Test:
    Laravel test, jest, mocha ...

### CI-CD:
    Gitlab-CI
    GCP Cloud Build
    Drone

### Frontend:
    HTML (Pug)
    CSS (SCSS、SASS)
    Javascript(Vue.js、Jquery)

##  👨‍💻 Side Projects:

### 🏃🏻 [Irunning: Running information web site & Telegram bot (2021/8~)](https://irunning.bibiota.com/)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BIBIOTA&repo=irunning-server-api)](https://github.com/anuraghazra/github-readme-stats)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BIBIOTA&repo=irunning-node)](https://github.com/anuraghazra/github-readme-stats)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BIBIOTA&repo=irunning-client-website)](https://github.com/anuraghazra/github-readme-stats)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BIBIOTA&repo=irunning-client-admin)](https://github.com/anuraghazra/github-readme-stats)

#### About this side-project:

- 路跑天氣: 即時取得台灣各地及目前所在地(GPS Location)的即時天氣資訊及空氣品質
- 跑步紀錄: 與運動社群應用程式[Strava](https://www.strava.com/?hl=zh-TW)串接、第三方登入，取得個人的跑步紀錄
- 台灣路跑賽事: 每日更新近期的台灣路跑賽事資訊
    
  - 目前透過爬蟲技術取得[跑者廣場-全國賽會](http://www.taipeimarathon.org.tw/contest.aspx)的資料
  - 提供賽事搜尋功能
  - 可以將即將參加的路跑賽事加入Google Calender
  - Telegram bot訂閱服務，每日自動取得最新的路跑賽事資訊

#### Tech:

- Frontend: Vue.js + Vuetify UI

- Backend: Laravel 9 (PHP 8.1 + Swoole + Octane) + Node.js(爬蟲、Telegram bot)

- Database: MYSQL

- API: RESTful & GraphQL

- Environment: GCP (Google Compute Engine & Google Kubernetes Engine)

- 3rd party:
  - Strava API V3 (運動社群第三方登入及資料取得)
  - Google API (MAP & Calendar API)
  - 政府開放平台API
  - 中央氣象局API

### 💰 [外幣匯率查詢 (2021/12)](https://currency-exchanger-nestjs.bibiota.com/)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=BIBIOTA&repo=money_exchange_nestjs)](https://github.com/BIBIOTA/money_exchange_nestjs)

#### About this side-project:

- 每小時取得台灣銀行的外幣資料，可以換算新台幣轉外幣的金額

#### Tech:

- Frontend: Vue.js(Vue 3)、Tailwind
- Backend: NestJs(TypeScript)
- Database: MongoDB
- API: GraphQL
- Environment: AWS(EC2)
