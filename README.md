# RKL 互動式幾何手冊

RIKULAU 車架尺寸幾何、客製車架幾何輸入與 3D 預覽、16 點扭力巡檢的互動網頁。單一 `index.html`，以 three.js r128 在瀏覽器內以程式繪製 3D，不載入任何模型檔。

- 尺寸幾何：六款車型、各尺寸，輸入身高、跨高、手臂長取得尺寸推薦
- 客製車架：十項騎乘幾何輸入、即時驗證、表單輸出（.md／.txt）
- 扭力巡檢：16 個部位，點選 3D 零件、設定扭力、計分

## 本機開啟

直接用瀏覽器開啟 `index.html` 即可（需連網，three.js 與字型從 CDN 載入）。

## 外部相依

| 項目 | 來源 |
|---|---|
| three.js r128 | `cdnjs.cloudflare.com` |
| Noto Sans TC、Barlow Condensed | Google Fonts |

## 部署到 GitHub Pages

儲存庫 → Settings → Pages → Source 選 `Deploy from a branch`、Branch 選 `main`、資料夾 `/ (root)` → Save。數十秒後網址為 `https://<帳號>.github.io/<儲存庫名>/`。

## 已知限制

- 在 claude.ai 以外的環境，「表單輸出」沒有直接下載能力，會改為顯示可複製的文字框。
- 推薦尺寸的係數為經驗估值，尚未經實騎或銷售資料校正。
- 3D 為示意，只有車架幾何以管長與角度為準，其餘零件外形為示意。

## 權利

保留所有權利。幾何資料與品牌標誌屬佰奇創意機械股份有限公司（RIKULAU），未經許可不得轉載或再利用。
