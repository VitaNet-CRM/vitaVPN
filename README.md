# vitaVPN — Android & Windows

دانلود رسمی **اندروید ۱٫۰٫۱۰، ساخت ۷۵** و **ویندوز ۱٫۰٫۸**؛ با پشتیبانی از مسیر جایگزین CRM و IP ثابت هنگام اختلال DNS.

## اندروید ۱٫۰٫۱۰

- [ARM64 — مناسب بیشتر گوشی‌ها](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.10/vitaVPN-1.0.10-arm64-v8a.apk)
- [ARM 32-bit](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.10/vitaVPN-1.0.10-armeabi-v7a.apk)
- [x86_64](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.10/vitaVPN-1.0.10-x86_64.apk)
- [x86](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.10/vitaVPN-1.0.10-x86.apk)

حداقل Android 7.0؛ فایل مناسب معماری را روی نسخه قبلی نصب کنید. فعال‌سازی حفظ می‌شود و VPN هنگام نصب لحظاتی قطع می‌شود.

[توضیحات و هش اندروید](https://github.com/VitaNet-CRM/vitaVPN/releases/tag/v1.0.10)

## ویندوز ۱٫۰٫۸

- [نصب‌کننده خودکار EXE](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.8/vitaVPN-1.0.8-Setup.exe) — اینترنت لازم است.
- [نصب آفلاین x64](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.8/vitaVPN-1.0.8-x64.msi)
- [نصب آفلاین x86](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.8/vitaVPN-1.0.8-x86.msi)

فقط یکی را نصب کنید. Windows 10/11 x64 و Windows 10 x86 پشتیبانی می‌شوند؛ ARM64 پشتیبانی نمی‌شود. نصب‌کننده‌ها امضای Authenticode ندارند. پیش از نصب VPN همین دستگاه را قطع کنید.

[توضیحات و هش ویندوز](https://github.com/VitaNet-CRM/vitaVPN/releases/tag/v1.0.8)

## تغییرات و بررسی

مسیر جایگزین CRM و IP ثابت با TLS معتبر اضافه شده و پرش صفحه ویندوز هنگام پیام وضعیت اصلاح شده است. جابه‌جایی CRM سرور ثابت مشتری را تغییر نمی‌دهد.

۲۶ بررسی کنترل مسیر اندروید و ۲۸ بررسی ویندوز پس از اصلاح IP موفق بودند. همین ARM64 روی Samsung A73 و همین x64 روی ویندوز مالک نصب و با هش تطبیق داده شدند؛ اتصال واقعی VPN و مسیر جایگزین بررسی شد. آزمون جداگانه روی شبکه فیزیکی سامسونگ و تست دستگاه واقعی همه معماری‌ها تکمیل نیست. جزئیات در توضیحات انتشار آمده است.

نسخه‌های قبلی در [فهرست انتشارها](https://github.com/VitaNet-CRM/vitaVPN/releases) حفظ شده‌اند. سورس برنامه‌ها **خصوصی و اختصاصی** است؛ آرشیوهای خودکار GitHub محتوای مخزن دانلود هستند.

## English

Official Android **1.0.10 (build 75)** and Windows **1.0.8** downloads. CRM failover and fixed-IP routes preserve TLS validation. Windows status notifications no longer shift the page. Choose the file matching your device architecture. Android requires Android 7.0 or newer. Windows ARM64 is unsupported. Application sources are private.
