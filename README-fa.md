<p align="center">
  <img
    src="https://raw.githubusercontent.com/MRThugh/MRThugh/main/badge.svg"
    width="50%"
  />
</p>

# 🎨 Colorify v3 Pro — استودیوی هوشمند ساخت پالت رنگ

*اینجا رنگ‌ها الکی نیستن—طراحی شدن.*

![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-blue.svg)
![Language](https://img.shields.io/badge/Language-JavaScript-yellow)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen)
![Last Commit](https://img.shields.io/github/last-commit/MRThugh/Colorify)
![Repo Size](https://img.shields.io/github/repo-size/MRThugh/Colorify)
![Stars](https://img.shields.io/github/stars/MRThugh/Colorify?style=social)
![Forks](https://img.shields.io/github/forks/MRThugh/Colorify?style=social)

---

## فلسفه

*طراحی از رنگ شروع می‌شه—Colorify کمک می‌کنه راحت پالت رنگِ درست و حسابی رو پیدا کنی.*

---

# فهرست مطالب

- درباره  
- امکانات  
- شروع کار  
- مثال استفاده  
- تکنولوژی‌های استفاده‌شده  
- مشارکت  
- مجوز  
- نویسنده  

---

# درباره

**Colorify v3 Pro** یه ابزار مدرن برای ساخت و مدیریت پالت رنگه که توی مرورگر کار می‌کنه؛ مخصوص طراح‌ها و دولوپرها.

پالت‌های هماهنگ تولید می‌کنه، کنتراست دسترس‌پذیری (accessibility) رو بررسی می‌کنه، و اجازه می‌ده پالت‌ها رو توی چند مدل خروجی بگیری.

با یه رابط کاربری شیک، تولید رنگ هوشمند، و ابزارهای تحلیل داخلی، تجربه‌ی کشف رنگ‌ها می‌شه یه کار ساده و خوشحال‌کننده.

---

# امکانات

- 🎨 **سازنده‌ی هوشمند پالت** — همون لحظه پالت‌های قشنگ و تصادفی بساز  
- 🔒 **قفل کردن رنگ‌ها** — رنگ‌های انتخاب‌شده رو نگه دار، بقیه رو دوباره تولید کن  
- 📊 **تحلیل پیشرفته‌ی رنگ** — روشنایی (luminance)، بازه‌ی تون (hue)، و کنتراست WCAG  
- 📈 **ویژوال‌سازی هارمونی** — نمودار تعاملی چرخ رنگ و هماهنگی‌ها  
- 💾 **ذخیره‌سازی پالت** — ذخیره‌ی محلی با دسته‌بندی  
- 📦 **خروجی/ورودی JSON** — پالت‌ها رو بین پروژه‌ها به اشتراک بذار  
- 🖼️ **خروجی PNG** — دانلود پالت به شکل تصویر (asset)  
- 📋 **کپی تک‌کلیکی** — HEX رنگ‌ها رو سریع کپی کن  
- 🌗 **حالت تیره/روشن** — جابه‌جایی نرم و روان تم  
- ⚡ **تعامل آنی** — میانبرهای کیبورد و انیمیشن  

---

# شروع کار

ریپو رو کلون کن و پروژه رو توی مرورگرت باز کن.

```bash
git clone https://github.com/MRThugh/colorify.git

cd colorify

# فایل اصلی رو باز کن
index.html
```

تمومه.

هیچ فرایند بیلد نداره.  
وابستگی هم لازم نیست نصب کنی.

فایل رو باز کن و شروع کن به ساخت پالت.

---

# مثال استفاده

پالت رو برنامه‌نویسی‌طور بساز:

```javascript
function randomColor(){
  const h = randInt(0,360)
  const s = randInt(55,85)
  const l = randInt(35,70)
  return hslToHex(h,s,l)
}

palette.push(randomColor())
renderPalette()
```

*ساده، سریع، شیک.*

---

# تکنولوژی‌های استفاده‌شده

- ⚡ **JavaScript (Vanilla)**  
- 🎨 **TailwindCSS**  
- 🧠 **Canvas API**  
- 🌐 **HTML5**  
- 💾 **LocalStorage API**  

---

# مشارکت

ما از مشارکت کردن شما عزیزان استقبال میکنیم :).

اگه دوست داری Colorify رو بهتر کنی—چه با بهتر کردن UI، چه با بهینه‌سازی الگوریتم‌های ساخت پالت، یا اضافه کردن فرمت‌های خروجی جدید—آزادانه یه Issue باز کن یا Pull Request بفرست.

ایده‌های خلاقانه همیشه باحال‌اند.

---

# مجوز

این پروژه **Open Source** هست و تحت **MIT License** منتشر شده.

آزاد هستی ازش استفاده کنی، تغییرش بدی، و طبق شرایط لایسنس توزیعش کنی.

---

# نویسنده

**Ali Kamrani**  
*معمارِ خاموش*  

GitHub:  
https://github.com/MRThugh

---

*ابزارهای طراحی میان و می‌رن—ولی رنگ خوب همیشه می‌مونه.*.
