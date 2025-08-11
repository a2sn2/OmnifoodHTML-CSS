# OmnifoodHTML+CSS

**Live demo:** [https://a2sn2.github.io/OmnifoodHTML-CSS/]

---

## Table of contents

* [Project goals](#project-goals)
* [File structure](#file-structure)
* [How to view locally](#how-to-view-locally)
* [CSS integration](#css-integration)
* [HTML + CSS walkthrough](#html--css-walkthrough)

  * [Header / Navigation](#header--navigation)
  * [Hero](#hero)
  * [Featured logos](#featured-logos)
  * [How it works](#how-it-works)
  * [Meals](#meals)
  * [Testimonials + Gallery](#testimonials--gallery)
  * [Pricing](#pricing)
  * [Call to Action (form)](#call-to-action-form)
  * [Footer](#footer)
* [Accessibility notes](#accessibility-notes)
* [Next steps (when JS is allowed)](#next-steps-when-js-is-allowed)

---

## Project goals

* إضافة ملف CSS خارجي لفصل المحتوى عن التنسيق.
* تطبيق تنسيقات متجاوبة (Responsive Design) بحيث تعمل على الشاشات المختلفة.
* استخدام خطوط وألوان متناسقة تعكس هوية Omnifood.
* جعل التجربة البصرية واضحة وسهلة الاستخدام.

---

## File structure

```
Omnifood-html/
├─ index.html
├─ styles.css            ← ملف التنسيقات الرئيسي
└─ img/
   ├─ omnifood-logo.png
   ├─ hero.webp
   ├─ customers/...
   ├─ app/...
   ├─ meals/...
   ├─ logos/...
   └─ gallery/...
```

> رابط CSS مضاف داخل `<head>`:

```html
<link rel="stylesheet" href="styles.css" />
```

---

## How to view locally

1. تأكد أن `index.html` و `styles.css` في نفس المجلد.
2. افتح `index.html` في أي متصفح.
3. لا حاجة لأي سيرفر — مجرد HTML + CSS.

---

## CSS integration

* ملف `styles.css` يحتوي على:

  * إعدادات الخطوط والألوان العامة.
  * تنسيقات العناوين والفقرات.
  * توزيع العناصر باستخدام Flexbox وGrid.
  * تنسيقات الصور (مثل القص، التوسيط، الظلال).
  * أقسام مخصصة لكل جزء من الصفحة (header, hero, meals...).
* تم استخدام Reset/Normalize بسيط لإزالة التباينات بين المتصفحات.

---

## HTML + CSS walkthrough

### Header / Navigation

* الشريط العلوي بخلفية ثابتة ولوجو محاذي يسار.
* الروابط تتحول للون مميز عند المرور (hover).

### Hero

* توزيع المحتوى على عمودين (نصوص يسار وصورة يمين).
* أزرار Call to Action بألوان مميزة وحواف دائرية.

### Featured logos

* عرض شعارات في صف أفقي مع تباعد متساوي.

### How it works

* ثلاث بطاقات Steps منظمة باستخدام Grid.
* أرقام الخطوات بارزة بخلفية دائرية.

### Meals

* بطاقات طعام مع ظل وborder-radius.
* قائمة الخصائص برموز أيقونات قبل النصوص.

### Testimonials + Gallery

* قسم اقتباسات على خلفية ملوّنة.
* شبكة صور 3×4 للمعرض.

### Pricing

* بطاقتا أسعار بتصميم متقابل.
* زر بارز في الأسفل لكل بطاقة.

### Call to Action (form)

* خلفية مميزة مع مربع تسجيل بيانات أبيض في المنتصف.
* الحقول والزر منسقة لتكون سهلة القراءة.

### Footer

* توزيع الأعمدة الثلاثة باستخدام Flexbox.
* نص الحقوق في الأسفل بمقاس صغير ولون باهت.

---

## Accessibility notes

* الألوان مختارة مع مراعاة تباين النصوص والخلفيات.
* التركيز (focus) على الروابط والأزرار واضح.
* الخطوط كبيرة بما يكفي للقراءة على الشاشات الصغيرة.

---
