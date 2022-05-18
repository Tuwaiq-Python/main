
# مقدمة عن Django

![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1652208910386_image.png)




يعتبر Django من أشهر Framework مفتوحة المصدر الخاصة بتطبيقات الويب ويستخدم في مواقع مشهورة مثل: Disqus, Instagram, Pinterest.



# ماهي Web Frameworks؟
![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1652209013570_image.png)


يوجد لدينا Web Frameworks مشهورة مثل: ReactJS، Angular، Vue, Django ويمكن تصنيف هذه Frameworks إلى ثلاثة أنواع كالتالي:

- أولا: Front-end Frameworks وهي تعبر عن كل مايراه المستخدم أو الأجزاء التي يتعامل معها المستخدم أثناء تصفح واجهات الموقع مثل الألوان والخطوط و dropdown menus وبشكل عام مكونات  HTML و CSS و JavaScript. 
- ثانيا: Back-end Frameworks وهي مايُمكن Front-end Frameworks من العمل ويقوم بحفظ البيانات الخاصة بالموقع وتشمل أيضا server و application.
- ثالثا: Full-stack Frameworks وهي تشمل النوعين السابقين، حيث يعمل Full-stack Developer على Client-side و Server-side .

 

![](https://paper-attachments.dropbox.com/s_1D6B086A45BCF6338C718F8B8F973D33B9FC54F52764DC46881B977111A9EBB6_1621763570863_Screen+Shot+2021-05-23+at+12.52.42+PM.png)


أما Django فهو Full-stack Framework بحيث يكون مسؤول عن بناء واجهات صفحات الويب عن طريق Templates ويتفاعل مع قواعد البيانات عن طريق Models.
ويمكن أيضا أن نستخدم Django ك  Back-end Framework و نحسن واجهات Django أو نضيف لها Interactivity عن طريق  Front-end Frameworks مثل: ReactJS.

مميزات Django Framework:

- يعتبر batteries included web framework والمقصود هو أن Django تقدم العديد من المميزات مثل: libraries و packages التي تسهل عملية تطوير المواقع على المبرمج ومن أمثلة ذلك: ORM التي تساعد في بناء قواعد البيانات باستخدام لغة python دون الحاجة لكتابة أكواد بلغة SQL، أيضا توفر واجهات Admin جاهزة وغيرها. 
- يساعد في إنشاء تطبيقات تتميز بأنها مرنة (reliable) بحيث يكون لديها القدرة في أنها تكبر لتتناسب مع احتياجاتنا.
-  يساعد في إنشاء تطبيقات أمنة (secure) وسهلة التعلم.
- لديها built-in database querying و URL mapping و template rendering.

  
  

![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1652209231606_image.png)

                 المهارات التي نحتاجها لتعلم Django هي:
- معرفة أساسيات لغة Python
- معرفة أساسيات HTML, CSS, JavaScript
- معرفة أساسيات قواعد البيانات SQL


![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1652209306530_image.png)


الأدوات التي نحتاجها لتعلم Django هي:

- تحميل Python نسخة 3 وأعلى. 
- تحميل Editor مناسب مثل PyCharm.
- تحميل Django نسخة 3 وأعلى.


مفهومي MVC و MVT

كلمة MVC  هي اختصار (Model View Controller) وهو يمثل Architectural Pattern ويستخدم كوسيلة لفصل واجهة المستخدم (User Interface) للتطبيق إلى ثلاثة جوانب رئيسية:
أولا: Model: يعبر عن البيانات التي يتم عرضها في الواجهات التي تظهر للمستخدم بالإضافة إلى قواعد تغيير البيانات ومعالجتها.
ثانيا: View: يعبر عن الواجهات التي يتم عرضها للمستخدم.
ثالثا: Controller: يعبر عن الجزء الذي ينظم التفاعل بين Model  و View ويتعامل مع المستخدم.


![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1652209407173_image.png)


في Django نستخدم نموذج مشابه يسمى MVT وهو اختصار (Model View Template) حيث يمثل كل جزء التالي:
أولا: Model: يعبر عن البيانات التي يتم عرضها في الواجهات التي تظهر للمستخدم بالإضافة إلى قواعد تغيير البيانات ومعالجتها.
ثانيا: View: يعبر عن الجزء الذي ينظم التفاعل بين Model و Template.
ثالثا: Template: يعبر عن الواجهات التي يتم عرضها للمستخدم.


![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1652209763016_image.png)


في Django عادة مايتم تمثيل View على شكل Function أو Class يقوم بعمل Query على بيانات Model ثم يقوم بعرضها على الواجهات Template.

مثال:
لنفرض أنك تقوم باستعراض قائمة الكتب من موقع إحدى المكتبات، في هذه الحالة يمثل تمثيل MVT كالتالي:

- الواجهة أو الصفحات التي تحتوى على قائمة الكتب (تمثل جزء Template).
- البيانات المخزنة في قواعد البيانات الخاصة بالكتب مثل عنوان وصورة الكتاب (تمثل جزء Model)
- أخيرا (جزء View) ينظم التفاعل بين Model و Template و يمكن أن يتم تمثيل View على 

شكل (BookList Function) هذه Function تقوم بإرجاع البيانات الخاصة بالكتب عن طريق عمل Query على قاعدة البيانات، ثم تقوم بعرض هذه البيانات (الكتب) على الواجهات.


الفرق بين MVC و MVT
- في نموذج MVC يقوم Controller بتنظيم التفاعل بين Model و View.
- في نموذج MVT يقوم جزء View بتنظم التفاعل بين Model و Template .


- في نموذج MVC يمثل View جزء الواجهات.
- في نموذج MVT يمثل Template جزء الواجهات.


- في نموذج MVC نقوم ببرمجة الثلاث مكونات بنفس لغة البرمجة.
- في نموذج MVT يتم عمل Template بلغة مختلفة، على سبيل المثال: في Django نقوم بكتابة Model و View بلغة Python أما Template نقوم بكتابتها عن طريق HTML.


تحميل Django Framework
تحميل Django Framework لنظام MacOS

لتحميل الأدوات التي نحتاجها لتعلم Django على نظام MacOS، قم باتباع التعليمات في الفيديو التالي:

https://satr.codes/courses/ba82119d-6d04-4ca1-bd4d-9667b04525b6/session/bc0db2e9-949b-45ca-a46c-5fba3390899f/view

تحميل Django Framework لنظام Windows

لتحميل الأدوات التي نحتاجها لتعلم Django على نظام Windows، قم باتباع التعليمات في الفيديو التالي:

https://satr.codes/courses/ba82119d-6d04-4ca1-bd4d-9667b04525b6/session/403b3199-8d72-43eb-8796-94ac4ab8e692/view



مفهوم World Wide Web

قبل البدء في تطوير مواقع الويب، نحتاج أولاً إلى معرفة مفهوم الويب بشكل عام. الويب هو عبارة عن نظام من صفحات الويب التي نستطيع الوصول إليها من خلال الإنترنت. مما يعني أن الويب ليس الإنترنت، بل هو واحد من التطبيقات التي تم إنشاؤها على الإنترنت. هناك بعض الأجزاء في World Wide Web نحتاج إلى فهمها ومعرفة الغرض من وجودها لكثرة استخدام مصطلحاتها أثناء تطوير تطبيقات الويب وهي Client, Server, Request, Response.

![](https://paper-attachments.dropbox.com/s_803AD9971490A5B412A11F053A6B7B478D6C3D309C1FBA548D35327DE9020899_1627919570518_image.png)


عندما يتصفح المستخدم الإنترنت من خلال PC, Laptop, Smart Phone, iPad في هذه الحالة يعتبرمستخدم (Client)، بحيث أنه عندما يبحث عن موقع معين من خلال وضع رابط هذا الموقع في المتصفح فهو في هذه الحالة يقوم بإرسال طلب (Request) أي طلب لهذا الموقع، في هذه الأثناء يقوم الخادم (Server) باستقبال طلب المستخدم للموقع ثم يقوم بعرض هذا الموقع للمستخدم كـرد (Response) لطلب المستخدم.



![](https://paper-attachments.dropbox.com/s_803AD9971490A5B412A11F053A6B7B478D6C3D309C1FBA548D35327DE9020899_1627919583193_image.png)

مثال: 

عندما تقوم بفتح المتصفح (safari أو google chrome مثلاً) وتقوم بالبحث عن منصة طويق التعليمية من خلال الرابط `www.tuwaiq.codes` في هذه الحالة أنت Client، ويقوم بعدها DNS باستقبال طلبك لتحويل ذلك الرابط إلى IP address الخاص بمنصة طويق التعليمة، حتى يرسل طلبك إلى Server منصة طويق التعليمة، بعد ذلك يقوم Server منصة طويق التعليمية بالرد على طلبك من خلال عرض الموقع لك.


![](https://paper-attachments.dropbox.com/s_803AD9971490A5B412A11F053A6B7B478D6C3D309C1FBA548D35327DE9020899_1627920531893_image.png)



> ماهو DNS ؟ هو اختصار لمصطلح Domain Name System يستخدم لربط اسم الموقع أو رابط الموقع بعنوان IP address  لذلك الموقع، لأنه من الصعب أن نقوم بحفظ IP address لكل المواقع التي نريد زيارتها، فيقوم DNS بالمساعدة بحيث يربط اسم كل موقع بالعنوان الحقيقي للخادم Server الخاص به. فتبحث أنت باستخدام اسم الموقع مثل `google.com` ويقوم DNS بإيجاد العنوان المقابل `216.58.212.110` وإرسال Request للخادم Server الخاص بذلك الموقع.


![العناوين ليست دقيقة، مجرد مثال.](https://paper-attachments.dropbox.com/s_803AD9971490A5B412A11F053A6B7B478D6C3D309C1FBA548D35327DE9020899_1627920454416_image.png)



كيف يعمل Internet

لنفترض أنك تريد الوصول لبيانات معينة من خلال Laptop أو Smart Phone موصول بشبكة الانترنت من خلال wifi. والبيانات التي تريد الوصول لها مثلاً عبارة عن مقطع Youtube مخزن في مركز بيانات شركة Youtube. لكن كيف تستطيع الوصول لذلك المقطع؟ 


![](https://paper-attachments.dropbox.com/s_4160F6DE7C6BAA2EB66EAEB7A845FBF4C0469F3877CA1B209DF191E1F3F78A5D_1627924002046_image.png)


أي جهاز موصول بشبكة الانترنت يكون معرّف من خلال مجموعة من الأرقام تسمى IP address. تلك العناوين يتم توفيرها من خلال ISP (Internet Service Provider) والتي تقوم بتوفير عنوان مختلف لكل جهاز في شبكة الانترنت. كذلك Server الذي يحتوي على المقطع الذي تريد مشاهدته يكون له عنوان IP خاص به.

![](https://paper-attachments.dropbox.com/s_4160F6DE7C6BAA2EB66EAEB7A845FBF4C0469F3877CA1B209DF191E1F3F78A5D_1627924288139_image.png)


فمن خلال عناوين IP يكون هناك مُرسل Sender ومُستقبل Receiver. 


![](https://paper-attachments.dropbox.com/s_4160F6DE7C6BAA2EB66EAEB7A845FBF4C0469F3877CA1B209DF191E1F3F78A5D_1627924532377_image.png)


وهذا يعني أن موقع Youtube يملك عنوان IP خاص به، لكن للبحث عنه والوصل إليه لا يشترط أن نقوم بحفظ عنوان IP. يمكننا استخدام الرابط `youtube.com` وذلك بمساعدة DNS الذي يقوم بربط كل عنوان IP باسم يسهل حفظه والبحث عنه باستمرار.


![](https://paper-attachments.dropbox.com/s_4160F6DE7C6BAA2EB66EAEB7A845FBF4C0469F3877CA1B209DF191E1F3F78A5D_1627925633246_image.png)

مكونات URL
