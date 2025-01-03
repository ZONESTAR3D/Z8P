## <a id="choose-language">:globe_with_meridians: اختر اللغة</a>
[![](./lanpic/EN.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme.md)
[![](./lanpic/ES.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-es.md)
[![](./lanpic/PT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-pt.md)
[![](./lanpic/FR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-fr.md)
[![](./lanpic/DE.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-de.md)
[![](./lanpic/IT.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-it.md)
[![](./lanpic/RU.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ru.md)
[![](./lanpic/JP.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-jp.md)
[![](./lanpic/KR.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-kr.md)
[![](./lanpic/SA.png)](https://github.com/ZONESTAR3D/Z8P/blob/main/Z8P_FAQ/readme-ar.md)

----
# حل المشكلات لـ Z8P

-----
## مراجعة
لإيجاد وحل مشاكل المنتج، قد تحتاج إلى استخدام وظيفة الفحص التلقائي، فتح صندوق التحكم لفحص التوصيل أو تJUSTم التيار الدفعة للمحرك، استخدام "اختبار الاستبدال" لفحص مكون إلكتروني، إلخ. هنا نسرد هذه الإرشادات و الصور ودروس الفيديو ل.Reference.
### التوصيل
- [:art: كيفية فتح صندوق التحكم](./pic/OpenControlBox.png)
- [:art: التوصيل على لوحة التحكم](./pic/Z8P_wiring.png)

### اختبار تلقائي للعناصر الإلكترونية
يحتوي Z8P على برنامج اختبار تلقائي للعناصر الإلكترونية. يمكنك استخدام هذا البرنامج لتحديد مصدر المشكلة عندما يواجه أي مكون إلكتروني مشكلة. لبدء هذا البرنامج، تحتاج إلى فتح القائمة "**Info**" وتدوير المكnob إلى البند "**Date: xx-xx-xx**"، ثم اضغط على المكnob cinco veces.
#### دروس الفيديو
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### حول "اختبار الاستبدال"
عندما نجد أن هناك مشكلة وظيفية في الآلة، والسبب في المشكلة لديه عدة إمكانيات (العديد من الأجزاء قد تسبب في同一个问题)، لدينا فرصة لاستخدام ما يسمى "اختبار الاستبدال" لتحديد سبب المشكلة في أقرب وقت ممكن.
على سبيل المثال، إذا لم يعمل محرك المحور Z الأيسر، فقد يأتي السبب من التوصيل، أو المحرك الخطوة، أو cáble del motor، أو وحدة التحكم في المحرك على لوحة التحكم أو لوحة التحكم نفسها. ولأن هناك نظام تحكم محور Z منظوم - نظام التحكم في المحور Z الأيسر واليمين - والتي هي نفسها، يمكننا تبادل الأجزاء/العناصر/التوصيلات نفسها على الجانبين الأيسر واليمين واحدًا بعد الآخر لتأكيد أين يأتي ال源自.
الأجزاء في الآلة التي يمكن إجراء اختبار الاستبدال عليها تشمل:
- محرك X/Y和平A	switch.
- محرك ZL/ZR والinterruptor de límite
- 4 مجموعات من محركات الاستخراج
- المسخن الكرتوني和平sensor de temperatura de la cama caliente y del extrusor.

-----
## المحتويات
- **[الآلة لا يمكن أن تبدأ](./Issue_of_startup/readme.md)**
- **[مشكلة التوجيه](./Issue_of_Homing/readme.md)**
- **[مشكلة الحرارة](./Issue_heating/readme.md)**
- **[إيقاف تلقائي عند الطباعة من بطاقة SD](./Issue_auto_shut_down/readme.md)**
- **[كيفية إصلاح مشكلة حzam في الطرف/the Extruder](./Issue_extruder_blocked/readme.md)**
- **[كيفية إصلاح مشكلة انخفاض الإخراج من الاستخراج](./Issue_of_Extruder_insufficient_discharge/readme.md)**
- **[انهيار عند الاتصال بـ USB في Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[الطابعة تتوقف تلقائيًا عند الطباعة من بطاقة SD](./Issue_auto_pause/readme.md)**
- **[مشكلة عدم قراءة بطاقة SD](./Issue_not_read_sdcard/readme.md)**
- **[مشكلة مفتاح الشاشة LCD](#dwinscreen)**

----
## المراجع الأخرى
- **[44 مشكلة 3D الطباعة الشائعة](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[جميع المشاكل和平solutions (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">مشكلة مفتاح الشاشة LCD</a>
إذا وجدت أن مفتاح الشاشة LCD ق固، يمكنك النقر على [:gift: هذا الرابط](https://www.aliexpress.com/item/3256805596235491.html) لشراء لوحة مفاتيح بديلة. إذا كان المنتج الخاص بك ضمن فترة الضمان (خلال 12 شهرًا من تاريخ استلام الpackage)، يرجى الاتصال بنا بعد إجراء الorder، وسنوفر لك خدمة الدعم بعد البيع.
كيفية استبدال لوحة مفاتيح الشاشة LCD، يرجى مشاهدة دروس الفيديو:
- للنسخة القديمة (الolder version)، يرجى الرجوع إلى [:clapper: هذا الفيديو](https://youtu.be/Xwfczp3nLOY).   
- للنسخة الجديدة (FPC version)، يرجى الرجوع إلى [:clapper: هذا الفيديو](https://youtu.be/z9E6glRZRIQ).  
####
![](./pic/keypad.jpg)

-----
## :email: إذا لم تجد حلًا لمشكلةك بعد قراءة التعليمات المتداولة، يرجى الاتصال بفريق الدعم الفني: support@zonestar3d.com .
