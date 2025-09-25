
使用說明（GitHub Pages）
------------------------
1) 把整個 exp-quest 資料夾上傳到 GitHub 新 repo（public）。
2) Settings → Pages → Source: Deploy from a branch；Branch: main；Folder: / (root) → Save。
3) 等待部署完成，網址會是 https://<你的帳號>.github.io/<repo名稱>/

檔案結構：
exp-quest/
  ├─ index.html
  ├─ README.txt
  └─ images/
     ├─ Emma_proudpost.png
     ├─ Emma_gratefulpost.png
     ├─ Lil_Miquela_proudpost.png
     ├─ Lil_Miquela_gratefulpost.png
     ├─ Pata_proudpost.png
     └─ Pata_gratefulpost.png

表單對接：
- GOOGLE_FORM_BASE 已設為你的表單 viewform 連結
- group/condition 的 entry ID: entry.1234557594
- 前往問卷時會自動帶入 A~F 其中一個代碼
- 刺激頁面有 10 秒等待倒數，按鈕才會解鎖

若要修改等待秒數：
- 搜尋 startGateTimer()，將 10 改成你要的秒數。

