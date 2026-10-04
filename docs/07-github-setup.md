# المستودع و GitHub Pages

**آخر تحديث:** 2026-10-04

## الحالة

- **المستودع:** https://github.com/IbtehalAbourokbah/Wasla (عام)
- **الحساب:** `IbtehalAbourokbah`
- **الفرع الافتراضي:** `claude/charming-feynman-qdgxxu` — ⚠️ ليس `main` ولا `master`.
  أي أمر git أو إعداد يجب أن يشير إلى هذا الاسم.
- **GitHub Pages:** مفعّل ويعمل · المصدر: هذا الفرع · المجلد `/ (root)`
- **الرابط المباشر:** https://ibtehalabourokbah.github.io/Wasla/

## إعادة تسمية الفرع إلى `main` (اختياري)

⚠️ GitHub ينبّه أن إعادة التسمية **ستُلغي نشر موقع Pages الحالي**. الخطوات:

1. Settings ← General ← Default branch ← أيقونة القلم ← اكتبي `main` ← Rename
2. Settings ← Pages ← Branch ← اختاري `main` و `/ (root)` ← Save
3. انتظري دقيقة، ثم تأكّدي أن https://ibtehalabourokbah.github.io/Wasla/ يعمل
4. حدّثي اسم الفرع في `README.md` و `docs/00-HANDOFF.md`

## رفع تعديلات لاحقاً

**الأسهل (بلا git):** افتحي الملف على github.com ← أيقونة القلم ← عدّلي ← Commit.
لملف جديد: Add file ← Upload files ← اسحبيه ← Commit. رفع ملف بنفس الاسم يستبدله.

**عبر Claude Code:** https://claude.ai/code ← Select repository ← `IbtehalAbourokbah/Wasla`.
يعمل الآن لأن المستودع فيه commits وفرع افتراضي.

**عبر git:**
```bash
git clone https://github.com/IbtehalAbourokbah/Wasla.git
cd Wasla
# عدّلي index.html
git add . && git commit -m "وصف التعديل" && git push
```

## قيد معروف

لا يوجد موصل (connector) لـ GitHub داخل محادثات claude.ai — تم التحقق في 2026-10-04.
الرفع يدوي أو عبر Claude Code.
