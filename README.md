# PDFSplit

PDF / 圖片 / TIFF 分割合併單檔工具，部署於 GitHub Pages。

## 線上入口
https://lsisan1212.github.io/pdfsplit/

- `index.html` — portal 主頁（卡片入口，含搜尋 / 4 套主題）
- `pdfSplit.html` — 工具本體（純前端、零後端）
- `tools.json` — 子頁 manifest（加新子頁時改這個）

## 加新子頁
1. 將 `<New>.html` 丟根目錄
2. 在 `tools.json` 的 `tools` 陣列加一項
3. `git add && git commit && git push`（漏改 JSON 亦會自動偵測顯示）

## 工具功能
- 支援 PDF、JPG、PNG、TIFF（含多頁 TIFF）一次性載入
- 每頁填 TM（員工編號，自動補零 6 位）+ 開始/結束日期
- 多頁同組合併、勾選單獨合併、產生 ZIP 下載
- 淺色/深色主題、繁中/English 切換

> 離線：將四個 CDN 的 `.js`（utif、pdf-lib、pdf.js、jszip）下載到同目錄並改相對路徑即可。
