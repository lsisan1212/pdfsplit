# PDFSplit

PDF / 圖片 / TIFF 分割合併單檔工具，部署於 GitHub Pages。

## 線上入口（直接開啟工具）
https://lsisan1212.github.io/pdfsplit/

- `index.html` — 自動跳轉到 `pdfSplit.html`（根網址 = 工具）
- `pdfSplit.html` — 工具本體（純前端、零後端）

## 工具功能
- 支援 PDF、JPG、PNG、TIFF（含多頁 TIFF）一次性載入
- 每頁填 TM（員工編號，自動補零 6 位）+ 開始/結束日期
- 多頁同組合併、勾選單獨合併、產生 ZIP 下載
- 淺色/深色主題、繁中/English 切換

> 離線：將四個 CDN 的 `.js`（utif、pdf-lib、pdf.js、jszip）下載到同目錄並改相對路徑即可。
