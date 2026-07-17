صور الخدمات — Service photos
================================

ضع صور العيادة الحقيقية هنا لتظهر تلقائياً على بطاقات الخدمات في الموقع،
بدلاً من الرسم التوضيحي. أي خدمة بدون صورة تبقى بالرسم التوضيحي (لا صورة مكسورة).

Drop real clinic photos here and they replace the illustration on the matching
service card automatically. A missing photo just keeps the illustration.

Use these exact file names (JPG). Recommended: landscape, at least 800×600px.

  hollywood.jpg    → هوليوود سمايل / أي خدمة فيها كلمة ابتسامة
  whitening.jpg    → تبييض الأسنان
  cleaning.jpg     → تنظيف
  filling.jpg      → حشوة
  rootcanal.jpg    → سحب عصب / علاج جذور
  checkup.jpg      → كشفية / فحص
  braces.jpg       → تقويم الأسنان
  implant.jpg      → زراعة الأسنان
  extraction.jpg   → خلع
  default.jpg      → أي خدمة أخرى

After adding files, rebuild + redeploy:
  cd frontend
  VITE_STATIC_SITE=1 npx vite build --base=/ayasrah-dental-clinic/ --outDir dist-static
  (then copy dist-static/* into the site repo clone and push)
