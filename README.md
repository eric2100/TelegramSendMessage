# TelegramSendMessage
這是一個在終端機介面透過 curl 傳送到 telegram API，轉發到頻道的 script

# 使用方式
## 設定變數
```
  TOKEN=<TOKEN>
  CHAT_ID=<CHAT_ID>
```  
## 執行方法
### 單純傳送文字
```bash
./SendMsg Hello
```
### 傳送文字與檔案  
```bash
./SendMsg Hello /tmp/a.txt
```
