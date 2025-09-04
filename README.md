# 🐐 Goat Bot - بوت محادثة ماسنجر

## 📝 ملاحظة
- هذا بوت ماسنجر يستخدم حساب شخصي عبر **API غير رسمي**، وقد يؤدي ذلك إلى قفل الحساب بسبب الرسائل العشوائية أو أسباب أخرى.  
- يُنصح باستخدام حساب بديل (يمكنك التخلي عنه في أي وقت).  
- **المطور غير مسؤول عن أي مشاكل تحدث عند استخدام هذا البوت.**

---

## 🚧 المتطلبات
- Node.js إصدار **16.x**  
- معرفة بأساسيات **البرمجة** و **JavaScript** و **Node.js** و **الـ Facebook Unofficial API**

---

## 📝 الشرح
شرح كامل موجود على يوتيوب:  
- للهاتف: [اضغط هنا](https://www.youtube.com/watch?v=grVeZ76HlgA)  
- لـ VPS/ويندوز: [اضغط هنا](https://www.youtube.com/watch?v=uCbSYNQNEwY)  

📌 خطوات التثبيت: [STEP_INSTALL.md](https://github.com/ntkhang03/Goat-Bot-V2/blob/main/STEP_INSTALL.md)

---

## 💡 كيف يعمل؟
- يعتمد البوت على API غير رسمي لإرسال واستقبال الرسائل.  
- عند وجود حدث جديد (رسالة، تفاعل، دخول/خروج عضو، …) يتم تمريره إلى `handlerEvents`، الذي يقوم بتنفيذ الأوامر التالية:  
  - **onStart** → عند استدعاء أمر.  
  - **onChat** → عند إرسال رسالة.  
  - **onFirstChat** → عند أول رسالة منذ تشغيل البوت.  
  - **onReaction** → عند التفاعل مع رسالة مرتبطة.  
  - **onReply** → عند الرد على رسالة مرتبطة.  
  - **onEvent** → عند أحداث المجموعة (إضافة/خروج عضو، تغيير مشرف …).  
  - **handlerEvent** → ينفذ أوامر الأحداث من مجلد `scripts/events`.

---

## 🔔 التحديثات
- لتلقي إشعارات التحديثات الجديدة، اضغط على زر **Watch** في GitHub واختر **Releases** و **Pull requests**.

---

## 🆙 كيفية التحديث
- الهاتف/Repl: [شاهد من هنا](https://youtu.be/grVeZ76HlgA?t=1342)  
- VPS/الكمبيوتر: [شاهد من هنا](https://youtu.be/uCbSYNQNEwY?t=508)  

---

## 🛠️ إنشاء أوامر جديدة
📌 [اضغط هنا لقراءة الوثائق](https://github.com/ntkhang03/Goat-Bot-V2/blob/main/DOCS.md)

---

## 💭 الدعم
إذا لديك مشاكل برمجية كبيرة:  
- [Discord](https://discord.com/invite/DbyGwmkpVY) (موصى به)  
- [Facebook Group](https://www.facebook.com/groups/goatbot)  
- [Messenger](https://m.me/j/Abbq0B-nmkGJUl2C)  

⚠️ الرجاء عدم مراسلتي خاصًا، لن أجيب. فقط عبر المجموعات.

---

## 📚 اللغات المدعومة
- [x] en: الإنجليزية  
- [x] vi: الفيتنامية  

> يمكن تغيير اللغة من ملف `config.json` أو تعديل ملفات `languages/`

---

## 📌 المشاكل الشائعة
- **redirect_uri_mismatch** → تحقق من إعدادات OAuth.  
- **invalid_client / unauthorized_client** → تأكد من Client ID.  
- **access_denied** → المشروع غير منشور في Google Console.  

(التفاصيل الكاملة موجودة في المستند الأصلي).

---

## ❌ لا تستخدم النسخ المقلدة
- النسخة الرسمية الوحيدة: [Goat-Bot-V2](https://github.com/ntkhang03/Goat-Bot-V2)  
- أي نسخ أخرى (fork/replit/…) غير آمنة وقد تحتوي على برمجيات خبيثة.  

---

## 📸 لقطات شاشة
- يدعم: نظام الرتب، الطقس، إشعارات الترحيب، GPT، لوحة تحكم، تخصيص الإعدادات …  
(انظر الصور في المصدر).  

---

## ✨ حقوق النشر (C)
- **NTKhang (NTKhang03)**  

---

## 📜 الرخصة
**بالعربية**  
- إذا انتهكت أي قاعدة، سيتم حظرك من استخدام المشروع.  
- لا تبيع الكود المصدري.  
- لا تدّعي ملكية الكود.  
- لا تربح من الكود (بيع أوامر، تأجير بوت، تبرعات …).  
- لا تحذف أو تعدّل بيانات المؤلف.  

**بالإنجليزية**  
- If you violate any rules, you will be banned.  
- Don’t sell my source code.  
- Don’t claim my source code as your own.  
- Don’t monetize my source code.  
- Don’t remove/edit author credits.