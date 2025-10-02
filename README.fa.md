<div align="center" dir="rtl">

# یادگیری مارک‌دون

یک راهنمای جامع و کاربردی برای مارک‌دون به زبان فارسی — ساخته‌شده با _mdBook_.  
 این پروژه یک راهنمای ساختاریافته برای درک مارک‌دون، کاربردهای آن و ابزارهای مرتبط است.

[![CI](https://img.shields.io/github/actions/workflow/status/ackreq/mdlearn/mdbook.yml?logo=github)][ci]&nbsp;
[![GitHub license](https://img.shields.io/github/license/ackreq/mdlearn?color=white)][license]&nbsp;
[![Last Commit](https://img.shields.io/github/last-commit/ackreq/mdlearn?color=blueviolet)][Last Commit]&nbsp;

[**پیش‌نمایش زنده** ←][demo]
[![Devices Mockup](src/files/showcase.png)][demo]

</div>

## 📑 فهرست مطالب

#### مارک‌دون

- **مارک‌آپ و آغازمارک‌دون**  
  آشنایی با زبان‌های نشانه‌گذاری و این‌که چرا مارک‌دون به انتخاب اصلی برای مستندسازی تبدیل شد.
- **کاربردها و مزایا**  
  از مستندسازی و یادداشت‌برداری گرفته تا وبلاگ‌نویسی و فراتر از آن.
- **ویرایشگرها**  
  مروری بر ویرایشگرهای پیشنهادی در سیستم‌عامل‌های مختلف.
- **قواعد پایه**  
  بررسی دستورها، نکته‌ها و بهترین روش‌های نوشتن مارک‌دون.
- **مارک‌دون گسترش‌یافته**  
  نسخه‌های توسعه‌یافته مانند GFM و این‌که چگونه قابلیت‌های بیشتری به نسخه اصلی اضافه می‌کنند.
- **راهنمای سریع**  
  یک راهنمای سریع برای قواعد قالب‌بندی در مارک‌دون

#### پنداک (Pandoc)

- **آشنایی با پنداک**  
  پنداک چیست و چرا ابزاری قدرتمند برای تبدیل اسناد بین فرمت‌های مختلف است.
- **رابط خط فرمان**  
  خط فرمان چیست، چه تفاوتی با رابط‌های گرافیکی (GUI) دارد و چرا برای کار با پنداک ضروری است.
- **نحوه کارکرد پنداک**  
  پنداک چگونه یک سند را می‌خواند، پردازش می‌کند و در قالب دلخواه خروجی می‌دهد.
- **نصب و راه‌آندازی**  
  راهنمای گام‌به‌گام برای نصب پنداک و آماده‌سازی محیط.
- **تبدیلات ساده**  
  نحوه تبدیل مارک‌دون به HTML، LaTeX یا PDF و تغییر تنظیمات مطابق نیاز.
- **تنظیمات از پیش تعریف‌شده یا آماده**  
  چطور گزینه‌های متداول را در فایل‌های YAML ذخیره کنیم تا هم قابل استفاده‌ی مجدد باشند و هم دستورات ساده‌تر شوند.

## 📚 روش مطالعه

- **آنلاین:** قابل دسترسی از طریق [GitHub Pages](https://ackreq.github.io/mdlrean).
- **آفلاین:** ساخت و اجرای کتاب به‌صورت محلی (دستورالعمل‌ها در ادامه).

## 🛠️ ساخت به‌صورت محلی

```sh
# نصب mdBook:
cargo install mdbook mdbook-admonish

# کلون کردن مخزن:
git clone --depth=1 https://github.com/ackreq/mdlearn.git

# ورود به پروژه و اجرای کتاب:
cd mdlearn
mdbook serve --open
```

## 🌱 مشارکت

پروژه حاضر متن‌باز است و از بازخوردها و مشارکت‌ ها استقبال می‌شود.  
در صورت یافتن خطا، داشتن پیشنهاد برای بهبود پروژه یا اضافه کردن محتوای بیشتر، می‌توانید Pull Request ارسال کنید یا Issue ثبت کنید.

## 📜 حق نشر و مجوز

این پروژه شامل محتوایی اقتباس‌شده از [_The Markdown Guide_ اثر Matt Cone](https://www.markdownguide.org/) است که تحت مجوز [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) منتشر شده.  
تمام محتوای اصلی این پروژه نیز تحت همان مجوز [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) منتشر شده است.

[ci]: https://github.com/ackreq/mdlearn/actions/workflows/mdbook.yml?query=event%3Apush+branch%3Amain
[license]: https://github.com/ackreq/mdlearn/blob/main/LICENSE
[demo]: https://ackreq.github.io/mdlearn
[Last Commit]: https://github.com/ackreq/mdlearn/commits/main
