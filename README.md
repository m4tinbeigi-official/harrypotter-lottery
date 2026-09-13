<!-- DevSponsors Badges -->
<p align="center">
  <a href="https://devsponsors.github.io"><img src="https://img.shields.io/badge/DevSponsors-Verified_OSS-6366f1?style=for-the-badge&logo=github" alt="DevSponsors Verified"></a>
  <a href="https://devsponsors.github.io"><img src="https://img.shields.io/badge/Sponsor-DevSponsors_Hub-emerald?style=for-the-badge&logo=github-sponsors" alt="DevSponsors Sponsor"></a>
  <a href="https://devsponsors.github.io/mediakit.html"><img src="https://img.shields.io/badge/Infrastructure-DevSponsors_Cloud-ec4899?style=for-the-badge&logo=server" alt="DevSponsors Cloud"></a>
</p>

# ⚡ سامانه قرعه‌کشی شفاف بلیت تئاتر هری پاتر | Harry Potter Lottery

> **سامانه متن‌باز، شفاف و کلاینت‌ساید قرعه‌کشی مسابقه اینستاگرام نوشین ناصری برای همراهی در تئاتر هری پاتر و فرزند نفرین‌شده**

---

## 🎯 درباره پروژه و تضمین شفافیت (Fair Play & Transparency)

این پروژه با هدف برگزاری یک قرعه‌کشی **کاملاً سالم، شفاف، عمومی و غیرقابل دستکاری** برای همراهان اینستاگرام و علاقه‌مندان به تئاتر هری پاتر طراحی و به صورت متن‌باز (Open Source) روی گیت‌هاب پیجز مستقر شده است.

### 🛡️ چرا این قرعه‌کشی ۱۰۰٪ شفاف و بدون تقلب است؟

1. **متن‌باز و بازرسی‌پذیر توسط عموم (Open Source):**
   تمام کدهای این سامانه (شامل HTML, CSS, JavaScript) به صورت کاملاً عمومی در این ریپازیتوری در دسترس است و هر شخصی می‌تواند خط به خط منطق قرعه‌کشی را بررسی کند.

2. **پردازش کاملاً کلاینت‌ساید (Client-side Execution):**
   هیچ سرور مخفی، پایگاه‌داده اختصاصی یا الگوریتم پشت‌پرده‌ای وجود ندارد. قرعه‌کشی به صورت زنده در مرورگر کاربر و با توابع استاندارد جاوااسکریپت اجرا می‌شود.

3. **داده‌های خام و قابل راستی‌آزمایی (NovinHub Verified Raw Data):**
   فایل خروجی رسمی کامنت‌ها مستقیماً از سامانه مجاز نوین‌هاب دریافت شده و فایل خام آن (`export.xlsx` و `participants.json`) داخل همین ریپازیتوری قرار دارد. هر کاربری می‌تواند کامنت و آیدی خود را در لیست ۱۱۷ نفره بررسی و تطبیق دهد.

4. **الگوریتم تصادفی عادلانه (Fisher-Yates Shuffle & Uniform Random):**
   انتخاب نام‌ها با توابع تصادفی استاندارد و توزیع یکنواخت انجام می‌شود و تمامی شرکت‌کنندگان شانس کاملاً برابر دارند.

---

## 🎭 مشخصات رویداد و عوامل

- **برگزارکننده و میزبان:** نوشین ناصری ([@nooshinaseri](https://instagram.com/nooshinaseri))
- **عنوان نمایش:** تئاتر هری پاتر و فرزند نفرین‌شده
- **پیج رسمی تئاتر:** [@harrypottertheatre](https://instagram.com/harrypottertheatre)
- **سامانه رسمی تهیه بلیت:** [سایت تیوال (tiwall.com/p/harrypotter3)](https://www.tiwall.com/p/harrypotter3)
- **پست مسابقه اینستاگرام:** [مشاهده پست ریلز در اینستاگرام](https://www.instagram.com/reel/DdMSPMRBEZL/)

---

## ✨ امکانات فنی و بصری سامانه

- 🪄 **طراحی جادویی سبک هاگوارتز:** بهره‌گیری از تایپوگرافی چشم‌نواز، افکت‌های صوتی جادویی (Web Audio API) و انیمیشن جام آتش (Goblet of Fire).
- 📜 **بارگذاری خودکار ۱۱۷ شرکت‌کننده:** خواندن مستقیم کامنت‌ها از فایل نوین‌هاب با امکان آپلود مجدد و حذف موارد تکراری.
- 🏆 **تعیین برنده و رزرو:** استخراج برنده اصلی همراه با نفرات ذخیره برای جلوگیری از اتلاف وقت در صورت عدم پاسخگویی نفر اول.
- 📱 **تولید خودکار پوستر استوری اینستاگرام:** رسم و دانلود خودکار پوستر با کیفیت بالا (1080x1920) با اطلاعات کامل رویداد، آیدی برنده و مشخصات تئاتر جهت انتشار شفاف در استوری.

---

## 🚀 مشاهده آنلاین و نحوه اجرا

سامانه به صورت خودکار و بدون نیاز به نصب هیچ‌گونه ابزار اضافی، از طریق لینک زیر قابل استفاده است:

👉 **[ورود به صفحه قرعه‌کشی آنلاین](https://m4tinbeigi-official.github.io/harrypotter-lottery/)**

---

### 💻 اجرای محلی (Local Run)

برای تست و بررسی محلی کدها:

```bash
git clone https://github.com/m4tinbeigi-official/harrypotter-lottery.git
cd harrypotter-lottery
# باز کردن فایل index.html در مرورگر دلخواه
open index.html
```

---

<div align="center">
  <sub>طراحی شده برای ایجاد تجربه شفاف، هیجان‌انگیز و منصفانه برای تمامی طرفداران هری پاتر 🪄</sub>
</div>
