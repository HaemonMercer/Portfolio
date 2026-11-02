# Haemon Portfolio — GitHub Pages

這是一個可直接部署到 GitHub Pages 的靜態作品集網站。

## 部署方式
1. 建立一個 GitHub repository（例如 `portfolio`）。
2. 將 `index.html` 與 `assets/` 資料夾中的所有圖片上傳到 repository 根目錄。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`、資料夾選 `/(root)`，按 **Save**。
6. 等待部署完成，GitHub Pages 會顯示網站網址。

## 嵌入內容
- OpenProcessing：Windmill、Pattern 01、Key 以 iframe 嵌入。
- YouTube：雙星之誓與 Unity + MediaPipe 展示影片以 YouTube iframe 嵌入。
- 網站不需要後端、Node.js 或建置工具。

## 注意
- 若 OpenProcessing 專案的擁有者未開放嵌入，該區塊可能顯示拒絕連線；請在 OpenProcessing 專案設定中允許嵌入，或確認其公開狀態。
- `assets/page-XX.jpg` 是從提供的 PDF 頁面匯出的視覺素材；可用自己的原始圖片替換。
