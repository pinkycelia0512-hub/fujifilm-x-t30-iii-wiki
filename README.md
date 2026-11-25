# FUJIFILM X-T30 III 新手教學 Wiki 與 HTML 簡報

本專案以 FUJIFILM 官方資料建立 X-T30 III 新手知識庫，再將通過檢查的內容製作成可在瀏覽器翻頁的教學 HTML 簡報。

## 專案內容

- `AGENTS.md`：專案規則、結構、資料與檢查標準。
- `raw/`：6 份官方資料摘要。
- `wiki/index.md`：整合後的 LLM Wiki。
- `wiki/log.md`：實際執行、修正與反思紀錄。
- `dist/index.html`：教學 HTML 簡報。
- `dist/wiki.html`：可瀏覽 Wiki。
- `dist/report.html`：loop／graph、檢查紀錄與反思。

## Workflow

取得官方資料 → 分類整理 → 建立 Wiki → 規格與內容檢查 → 生成 HTML 簡報 → 瀏覽測試

若檢查失敗，會回到「分類整理」或「建立 Wiki」修正，再重新產生簡報。

## 本機瀏覽

直接打開 `dist/index.html`，或在專案根目錄執行：

```bash
python -m http.server 8000 --directory dist
```

再開啟 `http://localhost:8000`。
