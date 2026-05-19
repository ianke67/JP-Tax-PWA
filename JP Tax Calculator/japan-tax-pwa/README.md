# 日本退稅計算機 PWA

退稅計算、匯率換算的 iOS 主畫面 App。

## 功能
- 退稅計算：新增品項、手續費設定、計算退稅金額
- 匯率換算：JPY ↔ TWD，自訂匯率，快速鍵盤輸入
- 使用說明：退稅條件、商品分類、新制說明
- 離線可用（Service Worker 快取）

## 上線步驟（GitHub Pages，免費，約 3 分鐘）

1. 到 https://github.com/new 建立新的 repository（名稱隨意，例如 `japan-tax`）
2. 把這個資料夾的所有檔案上傳（Upload files）
3. 到 Settings → Pages → Source 選 `main` branch → Save
4. 幾分鐘後拿到網址，例如 `https://你的帳號.github.io/japan-tax/`

## 加到 iOS 主畫面

1. 用 **Safari** 開啟你的網址
2. 點底部的「分享」按鈕（□↑）
3. 選「加入主畫面」
4. 名稱可以改，點「加入」
5. 回到主畫面即可看到 App icon

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `index.html` | 主程式（完整 App） |
| `manifest.json` | PWA 設定（Android/Chrome 安裝用） |
| `sw.js` | Service Worker（離線快取） |
| `icon-192.png` | App 圖示 192×192 |
| `icon-512.png` | App 圖示 512×512 |
