# 💦 پنل BPB

![پنل BPB](images/panel-overview.jpg)

## معرفی

این پروژه یه پنل کاربری برای دسترسی به کانفیگ‌های رایگان، امن و خصوصی **VLESS**، **Trojan** و **Warp** ارائه می‌ده. حتی وقتی دامنه‌ها یا سرویس Warp توسط اپراتورها فیلتر شدن، اتصال رو تضمین می‌کنه. این پنل به دو روش راه‌اندازی می‌شه:

- با **Cloudflare Workers**
- با **Cloudflare Pages**

🌟 اگه **پنل BPB** براتون مفید بوده، با حمایتتون بهم دلگرمی می‌دید 🌟

```title="USDT (BEP20)"
0xbdf15d41C56f861f25b2b11C835bd45dfD5b792F
```

## ویژگی‌ها

- **رایگان و شخصی**: بدون هیچ هزینه‌ای، سرور شما شخصی هست.
- **پنل کاربری ساده**: کار باهاش راحته و تنظیمات و استفاده ازش خیلی آسونه.
- **پروتکل‌های متنوع**: ارائه کانفیگ‌های VLESS، Trojan و Wireguard (Warp).
- **کانفیگ‌های Warp Pro**: کانفیگ‌های Warp بهینه‌شده برای شرایط خاص ایران.
- **پشتیبانی از Fragment**: اتصال حتی در صورت فیلتر شدن دامنه.
- **قوانین مسیریابی کامل**: دور زدن سایت‌های ایرانی، چینی، روسی و LAN، مسدود کردن QUIC، محتوای پورن، تبلیغات، بدافزارها، فیشینگ و در زدن سایت‌های تحریمی.
- **زنجیره‌ی Proxy**: می‌تونید یه Proxy زنجیره‌ای اضافه کنید تا IP ثابت بشه.
- **پشتیبانی از برنامه‌های مختلف**: لینک‌های اشتراک برای برنامه‌های با هسته‌های Xray، Sing-box و Clash-Mihomo.
- **پنل امن با رمز عبور**: پنل محافظت شده با رمز عبور.
- **سفارشی‌سازی کامل**: تنظیم IP تمیز، Proxy IP، سرورهای DNS، انتخاب پورت‌ها و پروتکل‌ها، Warp Endpoint و خیلی امکانات دیگه.

## محدودیت‌ها

- **اتصال UDP**: پروتکل‌های VLESS و Trojan روی Workerها نمی‌تونن UDP رو به‌خوبی پشتیبانی کنن، برای همین به‌صورت پیش‌فرض غیرفعاله (این روی امکاناتی مثل تماس تصویری تلگرام تأثیر می‌ذاره). DNSهای UDP هم پشتیبانی نمی‌شن. به جاش DoH فعاله که امن‌تره.
- **محدودیت تعداد درخواست**: هر Worker برای VLESS و Trojan روزانه 100 هزار درخواست پشتیبانی می‌کنه، که برای 2-3 نفر کافیه. برای اتصال نامحدود می‌تونید از دامنه شخصی (برای VLESS/Trojan با روش Workers) یا کانفیگ‌های Warp استفاده کنید.

## شروع به کار

- [روش‌های راه‌اندازی](installation/wizard.md)
- [راهنمای تنظیمات](configuration/index.md)
- [نحوه‌ی استفاده](usage/index.md)
- [پرسش‌های متداول (FAQ)](faq.md)

## برنامه‌های پشتیبانی‌شده

|       Client        |     Version      | Fragment support | Warp Pro support |
| :-----------------: | :--------------: | :--------------: | :--------------: |
|     **v2rayNG**     | 1.10.2 یا بالاتر | :material-check: | :material-check: |
|     **MahsaNG**     |   13 یا بالاتر   | :material-check: | :material-check: |
|     **v2rayN**      | 7.12.5 یا بالاتر | :material-check: | :material-check: |
|   **v2rayN-PRO**    |  1.9 یا بالاتر   | :material-check: | :material-check: |
|    **Sing-box**     | 1.11.2 یا بالاتر | :material-close: | :material-close: |
|    **Streisand**    | 1.6.48 یا بالاتر | :material-check: | :material-check: |
|      **Happ**       | 1.6.48 یا بالاتر | :material-check: | :material-check: |
|      **V2Box**      |                  | :material-close: | :material-close: |
|   **Clash Meta**    |                  | :material-close: | :material-close: |
| **Clash Verge Rev** |                  | :material-close: | :material-close: |
|     **FLClash**     |                  | :material-close: | :material-close: |
|   **AmneziaVPN**    |                  | :material-close: | :material-check: |
|    **WG Tunnel**    |                  | :material-close: | :material-check: |

---

## تعداد ستاره‌ها به مرور زمان

[![تعداد ستاره‌ها به مرور زمان](https://starchart.cc/bia-pain-bache/BPB-Worker-Panel.svg?variant=adaptive)](https://starchart.cc/bia-pain-bache/BPB-Worker-Panel)
