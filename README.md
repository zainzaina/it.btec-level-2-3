# BTEC IT - موقع قسم مدرسة عائشة أم المؤمنين

موقع بسيط لقسم BTEC IT — صفحات HTML ثابتة (RTL - عربي).

## وصف
موقع تعريفي لقسم BTEC IT يحتوي على: `index.html` (الصفحة الرئيسية)، ومجلد `src/` لصفحات داخلية و`assets/` للصور والوسائط.

## بنية المشروع
- `index.html` — الصفحة الرئيسية (تفتح أولاً).
- `assets/` — صور وشعارات وفيديوهات.
- `src/` — صفحات داخلية مثل `about.html`, `projects.html`, `teachers.html`, `library.html`, `contact.html`, `Success stories.html`, `developers.html`.

## معاينة محليًا
1. افتح الطرفية في مجلد المشروع (`c:\Users\zain2\Downloads\it.btec`).
2. لتشغيل خادم HTTP بسيط عبر Python (إذا مثبت):

```bash
python -m http.server 8000
```
ثم افتح المتصفح على `http://localhost:8000/it%20btec/` أو مباشرة `http://localhost:8000/it%20btec/index.html` حسب مسار الملف.

بديل (فتح الملف محليًا): افتح `it btec/index.html` مباشرة في المتصفح.

## نشر إلى GitHub
1. أنشئ مستودعًا على GitHub (مثلاً `USERNAME/REPO`).
2. ربط الريموت ودفع الفرع `main`:

```bash
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git add .
git commit -m "Prepare site for GitHub Pages"
git push -u origin main
```
3. في صفحة المستودع على GitHub: Settings → Pages → Source = `main` branch, Folder = `/ (root)` ثم `Save`.

## ملاحظات
- أزلنا ظهور اسم "شهد" حسب طلبك؛ بقيت الإشارة إلى `زين` باعتبارها المطورة.
- إذا تريد نشر تلقائي عبر GitHub Actions أستطيع إنشاء ملف `.github/workflows/gh-pages.yml` أيضاً.

## الحقوق
جميع الحقوق محفوظة © 2025 - زين نوفان أبو زيد
