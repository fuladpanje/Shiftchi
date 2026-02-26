# راهنمای انتشار صفحات Privacy Policy و Terms of Service

## مرحله 1: آپلود به GitHub

### گزینه A: اگر قبلاً GitHub دارید

1. این پوشه `docs` را به repository خود اضافه کنید
2. Commit و Push کنید:
```bash
git add docs/
git commit -m "Add privacy policy and terms of service"
git push
```

### گزینه B: اگر GitHub ندارید

1. به [github.com](https://github.com) بروید و ثبت‌نام کنید
2. یک repository جدید بسازید (مثلاً `shiftchi-privacy`)
3. فایل‌های داخل پوشه `docs` را آپلود کنید

## مرحله 2: فعال‌سازی GitHub Pages

1. به repository خود بروید
2. به **Settings** بروید
3. از منوی سمت چپ **Pages** را انتخاب کنید
4. در قسمت **Source**:
   - Branch: `main` (یا `master`)
   - Folder: `/docs`
5. روی **Save** کلیک کنید

## مرحله 3: دریافت لینک‌ها

بعد از 2-3 دقیقه، صفحات شما در این آدرس‌ها در دسترس خواهند بود:

```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/privacy-policy.html
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/terms-of-service.html
```

## مرحله 4: استفاده در Google Console

این لینک‌ها را در Google Cloud Console وارد کنید:

- **Application home page**: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
- **Privacy policy link**: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/privacy-policy.html`
- **Terms of service link**: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/terms-of-service.html`

## نکات مهم

✅ **قبل از ارسال به Google:**
- لینک‌ها را در مرورگر باز کنید و مطمئن شوید کار می‌کنند
- ایمیل `support@shiftchi.app` را با ایمیل واقعی خود جایگزین کنید
- اگر اپلیکیشن در Play Store منتشر کردید، لینک Play Store را در `index.html` اضافه کنید

✅ **بعد از تایید Google:**
- این لینک‌ها را در اپلیکیشن Flutter خود نیز اضافه کنید (در صفحه تنظیمات)

## سوالات متداول

**Q: آیا باید دامنه اختصاصی داشته باشم؟**
A: خیر، GitHub Pages کافی است.

**Q: آیا این صفحات رایگان هستند؟**
A: بله، GitHub Pages کاملاً رایگان است.

**Q: چطور محتوا را ویرایش کنم؟**
A: فایل‌های HTML را ویرایش کنید و دوباره push کنید.

**Q: چند وقت طول می‌کشد تا تغییرات اعمال شود؟**
A: معمولاً 1-2 دقیقه.
