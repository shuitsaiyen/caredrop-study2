# CareDrop Study 2 · 部署說明

## 檔案
- `index.html` — 受試者主流程（A1B1 條件）
- `admin.html` — 研究者後台
- `README.md` — 本檔

## 部署到 Vercel（最快路徑）

### 步驟 1：建 GitHub repo
1. 到 github.com 點 `+` → `New repository`
2. 名稱：`caredrop-study2`
3. 設 `Public` → 點 `Create repository`

### 步驟 2：上傳檔案
1. 在新 repo 頁面點 `uploading an existing file`
2. 把 `index.html`、`admin.html`、`README.md` 拖進去
3. 點 `Commit changes`

### 步驟 3：連 Vercel
1. 到 vercel.com → 點 `Add New` → `Project`
2. 選 `caredrop-study2` repo
3. 直接點 `Deploy`（不用設定）
4. 等 30 秒，會給你網址：`https://caredrop-study2-xxx.vercel.app`

## QR code 連結
- 受試者：`https://你的網址/?c=A1B1&s=S01`
- 後台：`https://你的網址/admin.html`（密碼：`caredrop2026`）

## 可改的密碼
打開 `admin.html`，找到這行：
```
const ADMIN_PWD = 'caredrop2026';
```
改成你想要的密碼。
