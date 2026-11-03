# 成績查詢手機 APP(PWA)

這個資料夾就是 APP。放上任何 https 網址後,手機打開就能「加到主畫面」,有自己的圖示、全螢幕開啟,沒網路也能看。

## 放上網路(擇一)
**A. GitHub Pages(免費、網址固定,推薦)**
1. 到 github.com 建一個新的 public repository,例如 `swim-app`。
2. 告訴 Claude repo 名稱,Claude 會把這個資料夾推上去並開好 Pages。
   (自己做:repo → Add file → Upload files,把資料夾內所有檔案拖進去 → Commit;Settings → Pages → Branch 選 main → Save。)
3. 網址會是 `https://你的帳號.github.io/swim-app/`。

**B. Netlify Drop**:到 app.netlify.com/drop 登入後,把整個「手機APP」資料夾拖進去,會得到一個網址。

## 手機安裝
- iPhone:用 **Safari** 打開網址 → 下方分享鈕 ⬆️ → 「加入主畫面」。
- Android:用 Chrome 打開 → 畫面下方會跳出「安裝」;沒跳的話點右上 ⋮ →「安裝應用程式 / 加到主畫面」。

## 成績更新時
1. 換掉 index.html(Claude 會依最新的 v2 網頁產生)。
2. 把 sw.js 第 2 行 VERSION 改成新日期。
3. 重新上傳。手機下次連網打開 APP 就會自動換成新版。
