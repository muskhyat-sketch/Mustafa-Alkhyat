مغامرات الأبطال - مشروع Android

هذا مشروع Android Studio يغلّف اللعبة العربية داخل تطبيق Android يعمل دون إنترنت.
يتضمن اللعبتين وصور اللوحتين اللتين أرسلتهما.

لإنشاء APK:
1) ثبّت Android Studio على الكمبيوتر.
2) فك ضغط Moghamarat_AlAbtal_Android_Project.zip.
3) افتح مجلد heroes_android من Android Studio وانتظر مزامنة Gradle.
4) اختر Build > Build Bundle(s) / APK(s) > Build APK(s).
5) ستجد ملف APK داخل app/build/outputs/apk/debug/.

ملاحظة: لم يتم تضمين APK مبني داخل هذه الحزمة، لأن بيئة الإنشاء الحالية لا تحتوي Android SDK أو Gradle. يجب أن يقوم Android Studio بتنزيل أدوات البناء اللازمة.
