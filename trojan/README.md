# Trojan 
تروجان یک پراکسی سرور هست که برای دور زدن فایروال چین ساخته شده و خودش رو شبیه رکوئست های معمولی HTTP نشون میده و ادعا داره که غیر قابل تشخیص هست . این پروتکل جدیده و روش کارش به این صورت است که که با سرور عملیات TLS Handshake انجام میده در صورتی که این عملیات موفق باشه همه ترافیک توسط TLS محافظت خواهند شد و در غیر اینصورت سرور کانکشن رو همانند یک  سرور HTTPS خواهد بست. سپس کلاینت شروع به ارسال ساختار خاصی از داده ها می کنه سرور در ابتدا پسورد رو کنترل می کنه اگر درست بود رکوئست رو به عنوان یک رکوئست ولید تروجان قبول می کنه و تونل بین سرور و کلاینت برقرار میشه. 

## ابزار ها 
خوشبختانه تعدادی اپ که از این پروتکل پشتیبانی می کنن وجود داره که در ادامه معرفی شون می کنم نسخه ISO هم وجود داره که لینکشو قرار می دم . 

- [Qv2Ray for Desktop](/v2ray/app/)
- [Trojan for Android](/trojan/app/)
- [OnClick for IOS](https://apps.apple.com/us/app/oneclick-safe-easy-fast/id1545555197)

## سرویس دهنده ها 
سبق روال لیست سرویس دهنده هایی که در این قسمت قرار میگیره روزانه آپدیت میشه اونایی که توسط تیم خودمون ساخته شدن محدودیت استفاده ۲۴ ساعته دارن . 

| expire | provider | url |
| --- | --- | --- | 
| 2023-01-06 23:00 | ⚡OurTimeisNow | trojan://QbRZmktsOz@xyz.outlawanonymouse.ml:8080?security=tls&headerType=http&type=tcp&sni=portfolio.outlawanonymouse.ml#%E2%9A%A1Anonymouse%23200-OurTimeIsNow%E2%9A%A1 |
| 2023-01-06 23:00 | ⚡OurTimeisNow | trojan://2QyiwBOzNF@xyz.outlawanonymouse.ml:8080?security=tls&headerType=http&type=tcp&sni=portfolio.outlawanonymouse.ml#%E2%9A%A1Anonymouse%23200-OurTimeIsNow%E2%9A%A1 |
