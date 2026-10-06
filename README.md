# proposal-form

一張給 Telegram Bot 用的靜態表單頁（Telegram Mini App）。

- 只有前端一頁，沒有後端，不儲存任何資料。
- 不含帳號密碼，也不含任何個人資料。
- 填寫的內容透過 `Telegram.WebApp.sendData` 直接送回開啟它的那個 Bot 對話；不是從 Telegram 裡開啟時，送出不會有任何作用。
