## Intro To Python مقدمة في لغة البايثون
عن لغة البايثون (Python)
لغة البايثون (Python) تعتبر لغة عالية المستوى High-level ، عامة الغرض general-purpose . اكتسبت شعبية كبيرة بين المطورين لعدة أسباب ، أهمها : 

- سهولة التعلم.
- تعمل تقريباً في كل مكان مع جميع أنظمة التشغيل.
- دعم كبير من مجتمع المطورين.
- مفتوحة المصدر.
- استعمالاتها في الذكاء الاصطناعي وعلم البيانات.
- استعمالاتها في تطوير الأنظمة الخلفية لمشاريع الشبكة العنكبوتية مع ظهور أُطر عمل قوية مثل Django , Flask , FastAPI و غيرها. 

هي إحدى اللغات الديناميكية  (Dynamically Typed)، التي لا تتطلب تحديد النوع و إنما توفره كجزء اختياري . على الأقل حتى الوقت الراهن . تعتمد على جامع النفايات (Garbage Collector) في إدارة الذاكرة العشوائية و لا تتطلب من المبرمج أي تدخل يدوي لإدارتها بأغلب الحالات. 
مع دعم لعدة أنماط من البرمجة ، التي تتضمن البرمجة الإجرائية (Procedural Programming) ، البرمجة الوظيفية (Functional Programming) و البرمجة المعتمدة على الأجسام (Object Oriented Programming). و مع وجود مكتبة أساسية ضخمة ، فهي تتيح للمبرمج أغلب الأدوات التي يحتاجها المشروع الذي يعمل عليه ، لتنفيذه بسرعة و بكفاءة عالية . 
تم اطلاق النسخة 0.9.0 من اللغة  في عام 1991 من قبل المهندس Guido Van Rossum كخليفة أو لغة مطورة من لغة الـ ABC . و في  عام 2000 تم اطلق النسخة الثانية ، وأخيرا في عام 2008 تم إطلاق النسخة الثالثة و التي تعتبر أكبر تحديث للغة منذ نشأتها الأولى . 



لغة البايثون تم تصميمها بفلسفة معينة ، أبرز نقاطها :

- الجميل أفضل من القبيح.
- الصريح أفضل من الضمني.
- البسيط أفضل من المعقد.
- قابلية القراءة مُهمة.

لذا فاللغة تعتمد على فكرة الإضافة عبر الوحدات الخارجية . ففي جوهرها ، هي لغة صغيرة، بسيطة قابلة للإمتداد والإضافة عبر الوحدات الخارجية حسب احتياج البرنامج أو المشروع . كما أنها لغة سهلة القراءة ، تكتبها و كأنك تعبر عن برنامجك باللغة الإنجليزية باستخدام كلماتها المعتادة مع تقليل الاعتماد على الرموز قدر الإمكان واستبدالها بكلمات . 
من هنا نجد أنها تُشجع و تحفز المطور على أن يكتب كود مُرتب و سهل القراءة . فبدلاً من استخدام الأقواس المعكوفة لبدء كتلة من الكود ، فهي تستخدم المسافات ، فمثلا ثلاث مسافات تعني بدأ كتلة من الكود ، و الرجوع لبداية السطر تعني انتهاء تلك الكتلة .
لغة البايثون لغة مُترجمة (Interpreted) على عكس اللغات المجموعة (Compiled) .  فعند تشغيل البرنامج ، يقوم المترجم بمعالجة الكود و تنفيذه. تتم هذه العملية من خلال قراءة الكود و تحويله الى bytecode و من ثم تنفيذه بواسطة آلة البايثون الإفتراضية Virtual Machine ، مما يجعل من تطوير برامج البايثون أسرع و أسهل في اكتشاف أخطاء البرنامج أثناء تشغيله ، ولكن أيضا يجعل منها أبطأ من اللغات المجموعة (compiled) مثل ++C, C و غيرها. 




إعداد بيئة العمل

أولاً: تثبيت الـ Python على جهازك

بالأعم الأغلب ، جهازك يأتي مع نسخة مثبتة من البايثون . للتأكد من وجود نسخة من البايثون على جهازك ، استخدم الأمر التالي على الـ Terminal , PowerShell, Bash :
python –version
Or
python3 –version

من المفترض أن تحصل على المخرج التالي (أو مماثل له) :
Python 3.8.9

في حال كانت لديك نسخة قديمة ، أو لا يوجد لديك أي نسخة يمكنك تثبيت آخر إصدار من البايثون على جهازك من خلال زيارة الرابط التالي و اتباع التعليمات كُل حسب نظام التشغيل الذي يستخدمه .

https://www.python.org/downloads/

ثانياً : تثبيت الـ IDE (بيئة العمل المدمجة)

لتطوير برامج البايثون على أجهزتنا ، سنستخدم الـ Visual Studio Code لكتابة الكود و ادارة مشاريعنا . و تم اختياره لشعبيته الكبيرة والدعم الكبير على مختلف الأجهزة .


من أجل تثبيت برنامج Visual Studio Code قم بالتوجه الى صفحة التحميل :

https://code.visualstudio.com/download


بعد إكمال تثبيت المحرر ، قم بتثبيت إضافة (Extension)  البايثون IntelliSense المقدمة من Microsoft و ذلك من خلال قائمة الإضافات في المحرر على يسار الشاشة ، ابحث عن Python و ثبت الإضافة المقدم من Microsoft .  هذه الإضافة ستوفر لنا الأدوات اللازمة للتعامل مع لغة البايثون في هذا المحرر كـ تلوين الجمل ، تصحيح الأخطاء ، مستكشف الكود، و غيرها.





مقدمة في لغة البايثون (Python)

مترجم البايثون التفاعلي (Python Interactive Interpreter)

يمكنك كتابة اكواد البايثون و العمل مباشرة على الـ terminal/PowerShell/Bash من خلال استخدام مترجم البايثون التفاعلي وذلك من خلال طباعة الأمر python او python3 و الذي سيشغله لك . بعدها تستطيع كتابة أكواد البايثون كما و لو أنك تكتبها في ملف . 

![Screen Shot 2022-04-06 at 2.45.46 PM.png](https://lh4.googleusercontent.com/T7WN5q0oCNdZ3iGuq2EKD1_Xo1vTz6Mf312PVqt37mKvVtofkWiUS9PnCi3MOBdxdu5q8YWcANz2xSCEM1STdRWbw4fOcNfeokSV6aUxF0Ppl_naHwcIMSSngNpytNorViHOWNEadj2rzsxpyN0)


للخروج من المترجم التفاعلي ، اضغط CTRL-D

ملفات البايثون

لكتابة كود البايثون  وتنفيذ البرنامج، نحتاج أن نضعه داخل ملف ينتهي بامتداد py. ، بعدها نستطيع تنفيذ الكود من داخل المحرر بالضغط على زر التشغيل في أعلى يمين المحرر .  كما هو موضح لك هنا:

![Screen Shot 2022-04-06 at 2.47.43 PM.png](https://lh5.googleusercontent.com/gvzHoP3qEoOoUlI2QKeYv-sKbTF1wY7tbUWPBQuASqtqSYyd8sBZCC8-Ghb3uJEfJMlxe20NLNPdKLx9kVnFsFBew09zoVz4h-D48w8JhbRwo5F5YT-DFubacxiwAVPooD4zmglQominz4wSxoM)


أو من خلال الدخول على الـ Termina/PowerShell/Bash و طباعة الأمر  python3 متبوعا بإسم الملف ، كما التالي (يجب أن تكون في نفس المجلد أو أن تكتب المسار الكامل للملف)  :
 python3  my_app.py

البيانات و أنواعها

أي برنامج على حاسوبك عبارة عن مجموعة من البيانات المخزنة في الذاكرة ، بيانات من عدة أنواع و أحجام مختلفة كالأرقام ، النصوص ، المصفوفات ، و غيرها التي تحتل مكانا في الذاكرة . فكر في الذاكرة و كأنها دولاب كبير ، في داخل هذا الدولاب بإمكاننا تخزين صناديق تحتوي على بيانات مختلفة . هذه الصناديق يمكن أن تكون لها أنواع و أحجام مختلفة . و لكل صندوق معرف يسمح للبرنامج بالوصول الى مكانه في الذاكرة بسرعة و قراءة البيانات التي بداخله .
فجميع البيانات في البايثون عبارة عن أجسام (objects)  مخزنة في الذاكرة ، و كل جسم على الأقل يحتوي على التالي:

- نوع يعرف لنا ما يمكن له أن يفعله (مثل رقم ، نص، مصفوفة ، الخ)
- مُعرف فريد يميزه عن باقي الأجسام .
- قيمة متوافقة مع نوعه .
- عدد مرجعي لمعرفة كم مرة تم استخدام الجسم هذا.


جدول بأنواع البيانات الأساسية في البايثون 
| الإسم            | النوع   | قابل للتعديل ؟ | مثال                                          |
| ---------------- | ------- | -------------- | --------------------------------------------- |
| قيمة منطقية      | bool    | لا             | True, False                                   |
| رقم              | int     | لا             | 50, 24, 105                                   |
| رقم عائم (فاصلة) | float   | لا             | 3.14, 0.45                                    |
| معقد             | complex | لا             | 3j , 5 + 9j                                   |
| نص               | str     | لا             | 'Ahmed', “Mohammed”                           |
| قائمة            | list    | نعم            | [1,2,3,4,5]                                   |
| جدول             | tuple   | لا             | (1,2,3,4)                                     |
| مجموعة           | set     | نعم            | set([“kiwi”, “apple”])                        |
| قاموس            | dict    | نعم            | {“Riyadh” : 34, “Medina” : 56, “Dammam” : 32} |





المتغيرات Variables
هناك طريقتين لكتابة قيم البيانات في لغة البايثون :
- بكتابتها حرفياً .
- بكتابتها و تعيينها لـ متغير .

المتغيرات عبارة عن أسماء تدل على قيم معينة في مسير برنامجك. لكتابة المتغير نحتاج  إسم للمتغير ، و قيمة لتعيينها لذلك الإسم . 

مثال للمتغير:


    my_var = 27

ففي المثال السابق ، اسم المتغير هو my_var والقيمة هي 27 . لاحظ استخدامنا لرمز التعيين = ، و ذلك لتعيين القيمة للمتغير .
كما يمكننا أيضاً اختيارياً أن نحدد نوع المتغير وذلك من خلال استخدام نقطتين فوق بعض بعد اسم المتغير و من ثم نحدد النوع ، كالتالي :


    my_var:int = 27
قواعد كتابة المتغير في البايثون
- يجب أن يبدأ المتغير بحرف أو شرطة تحتية .
- يمكن أن يحتوي على حروف كبيرة.
- يمكن أن يحتوي على حروف صغيرة .
- يمكن أن يحتوي على أرقام من 0 حتى الـ 9 .
- الأحرف الصغيرة و الكبيرة معتبرة فـ T غير t .
- لا يمكن أن يكون المتغير أحد الكلمات المفتاحية (قائمة لها بالأسفل)



قابلية التعديل (Mutability) 

نوع البيانات المخزنة تنقسم إلى قسمين :

- بيانات قابلة للتعديل (Mutable)
- بيانات غير قابلة للتعديل (Immutable)

كما يوحي الإسم ، البيانات ذات النوع القابل للتعديل ، بالإمكان تغيير قيمته إلى قيمة أخرى . بينما العكس غير صحيح ، فلا يمكن التعديل على قيمة البيانات ذات النوع الغير قابل للتعديل . 







الكلمات المفتاحية Keywords

هي كلمات خاصة باللغة يتم استخدامه لغرض معين . هذه الكلمات لا يمكن استخدامها كأسماء للمتغيرات .  
قائمة الكلمات المفتاحية في البايثون :
False      await      else       import     pass
None       break      except     in         raise
True       class      finally    is         return
and        continue   for        lambda     try
as         def        from       nonlocal   while
assert     del        global     not        with
async      elif       if         or         yield
 

تعيين قيمة لأكثر من متغير

كما تعلمنا آنفاً ، لتعيين قيمة لمتغير نستخدم علامة التعيين = . و من أجل تعيين قيمة واحدة لأكثر من متغير في البايثون استخدم التركيب التالي :



    var1 = var2 = var3 = 25

فالآن جميع المتغيرات var1, var2, var3 جميعها أصبحت قيمتها 25 .
و لتعيين أكثر من قيمة لأكثر من متغير على نفس السطر ، نستخدم التركيب التالي:



    var1, var2 = 35, 40

فالآن المتغير var1 اصبحت قيمته 35 ، و var2 أصبحت قيمته 40 .


تحويل نوع من البيانات إلى نوع آخر 

تسمح لك لغة البايثون بالتحويل اغلب انواع البيانات من نوع الى آخر . فمثلا يمكننا التحويل من نص str الى رقم من خلال استخدام التركيبة التالية :



    int(“64”)

وبطريقة مشابهة يمكنك التحويل بين العديد من أنواع البيانات و مماثلها كـ float ، bool و غيرها . 



التعليقات (comments)

لعمل تعليقات على داخل الكود في البايثون ، نستخدم الرمز # قبل السطر المراد جعله كتعليق . و لتعليم عدة أسطر كتعليق ، نستخدم ثلاث علامات تنصيص بداية التعليق و ثلاث علامات تنصيص نهاية التعليق . 


    # One line comment
    
    '''
    Multiline
    comment
    '''




حول المتغيرات ، تفصيل اكثر 


١. المتغيرات Variable
مقدمة في مفهوم المتغيرات Variables

ببساطة، يمكننا القول بأن المتغير variable هو عبارة عن طريقة نستخدمها لتخزين واسترجاع البيانات بشكلٍ مؤقت، فمن خلال المتغير يمكننا تخزين قيمة معينة، واسترجاعها متى أردنا، ويمكن النظر إليه أيضاً على أنه اسم يُشير إلى قيمة معينة value. وبما أنه “مُتغير”، فهذا يعني أن قيمته قابلة للتغير. من الأمثلة على المتغيرات ( العمر )، ‬لتوضيح هذا الأمر، لاحظ معي المثال التالي:


    myAge = 20

لاحظ هنا أننا قمنا بتعريف مُتغير باسم myAge، ومن ثم قمنا باسناد القيمة 20 له. الآن لو استخدمنا الاسم myAge في بقية البرنامج، فسيتم استبداله بالقيمة 20، وهذه هي الفكرة الأساسية من المتُغيرات.


 ‬تعريف أكثر‭ ‬من‭ ‬متغير في سطر واحد‭ ‬

يدعم عدد من لغات البرمجة ‬تعريف ‬أكثر‭ ‬من‭  ‬متغير‭ ‬في‭ ‬سطر‭ ‬واحد‭ ‬وذلك‭ ‬عن طريق استخدام‭ ‬الفاصلة ( , ) ووضعها بين أسماء تلك المتغيرات. لتوضيح الفكرة، لاحظ معي المثال التالي :‬ 


    myAge = 20, yourAge = 24

بدلاً من استخدام var مرتين، وفي سطرين مُختلفين، قمنا باستخدام var مرة واحدة، ومن ثم قمنا بتعريف الاسم myAge، يليه yourAge كما يظهر أمامك، ويمكن النظر لهذا الأمر على أنه طريقة مختصرة لتعريف أكثر من متغير.


تعيين قيمة جديدة للمتغير

ببساطة، المُتغير يتغير. ما نقصده بهذا الكلام أن اسم المتغير يشير إلى آخر قيمة تم إسنادها إليه، وعليه، في حال قمنا بتخزين قيمة جديدة في المتغير، فستكون تلك القيمة هي التي سيتم استبدالها مكان اسم المتغير. ‬لتوضيح الفكرة، لاحظ معي المثال التالي:


    myAge = 20
    myAge = 21

في السطر الأول تم تعريف المتغير وتخزين القيمة 20 فيه، بعد ذلك، قمنا “بتحديث” قيمة المتغير myAge إلى القيمة 21، وبما أنها آخر قيمة تم تخزينها في المتغير myAge، فستكون هي القيمة التي سيتم استبدالها مكان كل استخدام للمتغير myAge في البرنامج.

 ملاحظة: هناك فرق بين تعريف المتغير، وبين استخدامه، فالمتغير يتم تعريفه مرة واحدة فقط، وفي حالتنا هنا، عند استخدامنا لكلمة var، وبعد ذلك، يتم استخدامه، لذلك، لن نستخدم var في كل مرة نستخدم فيها myAge، وذلك لأن البرنامج تعرف عليه باستخدام var.
 
 ملاحظة: تستخدم لغات البرمجة طرق مُختلفة لتعريف المتغيرات، فمنها التي تستخدم كلمات مثل var و let، ومنها التي لا تحتاج إلى ذلك، وتكتفي فقط بذكر اسم المتغير واستخدامه بشكلٍ مُباشر.

بغض النظر عن لغة البرمجة التي تعمل عليها، فالمفهوم العام للمتغيرات واحد، وقد تختلف طريقة الكتابة أو تمثيل المتغيرات من لغة إلى أخرى، ويكفي النظر له بشكل عام على أن هناك مكان في الذاكرة يقوم بتخزين البيانات واسترجاعها، ونحن قمنا بإعطاء ذلك المكان اسما خاصاً به، وذلك الاسم هو اسم المتغير.


استخدام وتوظيف المتغير ‬

بعد‭ ‬إنشاء‭ ‬المتغير،‭ ‬يمكن‭ ‬استخدامه في أماكن مختلفة من البرنامج ومثال على ذلك، استخدامه في عملية الطباعة أو استخدامه في العمليات الحسابية، أو استخدامه في أي سياق يناسب ذلك المتغير. لتوضيح الفكرة، لاحظ معي المثال التالي:‬  ‬


    print(myAge)

قمنا باستخدام المتغير myAge مع print، وكما ذكرنا سابقاً، كل ما سيحدث هو عملية استبدال لاسم المتغير myAge بالقيمة التي يُشير إليها، وفي حالتنا هنا 20، وعليه، ستكون المُخرجات على النحو التالي:
 ‬

     20

ملاحظة : عند استدعاء المتغير للطباعة ستتم طباعة اخر قيمة أسندت له. 


تسمية المتغيرات

عند تسمية المتغيرات، هناك عدد من الشروط التي تفرضها لغات البرمجة، بالإضافة إلى عدد من الأساليب التي يستخدمها المبرمجين لهذا الغرض. سنتحدث في هذا الجزء عن شروط وأساليب تسمية المتغيرات.


شروط تسمية المتغيرات‬

عند إنشاء متغير، فأنت بحاجة إلى اختيار اسم مناسب لذلك المتغير، ويشمل ذلك، اختيار اسم يدل بشكل واضح على ماهية القيمة التي سيتم تخزينها فيه. في هذا الصدد، تضع بعض لغات البرمجة عدداً من الشروط عند تسمية المتغير، ورغم أن اللغات قد تختلف في هذا الأمر، إلا أنه بإمكاننا القول بشكلٍ عام، أن المتغير يجب:

- أن يبدأ اسم المتغير بحرف أو underscore.
- أن لا يبدأ برقم(رغم أنه قد يحتوي على أرقام).
- أن لا‭ ‬يحتوي ‬على‭ ‬مسافات.
- أن‭ ‬لا‭ ‬يكون‭ ‬الاسم‭ ‬من‭ ‬الكلمات‭ ‬المحجوزة reserved keywords‭ ‬ في‭ ‬لغة‭ ‬البرمجة نفسها.

ملاحظة: قد ‬تعتبر‭ ‬أسماء‭ ‬المُتغيرات‭ ‬في‭ ‬لغات البرمجة ‬حساسة‭ ‬لحالة‭ ‬الأحرف‭،‬case sensitive‭ ‬ أي‭ ‬أن‭ ‬المتغير‭ ‬username‭ ‬يختلف‭ ‬عن‭ ‬ userName‭ ‬ ويختلف‭ ‬كذلك‭ ‬عن ‭ ‬UserName.‬


أساليب في تسمية المتغيرات

يختلف المبرمجين والشركات في المعايير التي يستخدمونها في تسمية المتغيرات، ومع ذلك، يوجد عدد من الأساليب المشهورة والمتعارف عليها بين أوساط المبرمجين، منها:


- أسلوب Camel Case

في هذا الأسلوب، يتم كتابة اول كلمة في اسم المتغير بحروف صغيرة، وبعد ذلك،يتم كتابة الكلمات التي تليها بحرف كبير. ‬‬لتوضيح الفكرة، لاحظ معي المثال التالي:‬  ‬


    age = 20
    firstName = "Ahmed"
    dateOfBrith = "2020/03/20" 

ملاحظة : في حال كان اسم المتغير عبارة عن كلمة واحدة فيكتب بحروف صغيرة .


- أسلوب Pascal Case

في هذا الأسلوب، يتم كتابة كل كلمة من اسم المتغير بحرف كبير.‬‬ لتوضيح الف، لاحظ معي المثال التالي:‬  ‬


    Age = 20
    FirstName = "Ahmed"
    DateOfBrith = "2020/03/20" 



- أسلوب C Style 

في هذا الأسلوب، يتم كتابة كل كلمة من اسم المتغير بحروف صغيرة يفصل بينها بعلامة ـ .‬‬ لتوضيح الفكرة، لاحظ معي المثال التالي:‬  ‬


    age = 20
    first_name = "Ahmed"
    date_of_brith = "2020/03/20" 

ملاحظة : في حال كان اسم المتغير عبارة عن كلمة واحدة فيكتب بحروف صغيرة وليس هناك حاجة لوضع underscore.


المتغير والعمليات الأساسية‭

عند العمل مع المتغير variable، فغالباً، لن يخرج ما سنقوم به عليها عن ثلاث عمليات، وهي:

1. إنشاء متغير جديد create، وذلك من خلال اختيار اسم مناسب للمتغير يدل بوضوح على القيمة التي سيُشير إليها.
2. تخزين قيمة جديدة في المتغير write، وهذا الأمر بدوره سيقوم بمسح أو إزالة القيمة السابقة، وغالبا ما يتم هذا الأمر من خلال عملية الاسناد =. قد تُسمى هذه العملية، أي عملية تعيين قيمة جديدة للمتغير، باسم set.
3. جلب القيمة المخزنة read (نسخة منها)، ويتم هذا الأمر من خلال استخدام اسم المتغير، سواء في عملية طباعة أو في عملية حسابية او غيرها. قد تُسمى هذه العملية، أي عملية قراءة قيمة متغير معين، باسم get.



٦  أشياء يجب تذكرها عن المتغير

عندما نذكر كلمة متغيرات، فغالبا ما يكون لدينا ٦ أشياء يجب علينا تذكرها، وهي ترتبط ارتبطا وثيقا بالمتغير نفسه، وهذه الأشياء هي:

1. اسم المتغير name.
2. نوع المتغير type.
3. قيمة المتغير value.
4. مجال أو مدى المتغير scope.
5. دورة حياة المتغير life time.
6. عنوان المتغير أو مكانه في الذاكرة location.

ملاحظة: تختلف لغات البرمجة من حيث التركيز على هذه الأشياء الستة، فمثلاً، قد تخفي بعض لغات البرمجة واحد أو أكثر من هذه التفاصيل وتجعلها غير ذات أهمية بالنسبة للمبرمج كون اللغة تديرها في الخلفية دون أي تدخل من المبرمج.


اسم المتغير Variable Name 

يجب أن نعطي للمتغير اسما معبرا، فمثلا، من غير المعقول أن نقوم بتسمية متغير باسم width، أي العرض، ونقصد به العمر!، كون هذا الأمر مضلل، وستتعرف على أهمية هذا الأمر عند كتابة برامج وتطبيقات حقيقية، فكون المبرمج يضع أسماء لا تدل على مايحتويه المتغير فعلا، قد يدفع ثمنه من وقته وجهده عند مراجعته للشيفرة البرمجية التي كتبها بغرض تحسينها أو معالجتها من الأخطاء.

لتسمية المتغيرات شروط مختلفة في لغات البرمجة كما سبق وذكرنا، ورغم أن تلك الشروط قد تختلف من لغة لأخرى، إلا أنها قد تتفق في بعض الشروط، فمثلاً، تشترط بعض اللغات ان يبدا المتغير بحرف أو underscore (ـ)، وبعد ذلك يمكن وضع حروف وأرقام و underscore، وتمنع البدء برقم، بالاضافة إلى انها تمنع استخدام بعض الرموز في الاسم. بالاضافة إلى ذلك، هنالك لغات برمجة تبدأ المتغيرات فيها بعلامة $ ويسمح استخدام هذه العلامة في لغات برمجة اخرى كبداية لاسم متغير أيضا.

تعتبر تسمية المتغيرات من الأمور المهمة، كونها تعطي اسماً لمحتويات أو لبيانات معينة في ذاكرة الكمبيوتر، و تعتبر هي الطريقة التي تساعدنا على الوصول لتلك البيانات، لذلك، من الأفضل أن يكون الاسم الذي نختاره معبراً. بالإضافة الى ماذكرناه، يعتبر اسم المتغير مميزاً unique، أي أن كل متغير يجب ان يملك اسماً خاصاً يوضح الهدف منه،  و هذا التمييز يساعدنا على استخدام المتغير المناسب حسب اسمه في السياق المناسب.


نوع المتغير Variable type

بما أن المتغير يقوم بتخزين بيانات ويسترجعها، فما نوع تلك البيانات؟ هل هي نصوص Strings؟ أم أرقام Numbers؟ أم ماذا؟، ببساطة نحن نقوم بتخزين أرقام وحروف وغيرها، لذلك يجب أن نحدد نوعية البيانات التي سيقوم المتغير بتخزينها، وغالبا مايشار لهذا الأمر ب Datatype.

هناك لغات برمجة تفرض عليك تحديد نوع المتغير عندما تقوم بتعريفه، وهناك لغات برمجة أخرى ستكتشف نوع المتغير من القيمة التي أسندت له، وبغض النظر عن الطريقة، نحتاج إلى تحديد نوع المتغير لنحدد نوعية البيانات التي سيقوم بتخزينها. يمكنك النظر لنوع البيانات أو نوع المتغير على أنه نوع من القيود، فقبل تحديد النوع، كنا نفترض أنه بإمكاننا تخزين أي شيء، ولكن الأن قمنا بوضع بعض القيود على البيانات التي سيتم تخزينها في متغير معين، أي يجب أن تكون من نوع محدد، فمثلاً، لو حددنا نوع المتغير على أنه integer، فهذا يعني أن المتغير سيقوم بتخزين البيانات التي ستكون على هيئة أعداد صحيحة، ولن يقوم بتخزين النصوص والحروف  مثلاً(يوجد استثناء لهذا الأمر في بعض من لغات البرمجة).

تحتوي لغات البرمجة على العديد من الأنواع، منها ما يأتي مع اللغة ، و منها ما يقوم ببنائه المبرمج، ومن الأنواع المشهورة مثلاً، , char, int, float, و string. وضع أحد هذه الأنواع مع المتغير، هو إشارة الى أننا نود تخزين بيانات من ذلك النوع في المتغير. لتوضيح الفكرة، لاحظ معي المثال التالي


    myAge = 47

لاحظ كيف قمنا بوضع نوع البيانات int قبل اسم المتغير myAge، وبهذه الطريقة، قمنا بتحديد نوع البيانات التي سيتم تخزينها في ذلك المتغير، أي أن ذلك المتغير سيقوم بتخزين قيم أو أعداد أو أرقام صحيحة integers.

ملاحظة: يمكنك النظر لتحديد نوع المتغير على أنه نوع من أنواع القيود على محتوى ذلك المتغير، أي أنه “لن يقبل” تخزين قيمة فيه تكون من نوع بيانات آخر.



قيمة المتغير Variable Value

ببساطة، هي القيمة value التي ستضعها في المتغير، والتي تمثل البيانات data التي ستقوم بتخزينها واسترجاعها، ويجب أن تتوافق مع نوع المتغير الذي تم تحديده. تعتبر القيمة في حالة المتغير شيء قابل للتغير، ويمكننا إسناد القيمة للمتغير، غالباً، من خلال استخدام =.

ملاحظة : برمجياً، قد لا تتعرف على القيمة المناسبة التي تقوم بتخزينها في المتغير من البداية، ولتوضيح الأمر، ربما تطلب من المستخدم إدخال العمر، و من ثم ستقوم بتخزينه في المتغير، لذلك، و قبل ادخال المستخدم للعمر، سيبقى المتغير أو قيمته فارغة، لذلك نحن بحاجة الى مايسمى بالقيمة الإفتراضية default value , و هي قيمة أولية أو مؤقتة يضعها المبرمج للمتغير لحين الحصول على قيمة مناسبة و تخزينها. تسمى القيمة الإفتراضية أو الأولية أيضاً بإسم initial value، وليس شرطاً أن تكون هذه القيمة مؤقتة، فقد تستخدم بشكل فعلي كونها مناسبة في السياق البرمجي الذي استخدمت فيه.

ملاحظة: عند عدم تحديدك للقيمة بعد تعريف المتغير، عندها قد تكون قيمة ذلك المتغير عشوائية وغير معلومة أو قد تكون قيمة افتراضية، مثل صفر في حال كان نوع المتغير هو متغير رقمي يقوم بتخزين عدد صحيح integer على سبيل المثال. بكلامٍ آخر، تختلف لغات البرمجة في التعامل مع هذا 

بغض النظر عن لغة البرمجة التي تعمل أو ستعمل عليها، من الأفضل لك كمبرمج أن تجعل فكرة تمهيد المتغيرات بقيم أولية أمر مهم بالنسبة لك.

ملاحظة: تعتبر الثلاثه اجزاء الأولى التي تحدثنا عنها، الاسم name  والنوع type  والقيمه value اهم  الاجزاء في بدايه البرمجه، وبقيه الاجزاء الثلاثه الاخرى ستظهر اهميتها  عندما تتقدم في مجال البرمجة.
