# 拾光｜課表與待辦

GitHub Pages 網站：<https://puweichih.github.io/20261030/>

網站使用 Firebase Authentication 登入、Cloud Firestore 儲存資料，並透過 Firebase AI Logic 提供拾光 AI 助手。AI 助手只會將待辦名稱、分類、日期、課表與目前訊息送給 Gemini 作為回答脈絡；對話不會寫入 Firestore。

## 本機預覽

請用本機網站伺服器透過 `http://localhost` 開啟，不要直接用 `file://` 開啟。Firebase App Check 的本機 debug token 放在被 Git 忽略的 `appcheck-local.js`，不要提交這個檔案。

## 發佈

將 `main` 分支推送到 GitHub 後，GitHub Pages 會更新網站。Firebase App Check 的正式 reCAPTCHA 網域限定為 `puweichih.github.io`。
