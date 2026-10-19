# 紅洋貿易有限公司｜GitHub Pages 企業形象網站 V1.0

## 專案用途
純靜態網站，**只需 GitHub Pages**，不需要 Vercel、Supabase、Node.js、npm 或任何資料庫。全站繁體中文，包含：首頁、關於紅洋、商品介紹、乾燕窩、台灣高端水果、品牌故事、最新消息、聯絡資訊。

> 重要：這個網站不是線上商店；沒有購物車、售價、結帳、付款、詢價表單或會員資料收集。GitHub Pages 官方限制將其用於主要促成商業交易的網站。若之後改為電商，請重新評估託管平台。

## 快速發布（無須程式安裝）

1. 將本 ZIP 解壓縮，確認 `index.html` 位於資料夾根目錄。
2. 登入 GitHub，建立一個新的 Repository，例如 `hongyang-website`。
3. 在 Repository 選 **Add file → Upload files**，把這個資料夾**裡面的所有檔案及 assets 資料夾**上傳（不要額外包一層資料夾）。
4. Commit changes。
5. 進入 **Settings → Pages → Build and deployment**。
6. **Source** 選 `Deploy from a branch`；**Branch** 選 `main`、資料夾選 `/(root)`，按 **Save**。
7. 部署完成後，網站通常會在 `https://你的GitHub帳號.github.io/hongyang-website/`。

若選用付費 GitHub 方案，可視方案用私人 Repo 作為來源；**部署的網頁仍會公開**，切勿將機密放到檔案中。

## 如何在電腦測試

直接雙擊 `index.html` 即可瀏覽大部分功能。亦可在專案資料夾執行 `python -m http.server 8000`，然後開啟 `http://localhost:8000`。

## 修改內容

- `index.html`：首頁
- `about.html`：公司介紹（目前部分文字為待確認示意）
- `products.html`：商品分類
- `nest.html`：乾燕窩介紹（規格未定）
- `fruit.html`：台灣高端水果介紹
- `stories.html`：品牌故事
- `news.html`：消息
- `contact.html`：聯絡方式（**務必填入正確資料**）
- `assets/css/style.css`：全站版型、字體與配色
- `assets/js/main.js`：手機選單與頁尾年份
- `assets/img/*.svg`：可自行替換的**原創示意插畫**；不代表實物

建議使用 VS Code 編輯後上傳 GitHub。網站使用相對路徑，支援 GitHub Pages 的專案型網址。

## 上線前檢查

- [ ] 公司沿革與經營理念均已由公司確認
- [ ] 聯絡方式、公司地址、對外資訊已改為真實資料
- [ ] 商品頁文字經確認，未誇大燕窩食品功效
- [ ] 示意插畫是否需要替換為經授權的商品照片
- [ ] 瀏覽桌面與手機尺寸
- [ ] 所有導覽連結可用
- [ ] 確認網站定位維持「企業形象／商品介紹」，不涉及交易

## GitHub Pages 官方說明

- 發布設定：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- 使用限制：https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

## 未來升級

第一階段保留文字介紹頁及可重用的 CSS；若日後轉為 B2C/B2B 電子商務，需要搭配新的後端與符合商業交易用途的託管服務，不能直接在 GitHub Pages 加上支付功能。
