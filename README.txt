HFC Network Tool PWA v1.0

使用方式：
1. 將整個資料夾內容部署到支援 HTTPS 的靜態網站空間（例如 GitHub Pages、Cloudflare Pages）。不可只將 ZIP 放到 iPhone 開啟，這樣無法正常安裝 PWA 或使用 Service Worker。
2. 用 iPhone Safari 開啟 HTTPS 網址，點「分享」→「加入主畫面」。
3. 第一次需連網載入；之後已快取的頁面可以離線使用，線上 DNS / HTTPS 測試仍需連網。

限制：網頁版不支援 ICMP Ping、任意 TCP Port 掃描、Gateway 自動偵測、CM 訊號自動讀取。Ping 欄位為手動輸入其他工具實測數據。DNS 和 HTTPS 測試可能受 CORS、網路或瀏覽器政策影響。

資料儲存在瀏覽器 localStorage，清除網站資料可能造成遺失，請定期匯出 CSV。
