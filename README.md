# Front-end-interview

## 流程：
- 面試官自我介紹，名字、負責產品、職缺期待
- 請面試者針對剛剛的介紹自我推薦
- Q&A

## 觀察重點：
- 想不想做front-end
- 喜不喜歡學新東西
- 跟team裡面的tone合不合
- 基本skill夠不夠

## 暖身問題：
- 在前份工作負責什麼角色？可以介紹一個你最有成就感的專案嗎？
- 你期待做什麼、學什麼？
- 最近有看什麼新技術嗎？有心得嗎？有實作嗎？有Open source可分享嗎？
- 可以寫現場寫字串反轉嗎？
- 寫code最讓你感興趣的部分是什麼？

## 情境題：(目標對象：2 year experience above)
### 效能：
- 一個放文章的網站需要常常Query首頁50篇文章，你會怎麼做？
- 有沒有遇過被抱怨網站loading速度慢？情況是？如何解決？ 你會從哪看？
- 網站靜態資源如何優化？怎麼Bundle？Bundle成幾隻？怎麼決定？Bundle之後怎麼debug?
- browser cache怎麼實做? 你知道哪些方法？
- 靜態檔案被cache但你改版需要更新怎麼辦? 版號? 還有其他方式嗎?
- 如果有大約500筆資料，要在網頁上用分頁顯示你會怎麼做？
- 5萬筆資料呢?
- Memory cache哪時候放進去？這樣會犧牲啟動的時間，開發就會變慢怎麼辦？
- Application有多台server時cache怎麼辦？放DB的話誰來Update cache?
- 遇過DB拉資料很慢嗎？你當時怎麼查？怎麼知道慢在網路還是query？
- CDN是幹嘛用的？

### SEO：
- 你網站都怎麼做呢？MVC? 使用Template engine / SPA + webpai / Template engine + webapi?
- Ajax拿資料對SEO的影響？
- SEO的重點是什麼？你有做過哪些SEO優化？ 用過什麼工具？
Meta data, key word, title, RWD, content, server render, routing, url rewrite, canonical url, user experience, robots.txt
- 網站maintenance的時候爬蟲還是會來爬資料怎麼辦？

### Session/Cookie
- 它們是什麼？如何運作？
- 常常使用到的使用者資料應該存在哪裡？

### Testing
- 寫過什麼語言的testing呢？
- 你要測試的function會call updateDB怎麼處理？
- TDD是什麼？哪時候會用到？為了寫TDD你有用過什麼Design pattern嗎？
- 先寫測試再寫程式碼和先寫程式碼在測試有什麼不一樣？
- BDD呢?
- E2E用過什麼呢?

### 資料分析
- 使用GA的目的？用過GA蒐集自定義資料嗎？怎麼做？
- 使用過ELK Stack嗎？

### Design
- 如果你要把每個request的input/output log起來你會怎麼做？
- Interface幹嘛用的，好處是？

### DevOps
- Devops是什麼？
- 使用過CI/CD tool嗎？好處是什麼？
- 用過cloud service嗎？好處是什麼？

### Debugging
- 如果網頁上某個使用者的訂單資料不見了你會從哪裡開始看？
- 10台Server log怎麼查？

### Advance
- 如果三個application, website, mobile, mobileapp都需要跟你的api拿一樣的資料，但是mobileApp先改版其中一欄位需要不一樣的資料怎麼辦？
- 做過realtime app嗎？從後台發message給一個使用者andy怎麼做？我怎知道andy是mapping到哪個connectionID？若mapping存在server上，有多台server怎麼知道mapping？

### Coding
#### Javascript
- A domain client side 要去 B domain webapi拿資料怎麼拿？有什麼限制嗎？如何突破？
- Closure是什麼, Array map是什麼reduce是什麼，又等於linq的什麼？
- 寫過TS嗎？TS的好處?
- 前端Framework優缺點？
- 寫過nodeJS嗎？
- 非同步操作怎麼處理？如果我request A.json，用A.json來呈現部分畫面，怎麼做？如果要讀完A.json和B.json呢？如果A和B有一個操作失敗我就不呈現呢？
- Defer/Promise是什麼？Resolve Reject是什麼？你在哪邊有用過Promise呢？

#### CSS
- 用過CSS framework嗎？
- RWD原理是什麼？
- CSS簡單切版？
- span在block裡面如何垂直置中? 
- span若超過parent寬度會怎麼樣？強制不換行怎麼做？

### Reference
https://github.com/h5bp/Front-end-Developer-Interview-Questions
