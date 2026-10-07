# vitaVPN — Android & Windows

دانلود رسمی **اندروید ۱٫۰٫۹، ساخت ۷۴** و **ویندوز ۱٫۰٫۶**.

## اندروید ۱٫۰٫۹

- [ARM64 — مناسب بیشتر گوشی‌ها](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.9/vitaVPN-1.0.9-arm64-v8a.apk)
- [ARM 32-bit](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.9/vitaVPN-1.0.9-armeabi-v7a.apk)
- [x86_64](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.9/vitaVPN-1.0.9-x86_64.apk)
- [x86](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.9/vitaVPN-1.0.9-x86.apk)

حداقل Android 7.0؛ فایل مناسب معماری دستگاه را روی نسخهٔ قبلی نصب کنید. اطلاعات فعال‌سازی حفظ می‌شود و اتصال VPN هنگام نصب موقتاً قطع می‌شود.

[توضیحات انتشار اندروید](https://github.com/VitaNet-CRM/vitaVPN/releases/tag/v1.0.9) · [هش فایل‌های اندروید](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.9/SHA256SUMS.txt)

## ویندوز ۱٫۰٫۶

- [نصب‌کنندهٔ خودکار EXE](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.6/vitaVPN-1.0.6-Setup.exe) — معماری سیستم را تشخیص می‌دهد و MSI مناسب را دریافت و بررسی می‌کند؛ اینترنت لازم است.
- [Windows x64 — نصب آفلاین MSI](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.6/vitaVPN-1.0.6-x64.msi)
- [Windows x86 — نصب آفلاین MSI](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.6/vitaVPN-1.0.6-x86.msi)

فقط یک نصب‌کننده را اجرا کنید. نصب جداگانهٔ .NET لازم نیست. Windows 10/11 x64 و Windows 10 x86 پشتیبانی می‌شوند؛ Windows ARM64 پشتیبانی نمی‌شود. نصب‌کننده‌ها فعلاً امضای Authenticode ندارند. پیش از نصب اتصال VPN را قطع کنید.

[توضیحات انتشار ویندوز](https://github.com/VitaNet-CRM/vitaVPN/releases/tag/v1.0.6) · [هش فایل‌های ویندوز](https://github.com/VitaNet-CRM/vitaVPN/releases/download/v1.0.6/SHA256SUMS.txt)

## تغییرات و بررسی

بهبود پشتیبانی از پروتکل‌های پنل ثنایی و نمایش مقصدهای جدید، اصلاح راه‌اندازی WireGuard در اندروید، و حفظ انتخاب دستی و خودکار سرور.

اندروید: ۳۳ آزمون مرتبط و پذیرش کانفیگ هر ۸ پروتکل در هسته روی سامسونگ موفق بود. اتصال واقعی WG و UK و اتصال دوباره در حالت خودکار با درخواست HTTPS از داخل VPN بررسی شد. ویندوز: ۱۳۵ بررسی عمومی، ۴۷ بررسی پروتکل و ۱۴ بررسی فهرست سرورها موفق بود؛ نصب x64 و اتصال واقعی WG با درخواست HTTPS تأیید شد. اتصال واقعی همهٔ پروتکل‌ها و همهٔ دستگاه‌ها هنوز بررسی نشده است.

نسخه‌های قبلی در [فهرست انتشارها](https://github.com/VitaNet-CRM/vitaVPN/releases) محفوظ‌اند. سورس برنامه‌ها **خصوصی و اختصاصی** است؛ آرشیوهای خودکار GitHub فقط محتوای همین مخزن دانلود را دارند.

## English

Official Android **1.0.9 (build 74)** and Windows **1.0.6** downloads. Improved Sanaei protocol support and Android WireGuard startup. Choose the file matching your device architecture. Android requires Android 7.0 or newer. Windows installers are self-contained; Windows ARM64 is unsupported. Application sources are private.