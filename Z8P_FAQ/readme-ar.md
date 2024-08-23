## <a id="choose-language">:globe_with_meridians: Choose language </a>
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
# استكشاف أخطاء Z8P وإصلاحها

-----
## مرجع
من أجل العثور على مشكلة المنتج وحلها، قد تحتاج إلى استخدام وظيفة الاختبار التلقائي، أو فتح صندوق التحكم للتحقق من الأسلاك أو ضبط تيار محرك الموت، واستخدام "اختبار المبادلة" للتحقق من المكونات الإلكترونية، وما إلى ذلك. .. ندرج هنا هذه الأدلة والصور والفيديو التعليمي للرجوع إليها.
### الأسلاك
- [:art: كيفية فتح صندوق التحكم](./pic/OpenControlBox.png)
- [:art: الأسلاك على لوحة التحكم](./pic/Z8P_wiring.png)

### اختبار قطع غيار السيارات الإلكترونية
قامت Z8P ببناء برنامج اختبار تلقائي للإلكترونيات. يمكنك استخدام هذا البرنامج لتحديد مصدر المشكلة عندما يواجه أي مكون إلكتروني مشكلة. لبدء هذا البرنامج، تحتاج إلى فتح قائمة "**المعلومات**" وتدوير المقبض للإشارة إلى العنصر "**التاريخ: xx-xx-xx**"، ثم الضغط على المقبض خمس مرات.
#### فيديو تعليمي
[![](https://img.youtube.com/vi/iSsuy2ePWw8/0.jpg)](https://www.youtube.com/watch?v=iSsuy2ePWw8)

### حول "اختبار المبادلة"
عندما نجد أن هناك مشكلة وظيفية في الجهاز، وسبب المشكلة له احتمالات متعددة (أجزاء متعددة قد تسبب نفس المشكلة)، لدينا الفرصة لاستخدام ما يسمى "**اختبار المبادلة**" " لتحديد سبب المشكلة في أسرع وقت ممكن.
على سبيل المثال، إذا كان محرك المحور Z الأيسر لا يعمل، فقد تأتي المشكلة من الأسلاك أو المحرك السائر أو كابل المحرك أو وحدة محرك المحرك الموجودة على لوحة التحكم أو لوحة التحكم. نظرًا لوجود مجموعتين من أنظمة محرك المحور Z في الماكينة - نظامي محرك Z الأيسر ونظام محرك Z الأيمن - وهما متطابقان، يمكننا تبادل نفس الأجزاء/المكونات/الأسلاك على الجانبين الأيسر والأيمن واحدًا تلو الآخر للتأكيد من أين تأتي المشكلة.
تشمل الأجزاء الموجودة في الجهاز والتي يمكنها إجراء اختبار التبادل ما يلي:
- محرك X/Y ومفتاح الحد.
- محرك ZL/ZR ومفتاح الحد
- 4 مجموعات من محركات الطارد
- سخان خرطوشة ومستشعر درجة حرارة السرير الساخن والنهاية الساخنة.

-----
## محتويات
- **[لا يمكن تشغيل الجهاز](./Issue_of_startup/readme.md)**
<!-- - **[النهاية الساخنة مسدودة/مسدودة](./Issue_extruder_blocked/readme.md)** -->
- **[مشكلة التسخين](./Issue_heating/readme.md)**
- **[إيقاف التشغيل تلقائيًا عند الطباعة من بطاقة SD](./Issue_auto_shut_down/readme.md)**
- **[كيفية إصلاح مشكلة كتلة الطارد](./Issue_extruder_blocked/readme.md)**
- **[كيفية إصلاح مشكلة التفريغ غير الكافي للطارد](./Issue_of_Extruder_inavailable_discharge/readme.md)**
- **[تعطل عند توصيل USB في Cura](./issue_of_connect_USB_in_Cura/readme.md)**
- **[إيقاف الطابعة مؤقتًا تلقائيًا عند الطباعة من بطاقة SD](./Issue_auto_pause/readme.md)**
- **[مشكلة عدم قراءة بطاقة SD](./Issue_not_read_sdcard/readme.md)**
- **[مشكلة في مقبض شاشة LCD](#dwinscreen)**

----
## مراجع أخرى
- **[44 مشكلة شائعة في الطباعة ثلاثية الأبعاد](https://github.com/ZONESTAR3D/Document-and-User-Guide/tree/master/FAQ)**
- **[جميع المشاكل والحلول (@All3DP.com)](https://all3dp.com/1/common-3d-printing-problems-troubleshooting-3d-printer-issues/)**

-----
## <a id="dwinscreen">مشكلة في مقبض شاشة LCD</a>
إذا وجدت أن مقبض شاشة LCD عالق، يمكنك النقر فوق [:gift: this link](https://www.aliexpress.com/item/3256805596235491.html) لشراء لوحة مفاتيح بديلة. إذا كان منتجك ضمن فترة الضمان (خلال 12 شهرًا من تاريخ استلام الطرد)، فيرجى الاتصال بنا بعد تقديم الطلب، وسنقدم لك خدمة ما بعد البيع.
كيفية استبدال لوحة المفاتيح لشاشة LCD، يرجى مشاهدة الفيديو التعليمي:
- للحصول على نسخة اللحام (الأقدم)، يرجى الرجوع إلى [:clapper: هذا الفيديو](https://youtu.be/Xwfczp3nLOY).
- للحصول على إصدار FPC (الأحدث)، يرجى الرجوع إلى [:clapper: هذا الفيديو](https://youtu.be/z9E6glRZRIQ).
####
![](./pic/keypad.jpg)

-----
## :email: إذا لم تتمكن من العثور على حل لمشكلتك بعد قراءة الأسئلة الشائعة، فيرجى الاتصال بفريق الدعم الفني لدينا: support@zonestar3d.com.