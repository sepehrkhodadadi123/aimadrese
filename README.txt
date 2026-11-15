ای‌آی مدرسه — نسخه Gemini برای Netlify

1) در https://aistudio.google.com/api-keys کلید بسازید.
2) در Netlify > Project configuration > Environment variables متغیر GEMINI_API_KEY را با مقدار کلید تنظیم کنید؛ کلید را در فایل‌ها نگذارید.
3) کل پروژه را به روش پشتیبانی‌کننده از Netlify Functions (اتصال Git یا Netlify CLI) منتشر کنید. آپلود ساده پوشه در Netlify Drop ممکن است توابع سمت سرور را منتشر نکند.
4) پس از انتشار و تنظیم متغیر، یک deploy تازه ایجاد کنید.
5) برای تست فقط یک نفر؛ قبل از استفاده عمومی محدودیت درخواست و احراز هویت اضافه شود.
