# ChatBot-note
#### 要注意不能將 token 和 api key 上傳
#### 要使用環境變數
##### Step 1. 在根目錄建立 .env 檔案並定義變數 TELEGRAM_BOT_TOKEN = 和 OPENAI_API_KEY =
##### Step 2. 再建立 .gitignore 檔案，直接輸入 .env，防止 .env 檔案被 push 到 GitHub 上
##### Step 3. 在程式碼中呼叫變數
