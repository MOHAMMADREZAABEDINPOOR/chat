<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="PIMX CHAT · DJANGO: a desktop conversation with account and message cards" />

**[English](README.md) · [فارسی](README.fa.md)**

</div>

<div dir="rtl">

# 💬 PIMX CHAT · DJANGO

برنامه گفتگو با Django، مدیریت حساب، ذخیره مکالمه، فایل استاتیک و اتصال پاسخ هوش مصنوعی.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/chat) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [بنر ثابت](assets/readme/hero.png)

| نمای کلی | جزئیات |
|:---|:---|
| 💬 تجربه | برنامه وب / تجربه مرورگری |
| 🧰 فناوری | `Django==4.2.7` · `djangorestframework==3.14.0` · `django-cors-headers==4.3.1` · `django-allauth==0.57.0` |
| 🌐 زبان راهنما | [English](README.md) · [فارسی](README.fa.md) |

[✨ امکانات](#امکانات) · [🚀 شروع کار](#شروع-کار) · [⚙️ تنظیمات](#تنظیمات) · [🌍 استقرار](#استقرار)

---

<a id="امکانات"></a>

## ✨ امکانات

| بخش | قابلیت موجود |
|:---|:---|
| 👤 حساب‌ها | اپ‌های حساب و گفتگو در Django |
| 🧠 هوشمندی | مدل مکالمه و رابط مبتنی بر قالب |
| ⚡ روند کار | فایل استاتیک و وابستگی مرتبط با استقرار |
| 🧠 هوشمندی | پکیج Google AI در فهرست وابستگی |

<a id="پشته-فنی"></a>

## 🧰 پشته فنی

| ابزار | نسخه یا منبع |
|---|---|
| Django==4.2.7 | `requirements.txt` |
| djangorestframework==3.14.0 | `requirements.txt` |
| django-cors-headers==4.3.1 | `requirements.txt` |
| django-allauth==0.57.0 | `requirements.txt` |
| Pillow==10.1.0 | `requirements.txt` |
| django-celery-beat==2.5.0 | `requirements.txt` |
| django-celery-results==2.5.1 | `requirements.txt` |
| django-extensions==3.2.3 | `requirements.txt` |
| django-debug-toolbar==4.2.0 | `requirements.txt` |
| django-storages==1.14.2 | `requirements.txt` |
| django-redis==5.4.0 | `requirements.txt` |
| django-user-agents==0.4.0 | `requirements.txt` |

<a id="شروع-کار"></a>

## 🚀 شروع کار

Python 3 و محیط دسکتاپ برای پروژه‌های Tkinter/Turtle؛ Tkinter از اجزای نصب Python است و با pip نصب نمی‌شود. برای وابستگی‌های قدیمی از نسخه Python سازگار استفاده کنید.

<div dir="ltr">

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/chat.git
cd chat

python -m venv .venv
# Windows: .venv\Scripts\Activate.ps1; macOS/Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

</div>

<a id="تنظیمات"></a>

## ⚙️ تنظیمات

کلیدهای زیر از فایل نمونه یا کد استخراج شده‌اند؛ همه الزاماً اجباری نیستند. مقدار و پیش‌فرض را در همان فایل بررسی و اسرار را فقط در محیط محلی یا هاست تنظیم کنید.

| نام | کاربرد |
|---|---|
| `DJANGO_ALLOW_MEDIA` | تنظیم برنامه؛ تعریف را در منبع بررسی کنید |

<a id="استفاده"></a>

## 🎯 استفاده

وابستگی را در محیط مجازی نصب، config/settings.py و تنظیم هوش مصنوعی را بررسی، مایگریشن و سپس سرور محلی را اجرا کنید.

<a id="ساختار-پروژه"></a>

## 🗂️ ساختار پروژه

| مسیر | نقش |
|---|---|
| [`accounts/`](accounts/) | اپ حساب |
| [`assets/`](assets/) | فایل برند، رسانه و README |
| [`pimxchat/`](pimxchat/) | ماژول گفتگو و وب |
| [`static/`](static/) | فایل استاتیک وب |
| [`templates/`](templates/) | قالب سمت سرور |
| [`manage.py`](manage.py) | فایل ورودی یا تنظیم پروژه |

<a id="فرمان‌ها-و-بررسی"></a>

## 🧪 فرمان‌ها و بررسی

<div dir="ltr">

```bash
python manage.py check
python manage.py test
```

</div>

<a id="استقرار"></a>

## 🌍 استقرار

فایل محیط واقعی، HTTPS، دیتابیس مستقل و میزبان مجاز تنظیم کنید. در PHP ریشه وب را public/ و در Django فایل استاتیک و WSGI/ASGI را تنظیم کنید. سرور توسعه برای میزبانی عمومی نیست.

<a id="محدودیت‌ها"></a>

## 📌 محدودیت‌ها

نسخه مخزن داده و تنظیم توسعه و توضیحات نسخه قدیمی دارد. از دیتابیس محلی تازه استفاده و پیش از میزبانی اسرار، میزبان مجاز و فایل استاتیک را بررسی کنید.

<a id="رفع-مشکل"></a>

## 🛠️ رفع مشکل

- پکیج غایب: وابستگی را با مدیر پکیج پروژه نصب کنید.
- خطای API یا شبکه: آدرس، سرویس و اتصال میزبانی را بررسی کنید.
- فایل قدیمی: در صورت وجود اسکریپت ساخت، build و کش مرورگر را تازه کنید.

<a id="مشارکت"></a>

## 🤝 مشارکت

برای تغییر، شاخه مستقل بسازید، رفتار فعلی را بررسی کنید و توضیح روشن همراه تغییر بفرستید. اطلاعات خصوصی، خروجی build و دیتابیس محلی را commit نکنید.

<a id="مجوز"></a>

## 📄 مجوز

فایل مجوز در این نسخه موجود نیست. نمایش عمومی کد به‌تنهایی مجوز استفاده مجدد نیست؛ برای شرایط استفاده با مالک مخزن هماهنگ کنید.

---

ساخته‌شده در مجموعه **PIMX** · مستندات فارسی و انگلیسی.

---

<div align="center">

💬 **PIMX CHAT · DJANGO** · [English](README.md) · [فارسی](README.fa.md)

</div>

</div>
