# IT Administration — تطبيق Windows

نظام لإدارة قسم تقنية المعلومات: الأصول والعهد، رحلة الموظف (التوظيف والتعيين والإخلاء)، الخدمات التقنية والتجديدات، مصروفات IT، والربط مع Google Sheets أو Excel.

## التحميل
نزّل الملف **[ITAdministration.exe](ITAdministration.exe)** (اضغط عليه ثم زرار التحميل ⬇).

## التشغيل
1. شغّل `ITAdministration.exe`.
2. لو ويندوز ظهّر «Windows protected your PC»، اضغط **More info** ثم **Run anyway** (البرنامج مش موقّع رقميًا).
3. المتصفح هيفتح لوحده. أول مرة هتعمل حساب المدير.
4. أضف شركتك من «إدارة النظام»، واربط شيتات Google الخاصة بيك من «الربط والأتمتة» (أو استخدم ملف Excel محلي).

## ملاحظات
- بيشتغل **من غير إنترنت** — الإنترنت مطلوب بس وقت مزامنة شيتات Google.
- مش محتاج تثبيت Python أو أي برنامج تاني.
- بياناتك بتتحفظ على جهازك في `%LOCALAPPDATA%\ITAdministration`.
- لفتحه من أجهزة تانية على نفس الشبكة: `ITAdministration.exe --lan`
- لتغيير المنفذ: `ITAdministration.exe --port 8010`
- اقفل شباك البرنامج عشان توقفه.

## التحقق من الملف
SHA256 موجود في `ITAdministration.exe.sha256`.

## السورس كود
https://github.com/hunterx02/it-administration
