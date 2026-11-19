# IT Administration — برنامج Windows

نظام لإدارة قسم تقنية المعلومات: الأصول والعهد، رحلة الموظف (التوظيف والتعيين والإخلاء)، الخدمات التقنية والتجديدات، مصروفات IT، والربط مع Google Sheets أو Excel.

## التحميل
نزّل الملف **[ITAdministration.exe](ITAdministration.exe)** (اضغط عليه ثم زرار التحميل ⬇).

## التشغيل
1. شغّل `ITAdministration.exe`.
2. لو ويندوز ظهّر «Windows protected your PC»، اضغط **More info** ثم **Run anyway** (البرنامج مش موقّع رقميًا).
3. البرنامج بيفتح في **شباك لوحده** زي أي برنامج. أول مرة هتعمل حساب المدير.
4. أول تشغيل بيعمل اختصار **IT Administration** على سطح المكتب وفي قائمة Start — بعد كده افتحه منهم.
5. أضف شركتك من «إدارة النظام»، واربط شيتات Google الخاصة بيك من «الربط والأتمتة» (أو استخدم ملف Excel محلي).

## ملاحظات
- بيشتغل **من غير إنترنت** — الإنترنت مطلوب بس وقت مزامنة شيتات Google.
- مش محتاج تثبيت Python أو أي برنامج تاني (بيستخدم Microsoft Edge الموجود في ويندوز لعرض الشباك).
- قفل الشباك = قفل البرنامج. الإشعارات والمزامنة والنسخ الاحتياطي بتشتغل طول ما البرنامج مفتوح.
- بياناتك بتتحفظ على جهازك في `%LOCALAPPDATA%\ITAdministration`.
- لفتحه من أجهزة تانية على نفس الشبكة: `ITAdministration.exe --lan`
- لتغيير المنفذ: `ITAdministration.exe --port 8010`
- لو حصلت مشكلة: التفاصيل في `%LOCALAPPDATA%\ITAdministration\app.log`

## التحقق من الملف
SHA256 موجود في `ITAdministration.exe.sha256`.

## السورس كود
https://github.com/hunterx02/it-administration
