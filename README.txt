# Gift Game v2.7（GitHub Pages 版）
單檔 `index.html`，可直接部署到 GitHub Pages。已預填你的 Supabase 連線：
- URL: https://qcbhhfvkfjpazchaixzz.supabase.co
- ANON KEY: sb_publishable_WmO0PJW-WGP5kNNBJiAZtA_5hIdbr0x

## 部署步驟（無 build）
1. 新建 GitHub repository（例如 gift-game）。
2. 上傳這個 zip 內的 `index.html`（放在 repo 根目錄）。
3. 到 Settings → Pages：
   - Source: Deploy from a branch
   - Branch: main，Folder: /（root）→ Save
4. 等 30–60 秒後，訪問 `https://<你的帳號>.github.io/<repo>/`。

## 使用重點
- 主持人先在頁面上設定「總人數」，建立 6 位數字房號。
- 玩家輸入房號 + 名字加入；每台裝置同房只佔一席（device_id）。
- 揭露前只顯示「已送出/尚未選擇」，不顯示 PASS 或數字；揭露後才公開所有選擇。