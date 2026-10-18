# TOEIC Line Dog｜GitHub Pages 部署

本資料夾可作為 GitHub 儲存庫根目錄。網站由 GitHub Actions 部署到 GitHub Pages，透過 GitHub 提供的 HTTPS 網址公開瀏覽。

## 發佈步驟

1. 在 GitHub 建立儲存庫，名稱建議使用 `toeic-line-dog`。網站內容與小狗圖片會公開，請先確認這些內容適合公開。
2. 將本資料夾中的 `.github/`、`assets/`、`.gitignore`、`index.html` 和本說明檔放在儲存庫根目錄。不要上傳 `index-before-shop-and-dog-assets.html` 備份。
3. 在儲存庫的 **Settings → Pages → Build and deployment → Source** 選擇 **GitHub Actions**。
4. 將檔案推送到 `main` 分支。GitHub Actions 會執行「Deploy site to GitHub Pages」工作流程。
5. 在 **Actions** 確認部署成功，再回到 **Settings → Pages** 開啟網站網址。GitHub Pages 使用 HTTPS；若有 **Enforce HTTPS** 選項，請開啟。

## 更新網站

修改 `index.html` 或 `assets/` 後，推送到 `main` 即會重新部署。學習進度存在使用者瀏覽器的本機儲存空間，不會同步到其他裝置。