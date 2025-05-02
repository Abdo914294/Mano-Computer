# Mano-Computer

هذا المشروع هو محاكاة لحاسوب مانو ، ويهدف إلى تنفيذ معالج بسيط بحجم 8-بت لفهم بنية الحاسوب من المستوى المنخفض.

## مكونات المشروع

- وحدة المعالجة المركزية (CPU)
- وحدة التحكم (Hardwired Control Unit)
- وحدة الحساب والمنطق (ALU)
- الذاكرة (RAM) بسعة 256 × 8 بت
- مجموعة المسجلات: AC, DR, AR, IR, PC, TR, INPR, OUTR
- common bus , adder and logic circuit
- 4bits sequence counter


## الملفات


## التعليمات المدعومة

- LDA (Load Accumulator)
- STA (Store Accumulator)
- ADD, SUB, AND
- BUN (Branch Unconditionally)
- ISZ (Increment and Skip if Zero)
- BSA (Branch and Save Return Address)


## التشغيل

1. استخدام برنامج vivado and proteus
2. حمّل برنامج الآلة داخل `memory.v`.
3. شغّل المحاكاة باستخدام `top.v`.
4. تتبع التنفيذ عبر الـ waveform أو الرسائل النصية.


## فيديو الشرح

- شرح تصميم المشروع وأخذ فكرة عامة عنه
- عمل تنفيذ لبعض الأوامر مثل : LDA,ISZ
- شرح نتيجة المحاكاة علي برنامج vivado

## رابط الفيديو

[https://www.dropbox.com/scl/fo/iyp9wsquztfoyafb6nsvf/AMkODBKorex3kQ40yFqMySM?rlkey=v23o2j90mb6md517v73djlbm9&st=rkoyddji&dl=0](https://www.dropbox.com/scl/fo/iyp9wsquztfoyafb6nsvf/AMkODBKorex3kQ40yFqMySM?rlkey=gne4orjgis713jb4uwy449a1i&st=it53gr22&dl=0)

## العرض التقديمي 

https://www.dropbox.com/scl/fo/x7epyx2ob3ms7urn2ugzg/ABgMpNGgzrz6WmV83RvN0us?rlkey=d9g3zinuppwvcu3p36vvcq10j&st=db6m6u9l&dl=0

