# 主動式ETF雷達 — 支援與隱私政策

「主動式ETF雷達」(主畫面顯示為「主動雷達」)iOS App 的對外網頁,
以 GitHub Pages 發佈。App Store Connect 的「支援 URL」與「隱私政策 URL」指向這裡。

| 頁面 | 檔案 | 用途 |
| --- | --- | --- |
| 支援與說明 | `index.html` | App 功能說明、常見問題、資料來源、聯絡方式 |
| 隱私政策 | `privacy.html` | App Store 要求的隱私政策(本 App 不收集任何個人資料) |

兩頁都是自足的單一 HTML —— 無外部 CSS/JS/字型/圖片,支援深淺色與行動版。
色值逐項對照 App 的 `DesignTokens.swift`,改 App 配色時記得一併更新。

本機預覽:

```bash
python3 -m http.server 8899
```

App 本身的原始碼在另一個(私有)repo,不在這裡。
