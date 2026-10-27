# موقع حادي عشر علمي هـ ، و

## الملفات (ارفعها كلها في نفس المكان على GitHub)
- index.html  هو الموقع
- data.json  فيه الواجبات والإعلانات
- teams-guide.pdf و eschool-guide.pdf

## تشغيل الموقع
Settings ثم Pages ثم Deploy from a branch ثم main و / (root) ثم Save.

## إضافة واجب
افتح data.json على GitHub، واضغط أيقونة القلم، وضع هذا السطر داخل القوسين المربعين بعد "homework":[ ، مع فاصلة بين الواجبات، ثم Commit changes.

    {
      "id": "phys-1",
      "subject": "phys",
      "title": "عنوان الواجب",
      "details": "تفاصيل الواجب",
      "due": "2026-11-02"
    }

المواد: phys فيزياء، math رياضيات، chem كيمياء، bio أحياء، arab عربي، relig دين، tech تكنو، eng إنجليزي.
اختياري: "closed": true لإنهاء موعد التسليم، و "link": {"url": "https://...", "label": "نص الزر"} لزر تسليم.
كل واجب له id مختلف.

## إضافة إعلان
نفس الطريقة داخل "announcements":
    { "id": "n2", "pin": false, "date": "2026-11-01", "title": "العنوان", "body": "النص" }
