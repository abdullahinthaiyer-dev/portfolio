# Abdullah Majid Intheer — Surveying & GIS Engineer | Portfolio

موقع بورتفوليو شخصي (صفحة واحدة) لمهندس مساحة وGIS، مبني بـ HTML/CSS/JS خالص بدون أي إطار عمل، وجاهز للنشر مباشرة عبر GitHub Pages.

🔗 **المعاينة المباشرة (بعد التفعيل):** `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 📁 هيكل الملفات

```
.
├── index.html              ← الصفحة الرئيسية (كل التصميم والسكربتات بداخلها)
├── Abdullah_Majid_CV.pdf   ← السيرة الذاتية القابلة للتحميل والمعاينة من الموقع
├── README.md               ← هذا الملف
└── images/                 ← 📸 أنشئ هذا المجلد وضع فيه صورك (انظر القائمة أدناه)
```

> ⚠️ مجلد `images/` غير موجود بعد — أنشئه يدوياً وضع فيه الصور التالية بنفس الأسماء ليحل الموقع الصناديق الفارغة (📷) محلها تلقائياً بمجرد ربط مسارها في `index.html`.

## 🖼️ الصور المطلوبة (Placeholders داخل الموقع)

| الاسم المقترح | أين تُستخدم |
|---|---|
| `profile-photo.jpg` | الصورة الشخصية في القسم الترحيبي (بدل الحروف AM) |
| `og-cover.jpg` | صورة المشاركة عند نشر الرابط على LinkedIn/فيسبوك (1200×630px) |
| `west-qurna-map.jpg` | خريطة مسار مشروع West Qurna 2 |
| `west-qurna-civil3d.jpg` | لقطة شاشة من Civil 3D لمشروع West Qurna 2 |
| `west-qurna-field.jpg` | صورة ميدانية من موقع West Qurna 2 |
| `empire-downtown-map.jpg` | مخطط توزيع وحدات Empire Downtown |
| `empire-downtown-gis.jpg` | لقطة GIS لحالة الوحدات |
| `empire-downtown-field.jpg` | صورة ميدانية من الموقع |
| `ftth-network-map.jpg` | خريطة مسار شبكة FTTH |
| `ftth-gis-design.jpg` | لقطة GIS لتصميم الشبكة |
| `ftth-field.jpg` | صورة ميدانية من التركيب |
| `webgis-screenshot.jpg` … `remote-screenshot.jpg` | لقطات شاشة حقيقية لكل بطاقة في قسم GIS Portfolio (8 صور) |

بعد إضافة الصور، افتح `index.html` وابحث عن كل عنصر بصيغة:
```html
<div class="img-slot"> ... </div>
```
واستبدله بـ:
```html
<img src="images/اسم-الملف.jpg" alt="وصف الصورة" style="width:100%;border-radius:12px;">
```

---

## 🚀 رفع المشروع على GitHub (خطوة بخطوة)

### 1) أنشئ مستودعاً جديداً على GitHub
اذهب إلى https://github.com/new واختر اسماً مثل `portfolio` ثم اضغط **Create repository** (اتركه بدون README لتفادي التعارض).

### 2) من جهازك، داخل مجلد المشروع نفّذ:
```bash
git init
git add .
git commit -m "Initial commit: portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git push -u origin main
```

### 3) فعّل GitHub Pages
1. في صفحة المستودع على GitHub، اذهب إلى **Settings → Pages**
2. تحت **Source** اختر **Deploy from a branch**
3. اختر الفرع **main** والمجلد **/ (root)**
4. احفظ، وانتظر دقيقة — سيظهر رابط موقعك في نفس الصفحة بالشكل:
   `https://YOUR-USERNAME.github.io/REPO-NAME/`

### 4) (اختياري) دومين مخصص
إن كان لديك دومين خاص، أضف ملف `CNAME` بداخله اسم الدومين، واربطه من إعدادات DNS الخاصة بمزود الدومين حسب [توثيق GitHub Pages](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

## ✏️ أشياء يفضّل تحديثها قبل الرفع

- [ ] استبدال رابط `github.com/YOUR-USERNAME` في قسم "Python GIS & GitHub" برابط حسابك الفعلي
- [ ] إضافة صورة `og-cover.jpg` (1200×630) لتظهر عند مشاركة الرابط
- [ ] إضافة صورتك الشخصية بدل الحروف الأولى (راجع تعليق داخل `index.html` قرب `<div class="avatar">`)
- [ ] استبدال نصوص التوصيات Placeholder بتوصيات حقيقية من مدرائك عند توفرها
- [ ] مراجعة إحداثيات "Interactive Portfolio Map" — هي تقريبية للعرض التوضيحي فقط

---

## 🛠️ التقنيات المستخدمة
- HTML5 / CSS3 (متغيرات CSS لدعم الوضع الداكن والفاتح)
- JavaScript خالص (بدون مكتبات UI)
- [Leaflet.js](https://leafletjs.com/) للخريطة التفاعلية
- خطوط Google Fonts: Tajawal, IBM Plex Mono

## 📄 الترخيص
هذا المشروع ملك شخصي لعبدالله ماجد انذير — يمكن التعديل والاستخدام بحرية لأغراضك الشخصية.
