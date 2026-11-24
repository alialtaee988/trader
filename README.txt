طريقة الحصول على ملف APK (بدون كمبيوتر قوي، ومجاناً):
1) سجّل في github.com وأنشئ مستودعاً جديداً (New repository).
2) ارفع كل محتويات هذا المجلد كما هي (بما فيها مجلد .github).
3) افتح تبويب Actions ثم Build APK ثم Run workflow.
4) بعد 4-6 دقائق ينزل ملف trader-journal-apk من قسم Artifacts، وبداخله app-debug.apk.
5) ثبّته على الهاتف (فعّل "التثبيت من مصادر غير معروفة").

على كمبيوتر مع Node و Android Studio:
npm install && npx cap add android && npx cap sync android && npx cap open android
