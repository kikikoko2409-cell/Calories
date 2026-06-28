# 🔥 حاسبة السعرات اليومية — PWA

تطبيق تتبع السعرات والماكرو يعمل كتطبيق مستقل على الهاتف.

## 🚀 خطوات النشر على GitHub Pages

### 1. أنشئ Repository جديد
- اذهب إلى [github.com/new](https://github.com/new)
- سمّه: `calorie-tracker`
- اجعله **Public**
- اضغط **Create repository**

### 2. ارفع الملفات
اسحب وأفلت هذه الملفات على صفحة الـ Repository:
```
index.html
manifest.json
sw.js
icons/
  icon-192.svg
  icon-512.svg
```

أو استخدم Git:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/USERNAME/calorie-tracker.git
git push -u origin main
```

### 3. فعّل GitHub Pages
- اذهب لـ Settings → Pages
- Source: **Deploy from a branch**
- Branch: **main** → **/ (root)**
- اضغط **Save**

### 4. رابطك سيكون
```
https://USERNAME.github.io/calorie-tracker/
```

### 5. تثبيت التطبيق على الهاتف
- افتح الرابط في **Chrome** (أندرويد)
- ستظهر رسالة "إضافة للشاشة الرئيسية" تلقائياً
- اضغط **تثبيت**
- التطبيق يفتح بدون شريط متصفح ويعمل **offline** ✅

## ✨ المميزات
- يعمل بدون إنترنت (Service Worker)
- قاعدة بيانات 166+ صنف غذائي
- تحليل ذكاء اصطناعي للوجبات
- تتبع 7 أيام مع سجل كامل
- إضافة صور للوجبات
