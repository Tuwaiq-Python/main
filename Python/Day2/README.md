
## الشروط Conditionals

مقدمة‭ ‬في‭ ‬مفهوم‭ ‬الشروط

حتى‭ ‬الآن‭ ‬قمنا‭ ‬بكتابة‭ ‬برامج‭ ‬صغيرة‭ ‬تقوم‭ ‬بتنفيذ‭ ‬“كامل”‭ ‬الجُمل‭ ‬الموجودة‭ ‬فيها،‭ ‬وهذا‭ ‬الأمر‭ ‬لا‭ ‬يحدث‭ ‬على‭ ‬الدوام،‭ ‬فهناك‭ ‬حالات‭ ‬نريد ‬فيها‭ ‬تنفيذ‭ ‬جُملة‭ ‬أو‭ ‬أكثر‭ ‬عند‭ ‬“تحقق‭ ‬شرط‭ ‬معين”‭ . ‬فمثلاً،‭ ‬فلنفترض ‬أن‭ ‬لديك‭ ‬برنامج‭ ‬مكون‭ ‬من‭ ‬7‭ ‬جُمل،‭ ‬في‭ ‬حال‭ ‬قمت‭ ‬بتشغيله،‭ ‬فسيتم‭ ‬تنفيذ‭ ‬جميع‭ ‬الجُمل،‭ ‬لكن‭ ‬ماذا‭ ‬لو‭  ‬كنا‭ ‬نريد‭ ‬تنفيذ‭ ‬الجُملتين‭ ‬الرابعة‭ ‬والخامسة‭ ‬في‭ ‬حال‭ ‬“تحقق‭ ‬شرط‭ ‬معين”‭ ‬عدا‭ ‬ذلك‭ ‬سيتم‭ ‬تجاوزهما‭  ‬وتنفيذ‭ ‬الجُمل‭ ‬التي‭ ‬تليها؟‭ ‬

استخدام ‭ ‬if statement

ببساطة،‭ ‬يمكنك‭ ‬استخدام‭ ‬if statement‭ ‬أو‭ ‬جُملة‭ ‬if‭. ‬ولفهم‭ ‬الطريقة‭ ‬التي‭ ‬تُستخدم‭ ‬بها‭ ‬جُملة‭ ‬if،‭ ‬دعنا‭ ‬نوضحها‭ ‬من‭ ‬خلال‭ ‬مثال‭ ‬بسيط‭ ‬على‭ ‬النحو‭ ‬الموضح‭ ‬في‭ ‬الشيفرة‭ ‬‮٩‬‭-‬‮١‬‭.‬


    value = 10
    if value == 20:
       print("yes")

استخدام‭ ‬جملة‭ ‬if‭ ‬للتحقق‭ ‬من‭ ‬قيمة‭ ‬value‭ ‬فيما‭ ‬إذا‭ ‬كانت‭ ‬تساوي‭ ‬20‭ ‬أم‭ ‬لا‭.‬

ببساطة،‭ ‬سيتم‭ ‬تنفيذ‭ ‬السطر‭ ‬‮١‬،‭ ‬وعندما‭ ‬يأتي‭ ‬إلى‭ ‬السطر‭ ‬‮٢‬،‭ ‬سيتحقق‭ ‬من‭ ‬“صحة‭ ‬الشرط”‭ ‬فيما‭ ‬إذا‭ ‬كان‭ ‬True‭ ‬أو‭ ‬False،‭ ‬حتى‭ ‬يقرر‭ ‬ما ‬إذا‭ ‬كان‭ ‬سينفذ‭ ‬الجُملة‭ ‬الموجودة‭ ‬في‭ ‬السطر‭ ‬‮٣‬‭ ‬أم‭ ‬لا‭. ‬يتحقق‭ ‬الشرط‭ ‬من‭ ‬قيمة‭ ‬value‭ ‬إن‭ ‬كانت‭ ‬20‭ ‬أم‭ ‬لا‭و . ‬بما‭ ‬أن‭ ‬قيمة‭ ‬value‭ ‬هي‭ ‬10‭ ‬وليست‭ ‬ 20،‭ ‬ فإن الشرط ‬لن‭ ‬يتحقق‭ ‬،‭ ‬أي‭ ‬أن‭ ‬نتيجة‭ ‬الشرط‭ ‬هي‭ ‬false،‭  ‬وعليه‭ ‬سيتم‭ ‬تجاوز‭ ‬الجُملة‭ ‬الموجودة‭ ‬في‭ ‬السطر‭ ‬‮٣‬،‭ ‬و ‬لن‭ ‬تتم ‬طباعة‭ ‬yes‭.‬

لاحظ ان جملة if تحتوي على block حيث تبدأ بعلامة { وتنتهي بعلامة } وذلك لجعلها ضمن block  الخاص بجملة if. وعليه فإن أي جمل نضعها بداخل if block سيتم تجاوزها في حال عدم تحقق الشرط

ملاحظة تختلف طرق وأشكال if block من لغة لأخرى ولكن المفهوم واحد 

الآن‭ ‬لو‭ ‬قمنا‭ ‬بإعادة‭ ‬الشرط‭ ‬السابق‭ ‬لكي‭ ‬يتوافق‭ ‬مع‭ ‬القيمة‭ ‬10،‭ ‬أو‭ ‬قمنا‭ ‬بتغيير‭ ‬قيمة‭ ‬value‭ ‬إلى‭ ‬20،‭ ‬فعندها‭ ‬سيتحقق‭ ‬الشرط،‭ ‬وعليه‭ ‬ستكون‭ ‬الشيفرة‭ ‬كما‭ ‬توضح‭ ‬الشيفرة‭ ‬‮٩‬‭-‬‮٢‬‭.‬


    value = 10
    if value == 10:
       print("yes")

استخدام‭ ‬جملة‭ ‬if‭ ‬للتحقق‭ ‬من‭ ‬قيمة‭ ‬value‭ ‬فيما‭ ‬إذا‭ ‬كانت‭ ‬تساوي‭ ‬10‭ ‬أم‭ ‬لا‭.‬

في‭ ‬هذه‭ ‬الحالة،‭ ‬سيتم‭ ‬التحقق‭ ‬من‭ ‬الشرط‭ ‬الموجود‭ ‬في‭ ‬جملة‭ ‬if،‭ ‬وبما‭ ‬أنه‭ ‬صحيح،‭ ‬أي‭ ‬أنه‭ ‬سيُعطي‭ ‬True،‭ ‬عندها‭ ‬سيتم‭ ‬تنفيذ‭ ‬جميع‭ ‬الجُمل‭ ‬الموجودة‭ ‬في‭ ‬if block،‭ ‬وبما‭ ‬أنه‭ ‬ليس‭ ‬لدينا‭ ‬سوى‭ ‬جُملة‭ ‬واحدة،‭ ‬فإنه‭ ‬سيتم‭ ‬تنفيذه،‭ ‬وستتم ‬طباعة‭ ‬كلمة‭ ‬yes‭.‬


استخدام ‭else

هناك‭ ‬أوقات‭ ‬نود‭ ‬التصرف‭ ‬مع‭ ‬الحالات‭ ‬غير المتوقعة أي أن نوجد خيار بديل في حال عدم تحقق شروطنا‭و . ‬للقيــام‭ ‬بذلــك‭ ‬يمكننــا‭ ‬اســتخدام‭ ‬ else‭ ‬ ‭.  ‬ يوضح‭ ‬المثال‭ ‬التالي‭ ‬كيفية‭ ‬استخدام‭ ‬else‭ :‬


    value = 10
    if value == 10:
       print("yes")
    else:
       print("No")


استخدام ‭else if

احيانــا‭ ‬نحتــاج‭ ‬لاختبــار‭ ‬اكثــر‭ ‬مــن‭ ‬حالــة‭ ‬واحــدة‭. ‬للقيــام‭ ‬بذلــك‭ ‬يمكننــا‭ ‬اســتخدام‬else if‭  ‬ و‭ ‬التـي‭ ‬تقـوم‭ ‬باختبـار‭ ‬شـرط‭ ‬اخـر‭ ‬فـي‭ ‬حـال‭ ‬ان‭ ‬الشـرط‭ ‬الأول‭ ‬لـم‭ ‬يتحقـق‭. ‬يوضح‭ ‬المثال‭ ‬التالي‭ ‬كيفية‭ ‬استخدام‭ ‬else if‭ ‬:


    teamBlueScore = 7
    teamRedScore = 7
    if teamBlueScore > teamRedScore:
            print("Team Blue Won")
    elif teamBlueScore == teamRedScore:
            print("The two teams got the same score")
    else:
            print("Team Blue Lost")

النتيجة‭ ‬ستكون‭ ‬تفعيل‭ ‬الأوامر‭ ‬التابعة‭ ‬للشرط‭ ‬الثاني‭ ‬وذلك‭ ‬لانه‭ ‬بالفعل‭ ‬الفريق‭ ‬الأزرق‭ ‬متعادلة‭ ‬مع‭ ‬الفريق‭ ‬الأحمر


    The two teams got the same score


استخدام‭ ‬if statement‭ ‬بداخل ‭ ‬if statement

بإمكانك‭ ‬وضع‭ ‬if‭ ‬بداخل‭ ‬if،‭ ‬أي‭ ‬كتابة‭ ‬جُمل‭ ‬متداخلة‭ ‬nested،‭ ‬و‭ ‬if‭ ‬داخل‭ ‬if‭ ‬داخل‭ ‬if،‭ ‬وهكذا،‭ ‬أي‭ ‬مجموعة‭ ‬من‭ ‬التداخلات‭ ‬وفقاً‭ ‬لنوع‭ ‬المشكلة‭ ‬البرمجية‭ ‬التي‭ ‬تحاول‭ ‬حلها،‭ ‬وعلى‭ ‬أي‭ ‬حال،‭ ‬دعنا‭ ‬نوضح‭ ‬هذا‭ ‬الأمر‭ ‬بمثال‭ ‬بسيط‭ ‬على‭ ‬النحو‭ ‬الموضح‭ ‬في‭ ‬الشيفرة‭ ‬‮٩‬‭-‬‮٧‬‭.‬


    name = "Mohammad"
    number = 22
    if name == "Mohammad":
      if number == 23:
       print("Your name is Mohammad, and your number is 23")

استخدام‭ ‬if‭ ‬بداخل‭ ‬if‭ ‬لاختبار‭ ‬أكثر‭ ‬من‭ ‬شرط‭.‬

في‭ ‬السطر‭ ‬٣‭ ‬استخدمنا‭ ‬قمنا بالتحقق من الشرط الأول وهو أن تكون قيمة المتغيرname‭ ‬   هي   Mohammad ‬  وفي‭ ‬حال‭ ‬تحقق‭ ‬الشرط،‭ ‬سيتم‭ ‬الدخول‭ ‬إلى‭ ‬block‭ ‬الخاص‭ ‬بها ثم سيتم‭ ‬الدخول‭ ‬لتنفيذ‭ ‬if‭ ‬الداخلية‭‬ والتي تقوم بالتحقق من تحقق الشرط الثاني وهو ان تكون قيمة المتغير number  هي 23 و في ‭ ‬حال‭ ‬تحقق‭ ‬الشرط،‭ ‬سيتم‭ ‬طباعة‭ ‬النص‭ ‬الموجود‭ ‬في‭ ‬السطر‭ ‬‮الخامس‬،‭ ‬والذي‭ ‬يمثل‭ ‬رسالة‭ ‬باسم الشخص المسمى  Mohammad ورقمه.
لاحظ‭ ‬أنه‭ ‬في‭ ‬حال‭ ‬لم‭ ‬يتحقق‭ ‬الشرط‭ ‬الموجود‭ ‬في‭ ‬السطر‭ ‬٣‬،‭ ‬فسينتهي‭ ‬البرنامج‭ ‬مباشرة‭.‬
