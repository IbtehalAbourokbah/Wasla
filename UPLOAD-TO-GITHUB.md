# كيف ترفعين هذا إلى GitHub

المستودع: **https://github.com/IbtehalAbourokbah/Wasla** (عام، بلا commits حتى الآن)

> **لماذا يدوياً؟** لا يوجد موصل (connector) لـ GitHub داخل محادثات claude.ai على هذا الحساب —
> تم التحقق في 2026-10-04 ولم يظهر في دليل الموصلات. وبما أن المستودع فارغ بلا فرع افتراضي،
> لا يستطيع Claude Code استنساخه أيضاً. الرفع اليدوي يحل المشكلتين معاً.

---

## الطريقة الأسهل — بلا git وبلا طرفية (٣ دقائق)

1. فُكّي ضغط `wasla-repo.zip` على جهازك. ستحصلين على مجلد فيه `README.md` و `docs` و `prototype` و `assets`.
2. افتحي **https://github.com/IbtehalAbourokbah/Wasla**
3. اضغطي **uploading an existing file** (الرابط يظهر في صفحة المستودع الفارغ).
   إن لم يظهر: **Add file ← Upload files**.
4. **اسحبي محتويات المجلد** — أي `README.md` والمجلدات الثلاثة — وأفلتيها في الصفحة.
   ⚠️ اسحبي *ما بداخل* المجلد، لا المجلد نفسه، وإلا صار كل شيء داخل مجلد زائد.
5. في خانة الوصف اكتبي: `أول نسخة: النموذج الأولي والتوثيق الكامل`
6. اضغطي **Commit changes**

انتهى. المستودع صار فيه أول commit، وصار Claude Code قادراً على استنساخه لاحقاً.

> الرفع قد يستغرق دقيقة — مجلد `prototype` فيه ملفان حجمهما ~٩٠٠ كيلوبايت مجتمعين.

---

## لعرض النموذج كصفحة ويب مباشرة (اختياري، دقيقتان)

يعطيكِ رابطاً دائماً يعمل بلا claude.ai — مفيد كخطة بديلة يوم التحكيم:

1. في المستودع: **Settings ← Pages**
2. تحت **Source** اختاري `Deploy from a branch`
3. الفرع `main` والمجلد `/ (root)` ← **Save**
4. انتظري دقيقة، ثم افتحي:
   `https://ibtehalabourokbah.github.io/Wasla/prototype/index.html`

---

## بـ git من الطرفية (إن كان مثبّتاً)

```bash
cd المسار/إلى/المجلد-بعد-فك-الضغط
git init
git add .
git commit -m "أول نسخة: النموذج الأولي والتوثيق الكامل"
git branch -M main
git remote add origin https://github.com/IbtehalAbourokbah/Wasla.git
git push -u origin main
```

---

## بعد الرفع

- حدّثي `docs/07-github-setup.md` بتاريخ أول commit.
- لأي تعديل لاحق على النموذج: استخدمي **https://claude.ai/code** واختاري مستودع `Wasla` —
  سيستنسخه Claude ويفتح Pull Request. (هذا يعمل فقط بعد وجود أول commit.)
