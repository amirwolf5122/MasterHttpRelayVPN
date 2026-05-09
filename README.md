# MasterHttpRelayVPN + Termux + Psiphon  
تونل‌کردن همه‌ی برنامه‌های اندروید با استفاده از MasterHttpRelayVPN  
---

## 💡 پیش‌نیازها

۱. نصب **Termux**  
از نسخه‌ی رسمی ترموکس در گیت‌هاب استفاده کنید (نسخه‌ی گوگل‌پلی ناقص است):  
👉 [دانلود Termux](https://github.com/termux/termux-app/releases)

۲. نصب پکیج‌های مورد نیاز در Termux:
```
pkg install python3 git -y
apt install python-cryptography
termux-setup-storage
```

## 🐍 نصب و اجرای MasterHttpRelayVPN

راهنمای کامل در لینک زیر موجود است:  
🔗 [آموزش نصب MasterHttpRelayVPN (نسخه پایتون)](https://github.com/masterking32/MasterHttpRelayVPN/blob/python_testing/README_FA.md#%D9%85%D8%B1%D8%AD%D9%84%D9%87-1-%D8%AF%D8%B1%DB%8C%D8%A7%D9%81%D8%AA-%D9%BE%D8%B1%D9%88%DA%98%D9%87)

برای نصب وابستگی‌ها در Termux:
```
pip install -r requirements.txt -i https://mirror-pypi.runflare.com/simple/ --trusted-host mirror-pypi.runflare.com
```

---

## ⚡ ادغام با Psiphon

⚠️ **نکته مهم:** 
نسخه‌ی **mhrv-rs** تست شده ولی کار نکرد.

۱. پس از اجرای برنامه در ترموکس، فایل **CA Certificate** تولید می‌شود.  
فایل را به حافظه گوشی منتقل کرده و دستی نصب کنید.

۲. داخل برنامه **Psiphon** مسیر زیر را دنبال کنید:
```
Options → Proxy Settings
```
- **Host:** `127.0.0.1`  
- **Port:** عددی که در فایل `config.json` تنظیم کرده‌اید. `8085`

۳. برای تونل کردن فقط برنامه‌های موردنظر:
```
Options → VPN Settings → Only tunnel selected apps
```
برنامه‌ی Termux نباید در لیست تونل‌شده باشد.

۴. حالا Psiphon را فعال کنید و منتظر بمانید تا برنامه‌هایی مثل تلگرام متصل شوند.

---

## 🎥 آموزش ویدئویی

📥 [دانلود مستقیم ویدئو](https://raw.githubusercontent.com/amirwolf512k/data/refs/heads/main/video.mp4)  
📺 [مشاهده در YouTube](https://m.youtube.com/watch?v=U8yAa_GYEdc)

---

## 💬 نکات تکمیلی

- طبق تجربه، استفاده از **برنامه‌ی شیر خورشید** سرعت بهتری ارائه می‌دهد.  
- تنها اپ‌های ضروری را تونل کنید تا سرعت افت نکند.

---

## 📸 نمونه تصاویر

<p align="center">
  <img src="https://github.com/user-attachments/assets/c9fc286c-23fb-4149-9402-c7c76c9c694e" width="45%">
  <img src="https://github.com/user-attachments/assets/11f1d67a-b8b7-4d6d-9b17-02e3b4fcc716" width="45%">
</p>
