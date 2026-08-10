# صفحات App Store فانگلیش برای iOS

این مخزن یک سایت استاتیک مستقل برای دو URL موردنیاز App Store است و هیچ مسیر خرید، اشتراک یا پرداختی ندارد.

- `support/` — Support URL
- `privacy/` — Privacy Policy URL

## انتشار با GitHub Pages

1. یک مخزن جدید در GitHub بسازید؛ برای نمونه `funglish-ios-pages`.
2. محتویات همین پوشه را در شاخه `main` پوش کنید.
3. در **Settings → Pages**، بخش **Build and deployment** را روی **Deploy from a branch**، سپس `main` و پوشه `/(root)` قرار دهید.
4. پس از انتشار، اگر آدرس مخزن `funglish-ios-pages` باشد، URLها به شکل زیر خواهند بود:

   - `https://<github-username>.github.io/funglish-ios-pages/support/`
   - `https://<github-username>.github.io/funglish-ios-pages/privacy/`

## زیردامنهٔ پیشنهادی

برای استفاده از URL رسمی‌تر، یک زیردامنه مانند `ios.funglish.app` را در تنظیمات GitHub Pages متصل کنید و رکورد DNS لازم را مطابق راهنمای GitHub اضافه کنید. در آن صورت URLها این‌ها خواهند بود:

- `https://ios.funglish.app/support/`
- `https://ios.funglish.app/privacy/`

قبل از ارسال نسخه به App Review، متن بخش پردازش، ارسال و نگهداری صدای کاربر را با رفتار build نهایی iOS و تمام SDKهای آن تطبیق دهید.
