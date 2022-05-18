
مفهوم ORM و Migrations

قبل البدء بكتابة Model لابد من التعرف على مفهومين أساسين وهما:

- مفهوم Object Relational Mapper(ORM)
-  مفهوم Migrations
![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1651056613934_image.png)


أولا: مفهوم Object Relational Mapper(ORM)
في معظم تطبيقات الويب نحتاج للتفاعل مع البيانات عن طريق (تخزين، عرض، تعديل، حذف) البيانات. و يقوم Django بتوفير طريقة سهلة للتعامل مع قواعد البيانات عن طريق ORM.

![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1651057227814_image.png)


يساعد ORM بتحويل أكواد Python إلى database schema & tables من دون الحاجة لفهم تفاصيل قواعد البيانات وهذا يساعد في تسريع Web Development لأننا نستطيع تعريف قواعد البيانات باستخدام أكواد مكتوبة بلغة Python.
 

 مكونات Object Relational Mapper(ORM)
![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1651058633959_image.png)



أولا: Model 
ويتم تمثيله عن طريق Python Class بحيث يمثل البيانات الخاصة بتطبيق معين، ونقوم بتعريف fields الخاصة بالبيانات ونوعها بداخل هذا Class.
 مثل: الاسم ورقم الطالب إذا كنا نريد بناء قاعدة بيانات خاصة بالطلاب.

----------


![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1651058659709_image.png)


 

ثانيا: Migrations
يساعد في تحديث قاعدة البيانات المكتوبة بلغة SQL بحيث تكون متوافقة مع Model الذي تم كتابته بلغة Python.






----------


![](https://paper-attachments.dropbox.com/s_891266F9C0268F233056BDDFA8727ABE33AA9B24618CDE2386552BF1BA469F74_1651058711946_image.png)


مثال توضيحي:
لو كان لدينا Model يحتوي fields خاصة بالطلاب (الاسم ورقم الطالب)، وبعد فترة زمنية أردنا تغيير Model بحيث يشمل المعدل التراكمي للطالب، في هذه الحالة سوف نقوم بإضافة المعدل بداخل Model وأيضا نحتاج لعمل نفس التغييرات على قاعدة البيانات وهنا يأتي دور Migrations التي تقوم بتحديث قواعد البيانات بحيث تكون متطابقة مع ملف Model.

