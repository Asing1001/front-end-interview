# Front-end-interview

## 暖身：
- 面試官自我介紹，負責工作介紹，職缺期待介紹
- 請面試者針對剛剛的內容自我推薦或是介紹相關經驗
- 前份工作負責什麼角色？可以介紹一個你最有成就感的專案嗎？
- 你的期待？你今年最想學會甚麼？
- 最近有看什麼新技術嗎？有心得嗎？有實作嗎？有Open source可分享嗎？
- 喜歡寫Code嗎？寫code最讓你感興趣的部分是什麼？
- 白板寫字串反轉

## 觀察重點：
- 態度
- 對Front-end的興趣
- 喜不喜歡學新東西
- 與Team的Tone合不合
- 基本skill夠不夠

## 技術題：(目標對象：2 year experience above)

### Session/Cookie
- 一個頁面登入之後，下一頁怎麼知道登入的狀態？
- 常使用到的使用者資料你會存在哪裡？

### 效能：
- 網站靜態資源如何優化？怎麼Bundle？Bundle成幾隻？怎麼決定？Bundle之後怎麼debug?
- 靜態檔案被cache後改版需要更新怎麼辦? 版號? 還有其他方式嗎?
- 使用過CDN嗎？
- 請介紹幾個你用過讓page loading變快的方式
- 一個放文章的網站需要常常Query首頁50篇文章，你會怎麼做？
- 有沒有遇過被抱怨網站loading速度慢？情況是？如何解決？你第一時間從哪看？
- 如果有大約500筆資料，要在網頁上用分頁顯示你會怎麼做？5萬筆資料呢?
- Memory cache哪時候放進去？這樣會犧牲啟動的時間，開發就會變慢怎麼辦？
- Application有多台server時cache怎麼辦？放DB的話誰來Update cache?
- 遇過Production DB拉資料很慢嗎？你會怎麼查？怎麼知道慢在網路還是query還是...？

### SEO：
- Ajax拿資料對SEO的影響？
- SEO的重點是什麼？做過哪些SEO優化？用過什麼工具？
Meta data, key word, title, RWD, content, server render, routing, url rewrite, canonical url, user experience, robots.txt
- 網站maintenance的時候爬蟲還是會來爬資料怎麼辦？

### Testing
- 寫過什麼語言的testing呢？
- 你要測試的function會call updateDB怎麼處理？
- TDD是什麼？TDD和先寫程式碼再寫測試有差嗎？
- 為了TDD用過什麼Design pattern嗎？ 
- BDD呢?
- E2E用過什麼呢?

### Data analysis
- 使用GA的目的？用過GA蒐集event嗎？怎麼做？
- 使用過ELK Stack嗎？

### Design
- 如果你要把每個request的input/output log起來你會怎麼做？
- 哪時候會使用Interface？

### DevOps
- Devops是什麼？
- 使用過CI/CD tool嗎？好處是什麼？
- 用過cloud service嗎？好處是什麼？

### Debugging
- 如果網頁上某個使用者的訂單資料不見了你會從哪裡開始看？
- 10台Server log怎麼查？

### Advance
- 三個application, website, mobile, mobileapp都需要跟你的api拿一樣的資料，但是mobileApp先改版其中一欄位需要不一樣的資料怎麼辦？
- 做過realtime app嗎？後台發message給一個使用者andy怎麼做？怎麼知道andy mapping到哪個connectionID？若mapping存在server上，有多台server怎麼知道mapping？

### Coding
#### Javascript
- `<script>`放header和End of body有甚麼差別？`stylesheet`呢?
- `<script async defer>`差別？
- 請實作:`duplicate([1,2,3,4,5]);`
- == vs ===
- 如何從A client request B domain 資料？(Cross domain ajax)
- Closure
- 前端Framework：React-state/props, Angular-directive
- NodeJS：Express怎麼處理error/request/response/next？
- Defer/Promise：Resolve Reject是什麼？你在哪邊有用過Promise呢？

#### CSS
- ID vs class
- 你都怎麼修Css bug?
- 用過哪些CSS framework嗎？
- RWD原理是什麼？
- Sprite
- Font-icon
- 列出並介紹你知道的 css display property 

### Reference
https://github.com/h5bp/Front-end-Developer-Interview-Questions
