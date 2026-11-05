 老城裡的漫時光：國家漫畫博物館期中企劃專題網頁

本專案為網頁設計與開發課程之專題作業，將《老城裡的漫時光：國家漫畫博物館期中企劃》內容轉化為符合現代 Web 規範的專題展示網站。包含 SEO 優化、CSS Grid Layout、響應式 RWD 佈局與多分頁切換功能。

 個人與專案資訊

專案名稱： 老城裡的漫時光（國家漫畫博物館期中企劃）

組別： 乙四

作者： 李友書

學號： D1422211

 Vibe Coding 指令說明與 Prompt 紀錄

在開發本專案的過程中，採用了 Vibe Coding（AI 輔助程式開發）模式，將 PDF 企劃書內容精確轉化為現代網頁。以下為發出的 Prompt 指令與開發邏輯：

1. 專案整體結構與 SEO 設定 Prompt

Prompt:

「請依據企劃書《老城裡的漫時光：國家漫畫博物館》內容，設計一個影展/展覽專題網站。規格需求：包含 Open Graph 與 Meta SEO 標籤（作者為 李友書 / 乙四 / D1422211）、頂部導覽列、側邊欄（呈現場域亮點與個人資訊）、主要內容區域使用 JavaScript Tab 進行多分頁切換（專案摘要、競品分析、SWOT/STP定位、創意宣傳腳本）。CSS 必須進行模組化切割（reset.css, grid.css, style.css），圖片放置於 images 資料夾。」

2. 競品分析與 STP 定位數據轉化 Prompt

Prompt:

「請嚴格依照企劃書內容，將國漫館與臺中文學館、臺中州廳、臺中公園的歷史、導覽、體驗與交通比較表轉化為響應式 HTML 表格；並呈現以『文青美學體驗者』為目標客群的十字定位與 SO 交叉策略，絕對不要自行隨意新增非企劃書內的虛構資料。」

3. 創意腳本與 RWD 佈局 Prompt

Prompt:

「請撰寫 CSS Grid 語法，桌機端採用雙欄佈局（側邊欄 280px + 主內容 1fr）；當螢幕寬度小於 768px 時，透過 Media Query 轉為適合手機觀看的單欄垂直排版。並將『張律師法庭辯護』與『YouTuber 街訪』等創意聯想腳本獨立呈現於創意分頁中。」

 技術架構

HTML5: 語意化結構與完整 SEO Meta 標籤設定。

CSS3 (Modularized):

css/reset.css: 跨瀏覽器樣式重置。

css/grid.css: CSS Grid Layout 與 @media (max-width: 768px) RWD 斷點控制。

css/style.css: 和風漫活配色（朱紅與深灰）及組件設計。

JavaScript: 輕量化 Tab 分頁切換邏輯。

Deployment: Vercel & InfinityFree 雙平台託管與部署。

eofs

---

###  最終作業交付格式 (提交給老師的 3 個連結)

在完成 GitHub、InfinityFree 與 Vercel 的上傳與部署後，您可以將這三個連結填入並呈交：

1. **(1) Prompt 說明 Markdown 檔 (GitHub 連結)：**
   `https://github.com/您的GitHub帳號/您的專案名稱/blob/main/README.md`
2. **(2) InfinityFree 個人網址 (可直接顯示 Landing Page 首頁)：**
   `http://您的網域.infinityfreeapp.com/`
3. **(3) Vercel 部署後的網址：**
   `https://您的專案名稱.vercel.app/`

右側編輯器中的網頁程式碼與說明檔案均已準備妥當，可以在編輯器中點擊 `Preview` 預覽效果！


