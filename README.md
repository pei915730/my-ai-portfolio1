# Github-一鍵發布及一鍵修改

純 HTML + CSS + JavaScript 靜態網站。

- `index.html`：入口首頁。
- `new.html`：建立新公開 Repository，並發布 ZIP 網站。若名稱已存在，停止建立。
- `update.html`：更新既有 Repository 的網站檔案。

兩個功能頁面最底部統一提供 Token 差異比較、取得路徑、權限及 GitHub Pages 設定路徑；上方不重複顯示 Token 操作教學。

Classic Token：`public_repo`；Fine-grained Token：指定 Repository + `Contents: Read and write`，管理 Pages 時另需 `Administration: Read and write`。

將三個 HTML 上傳到 GitHub Pages 靜態站即可使用。Token 不應提交到 Repository。
