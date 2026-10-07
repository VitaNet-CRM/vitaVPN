# vitaVPN — Android & Windows

دانلود رسمی از [آخرین انتشار](https://github.com/VitaNet-CRM/vitaVPN/releases/latest)؛ اندروید **۱٫۰٫۵، ساخت ۷۰** و ویندوز **۱٫۰٫۳**.

## دانلود اندروید

- [گوشی‌های جدید — ARM64](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/vitaVPN-1.0.5-arm64-v8a.apk)
- [گوشی‌های قدیمی — ARM 32-bit](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/vitaVPN-1.0.5-armeabi-v7a.apk)
- [شبیه‌ساز x86_64](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/vitaVPN-1.0.5-x86_64.apk)
- [شبیه‌ساز x86](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/vitaVPN-1.0.5-x86.apk)

حداقل Android 7.0؛ فایل مناسب معماری دستگاه را روی نسخهٔ قبلی نصب کنید.

## دانلود ویندوز

- [Windows x64 — نصب‌کنندهٔ آفلاین MSI](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/vitaVPN-1.0.3-x64.msi)
- [Windows x86 — نصب‌کنندهٔ آفلاین MSI](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/vitaVPN-1.0.3-x86.msi)

فقط فایل مناسب معماری ویندوز را نصب کنید. نصب جداگانهٔ .NET لازم نیست. Windows ARM64 پشتیبانی نمی‌شود. فایل‌های MSI امضای Authenticode ندارند.

## تغییرات و بررسی

اعمال سهم مساوی یا وزن دلخواه Pool در اتصال خودکار، حفظ انتخاب دستی و اتصال سالم فعلی، و بهبود انتخاب مقصد جایگزین هنگام اختلال پنل.

اندروید: ۱۰۹۲ آزمون واحد موفق، بررسی امضا و تراز ۱۶ کیلوبایت، اتصال واقعی VPN در شبیه‌ساز Pixel و پاسخ HTTP 204 از داخل VPN تأیید شد. ویندوز: ۱۲۱ بررسی موفق و نصب x64 تأیید شد؛ آزمون اتصال واقعی ویندوز هنوز تکمیل نشده است.

[SHA256SUMS.txt](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.5/SHA256SUMS.txt) برای مقایسهٔ هش فایل‌ها. سورس برنامه‌ها خصوصی است؛ آرشیوهای خودکار GitHub فقط محتوای مخزن دانلود را دارند.

## English

Official Android **1.0.5 (build 70)** and Windows **1.0.3** binaries, identical to the CRM release. Automatic connections honor CRM pool distribution; manual selection and healthy existing connections remain preserved. Android requires Android 7.0 or newer. Choose the installer matching your device architecture.

Android: 1,092 unit tests passed; signature/alignment checks and VPN-bound HTTP 204 on the Pixel emulator passed. Windows: 121 checks and x64 installation passed; real Windows VPN connection verification is still pending.
