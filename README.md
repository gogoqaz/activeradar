# 主動式ETF底牌 — 支援、隱私政策與使用條款

「主動式ETF底牌」(主畫面顯示為「主動ETF底牌」)App 與網站的對外說明頁,
以 GitHub Pages 發佈。App Store Connect 的「支援 URL」與「隱私政策 URL」指向這裡,
網站頁尾的「隱私政策」與「使用條款」也連到這裡。

| 頁面 | 檔案 | 用途 |
| --- | --- | --- |
| 支援與說明 | `index.html` | App 功能說明、常見問題、資料來源、聯絡方式 |
| 隱私政策 | `privacy.html` | App 與網站處理哪些資料、保留多久(持股更新通知、訂閱通知、網站流量統計) |
| 使用條款 | `terms.html` | 服務內容、不構成投資建議、訂閱與贊助、使用規範 |

三頁都是自足的單一 HTML —— 無外部 CSS/JS/字型/圖片,支援深淺色與行動版。
色值逐項對照 App 的 `DesignTokens.swift`,改 App 配色時記得一併更新。

本機預覽:

```bash
python3 -m http.server 8899
```

App 本身的原始碼在另一個(私有)repo,不在這裡。
