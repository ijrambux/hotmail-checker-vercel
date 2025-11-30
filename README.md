# Hotmail Checker – Vercel Frontend

هذه النسخة خاصة بـ **Vercel فقط**.
Vercel لا يشغل Python أو IMAP.

لذلك:
- الواجهة هنا فقط (HTML + CSS + JS)
- الخادم Python يجب تشغيله على Render / Railway / local machine

## طريقة الربط
غيّر الرابط في `index.html` داخل:

```js
fetch("https://YOUR-BACKEND-URL/check")
