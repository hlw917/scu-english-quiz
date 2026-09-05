東吳英檢練習 App V1.0（PWA）

內容
- 第 51～110 題，共 60 題
- 文法＋閱讀
- 逐題作答
- 即時判斷
- 正確率統計
- 錯題重練
- 隨機出題
- 自動保存作答進度
- PWA 離線快取

使用方式
1. 本機電腦：
   直接開啟 index.html 可使用測驗功能。
   注意：Service Worker / PWA 安裝通常需要透過 HTTPS 網址或 localhost 才能完整啟用。

2. iPhone / iPad：
   將整個資料夾上傳至 GitHub Pages、Netlify、Cloudflare Pages 或其他 HTTPS 網頁空間。
   使用 Safari 開啟網址。
   按「分享」→「加入主畫面」。

3. Android：
   使用 Chrome 開啟 HTTPS 網址，依瀏覽器提示「安裝應用程式」。

重要
- 不要只上傳 index.html；manifest.webmanifest、service-worker.js 與 icons 資料夾需一起上傳。
- 題庫與作答紀錄都在使用者裝置端處理，不需要伺服器資料庫。
