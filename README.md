# MasterHttpRelayVPN + termux +psiphon
کاربرد: تونل کردن MasterHttpRelayVPN همه برنامه تو اندروید [متن قبلی](https://github.com/therealaleph/MasterHttpRelayVPN-RUST/issues/847)
# اموزش با متن:

پیش‌نیاز 
---
ترموکس
```
pkg install python3 git -y
apt install python-cryptography
termux-setup-storage
```
~**نکته مهم**: دستور بالا حتما یک بار به کانفیگ چیزی وصل باشید ک نصب  شه~

پایتون باچیزای ک نیاز به نصب داره
[اموزش دانلود و اجرا MasterHttpRelayVPN](https://github.com/masterking32/MasterHttpRelayVPN/blob/python_testing/README_FA.md#%D9%85%D8%B1%D8%AD%D9%84%D9%87-1-%D8%AF%D8%B1%DB%8C%D8%A7%D9%81%D8%AA-%D9%BE%D8%B1%D9%88%DA%98%D9%87)
ترکیب با
سایفون
---
حتما از 
https://github.com/masterking32/MasterHttpRelayVPN
استفاده کنید با
 mhrv-rs
تست زدم نشد
کد با ترموکس ران کنید
بعد
 ca certificate 
شو دستی نصب کنید بریز به حافظه 
بعد با http سایفون
در مسیر options=>proxy settings
هاست 127.0.0.1
پورت هم خودتون تو config.json وارد کردید بزنید

یک نکته ک هست سایفون فقط اپ های ک میخواید تانل شه انتخاب کنید(ترموکس نباید تانل شه)
مسیر 
options=>vpn settings=>only tunnel selected apps

سایفون ترکیب کنید وصل شید منتظر بمونید تا تلگرام لود شه
```
pip install -r requirements.txt -i https://mirror-pypi.runflare.com/simple/ --trusted-host mirror-pypi.runflare.com
```
# [اموزش با ویدیو لینک مستقیم](https://raw.githubusercontent.com/amirwolf512k/data/refs/heads/main/video.mp4)
https://m.youtube.com/watch?v=U8yAa_GYEdc

`چیزی ک فهمیدم با برنامه شیر خورشید سرعت بهتری داره`
# نمونه :

<p align="center">
  <img src="https://github.com/user-attachments/assets/c9fc286c-23fb-4149-9402-c7c76c9c694e" width="45%">
  <img src="https://github.com/user-attachments/assets/11f1d67a-b8b7-4d6d-9b17-02e3b4fcc716" width="45%">
</p>

