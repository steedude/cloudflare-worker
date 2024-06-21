# 建立 Cloudflare Worker

## 事前準備工作

1. Cloudflare 帳號
2. 建立新的 GitHub 空專案並 clone 下來
3. 安裝 Wrangler（`npm install -g wrangler`）

## 建立 Cloudflare Worker 流程

1. 執行 `npm create cloudflare@latest`
2. 選擇剛剛 clone 下來空專案的資料夾
3. 依需求選擇需要的模板
4. 選擇需要發布專案
5. 按照彈出來的網頁登入 cloudflare
6. 完成後就會有基本的專案並可以執行`wrangler dev`測試
7. 執行`wrangler deploy`可以部署
