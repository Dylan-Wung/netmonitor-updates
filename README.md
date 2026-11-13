# netmonitor-updates

NetMonitor 的「更新提醒」中繼資料。**只有版本資訊，沒有原始碼或發布包。**

- `latest.json`：最新發布版本（版本號、發布日、一句話摘要）。NetMonitor 設定頁的「更新檢查網址」指向此檔。
- `latest-test.json`：功能驗證用，請勿使用。

NetMonitor 只用它來「提醒有新版」，不會據此下載或安裝任何東西；實際升級須由管理員執行，且升級包會獨立驗證簽章。
