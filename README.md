# 店長當更 — Store Manager Learning Games

四個 BU 嘅 Shrinkage Awareness 互動試玩版：WTCHK、PNS、FTR、WW。每個版本有三個任務、即時回饋、重試，以及每題獨立嘅寫實人物情境及約 8 秒輕微運鏡。

## 下載及試玩

1. 打開 [下載套件](./store-manager-motion.zip)，按 GitHub 右上方 **Download raw file**（下載箭嘴）。亦可以用 repository 嘅 **Code → Download ZIP**。
2. **解壓全部檔案**。
3. 用電腦 Chrome 或 Edge 開啟 `index.html`；保留 `game.js`、`style.css` 同兩張 PNG（scene-1.png 及 question-scenes.png） 喺同一個資料夾。

唔好喺 GitHub 檔案預覽、聊天附件預覽或 ZIP 預覽直接執行 HTML。GitHub 檔案頁面顯示原始碼係正常。

單檔離線版亦提供於 [store-manager-motion.html](./store-manager-motion.html)，同樣需要先下載，再用瀏覽器開啟。

## 網頁部署

根目錄已包含靜態網站所需檔案，毋須安裝依賴或 build。
如帳戶及 repository 支援 GitHub Pages，可由 repository 管理員前往 **Settings → Pages → Deploy from a branch → main → / (root)** 啟用。網站未啟用前，repository 連結只供檔案瀏覽及下載。

## 內容及限制

- 場景及人物為 AI 生成，非真實分店或真人實拍。
- 12 條題目各自配有對應圖片，動態以輕微運鏡及字幕製作，並非連續人物動作影片。
- 無需登入；完成標記只儲存於本機瀏覽器。
- 支援暫停、重播；系統「減少動態」設定下預設靜態，仍可主動按播放或重播。
- 未接駁 LMS / SCORM，亦未加入配音。
- BU 名稱及場景對應為概念設計假設；正式品牌素材、責任分工及升級處理程序需內部確認。
- 核心原則：睇行為、先服務、安全行先；唔追、唔搜、唔對抗。

## 已驗證

Chromium 下測試四個 BU 共 12 關、錯誤回饋、重試、完成標記、圖片載入、動態轉場、暫停及重播，並檢查手機寬度排版。未完成正式 LMS 或所有裝置測試。

## 題目場景更新

- WTCHK：遮擋視線嘅高陳列、偏僻大量商品陳列、商品放入個人袋。
- PNS：兩區同時有服務需要、自助付款未完成、出口附近同事等候指示。
- FTR：三種顧客行為、同時發生嘅查詢及遮擋動作、店長與同事交代情況。
- WW：酒瓶放入個人袋、拒絕購物籃、顧客質疑時嘅對話。
- 答題前只顯示當刻情境；答對後先顯示文字行動結果。背景圖仍代表原先情境，唔係處理後嘅照片。

FTR 已取消觀察卡及解鎖限制：直接睇場景作答，答後提供解釋同回饋。

重播控制已更新：由零開始播放，顯示播放時間與進度，支援暫停後重播及播放完成後重播。
