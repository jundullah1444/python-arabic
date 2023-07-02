```python

# الحمد لله القوي المتين والصلاة والسلام على من بعث بالسبيف رحمة للعالمين, وعلى اله وأصحابه الغر الميامين وبعد:

# أسأل الله أن يكون ما يلي مفيدا لجنود الخلافة ضد أعداء الله. للبرمجة فوائد عديدة في محاربة العدو ، بدءا
# من برمجة الأسلحة والطائرات بدون طيار لإيصال الدعم الجوي لإخواننا ، إلى إنشاء مواقع الويب والروبوتات التي تنشر الدعوة

# تعليم البرمجة مع لغة البيثون خاص لجنود الخلافة



# الدرس الأول: الطباعة في بايثون
# تستخدم الدالة print() لعرض النصوص أو الأرقام على الشاشة

print("باقية")  # سيطبع البرنامج: باقية
print("1 + 1 = 2")  # سيطبع البرنامج: 2 = 1 + 1



# الدرس الثاني: المتغيرات في بايثون
# في بايثون، يمكنك تخزين القيم في ما يسمى "المتغيرات"
# لإنشاء متغير، كل ما عليك فعله هو إعطائه اسم وقيمة. مثلا:

اسمي = "أحمد"  # هنا قمنا بإنشاء متغير يدعى اسمي وأعطيناه القيمة "أحمد"

# يمكنك طباعة القيمة المخزنة في المتغير باستخدام دالة print()
print(اسمي)  # سيطبع البرنامج: أحمد


# الدرس الثالث: أنواع البيانات في بايثون
# بايثون تحتوي على العديد من أنواع البيانات، مثل الأرقام (int, float) والنصوص (str) والقوائم (list) والأطواق (tuple)

# نص (str)
دولة = "الدولة الاسلامية"  # هنا أعطينا المتغير "دولة" نص "الدولة الاسلامية"

# رقم صحيح (int)
قامت = 1435  # هنا أعطينا المتغير "قامت" الرقم 1435

# رقم عشري (float)
العمر = 9.5  # هنا أعطينا المتغير "العمر" الرقم 9.5

# قائمة (list)
سورة = ["ال عمران", "البقرة", "الفاتحة"]  # هنا أعطينا المتغير "سورة" قائمة من النصوص

# يمكننا طباعة كل هذه المتغيرات
print(دولة)  # سيطبع البرنامج: الدولة الاسلامية
print(قامت)  # سيطبع البرنامج: 1435
print(العمر)  # سيطبع البرنامج: 9.5
print(سورة)  # سيطبع البرنامج: ['الفاتحة', 'البقرة', 'ال عمران']



# الدرس الرابع: العمليات الأساسية في بايثون
# يمكنك أداء العديد من العمليات الرياضية في بايثون، مثل الجمع والطرح والضرب والقسمة

جمع = 7 + 3  # النتيجة ستكون 10
طرح = 7 - 3  # النتيجة ستكون 4
ضرب = 7 * 3  # النتيجة ستكون 21
قسمة = 7 / 3  # النتيجة ستكون حوالي 2.33

# يمكننا طباعة هذه النتائج
print(جمع)  # سيطبع البرنامج: 10
print(طرح)  # سيطبع البرنامج: 4
print(ضرب)  # سيطبع البرنامج: 21
print(قسمة)  # سيطبع البرنامج: 2.33



# الدرس الخامس: الشروط في بايثون
# يمكنك استخدام الشروط في بايثون لتنفيذ كود معين فقط إذا تم تحقق شرط معين

# مثال على ذلك:
العمر = 20

if العمر >= 60:
    print("أنت كبير")  # سيتم طباعة "أنت كبير" فقط إذا كان العمر أكبر من أو يساوي 60
else:
    print("أنت شاب")  # سيتم طباعة "أنت شاب" إذا كان العمر أقل من 60



# الدرس السادس: الحلقات في بايثون
# يمكنك استخدام الحلقات في بايثون لتكرار تنفيذ كود معين

# مثال على ذلك:
for i in range(5):
    print(i)  # سيتم طباعة الأرقام من 0 إلى 4


# الدرس السابع: الدوال في بايثون
# .الدوال في بايثون هي كتل من الكود قابلة لإعادة الاستخدام يمكنك تنفيذها عند الحاجة

# لإعلان الدالة، نستخدم كلمة الأمر "def"
def تحية():
    print("السلام عليكم!")

# الآن يمكننا استدعاء الدالة بكتابة اسمها متبوعاً بـ ()
# سيتم طباعة "السلام عليمن!"
تحية()


# الدرس الثامن: المعاملات في الدوال
# يمكن للدوال في بايثون أن تستلم معاملات (أو معلومات) لتعمل عليها
# مثلا، يمكننا إعلان دالة تقوم بجمع رقمين

def جمع(الرقم1, الرقم2):
    النتيجة = الرقم1 + الرقم2
    print(النتيجة)

# يمكننا الآن استدعاء الدالة وإعطائها الرقمين 3 و7
جمع(3, 7)  # سيتم طباعة 10
جمع(3, 7)  # سيتم طباعة 10




# الدرس التاسع: القوائم في بايثون
# القوائم في بايثون هي تجميعات مرتبة من العناصر التي يمكن أن تكون من أي نوع.
# يمكنك إنشاء قائمة باستخدام الأقواس المربعة []

الأنبياء = ["آدم", "نوح", "هود", "صالح"]

# يمكنك الوصول إلى عنصر في القائمة عن طريق مؤشره (تبدأ الأرقام من الصفر)
print(الأنبياء[0])  # سيطبع البرنامج: آدم





# الدرس العاشر: الحلقات والقوائم
# يمكنك استخدام الحلقات للتكرار على جميع عناصر القائمة
for نبي in الأنبياء:
    print(نبي)  # سيتم طباعة كل اسم في القائمة




# الدرس الحادي عشر: الدوال التي ترجع قيمة
# يمكن للدوال في بايثون أن ترجع قيمة باستخدام الأمر "return"

def ضرب(الرقم1, الرقم2):
    return الرقم1 * الرقم2  # ستعود الدالة بالقيمة التي تمثل ضرب الرقمين

النتيجة = ضرب(4, 5)
print(النتيجة)  # سيطبع البرنامج: 20






# الدرس الثاني عشر: القواميس في بايثون
# القواميس في بايثون هي بنية بيانات تستخدم لتخزين البيانات في شكل أزواج مفتاح-قيمة
# يمكنك إنشاء قاموس باستخدام الأقواس المتعرجة {}

الطالب = {"الاسم": "أحمد", "العمر": 20, "التخصص": "علم الشريعة"}

# يمكنك الوصول إلى القيم في القاموس عن طريق المفتاح
print(الطالب["الاسم"])  # سيطبع البرنامج: أحمد
print(الطالب["التخصص"]) # سيطبع البرنامج: علم الشريعة








# الدرس الثالث عشر: التعامل مع القواميس
الطالب = {"الاسم": "أحمد", "العمر": 20, "التخصص": "علم الشريعة"}

الطالب["العمر"] = 21  # تحديث القيمة
الطالب["الجنسية"] = "مصري"  # إضافة مفتاح وقيمة جديدين
print(الطالب)  # {'الاسم': 'أحمد', 'العمر': 21, 'التخصص': 'علم الشريعة', 'الجنسية': 'مصري'}




# الدرس الرابع عشر: الدوال المضمنة في بايثون
# بايثون يحتوي على العديد من الدوال المضمنة مثل sum(), len(), وغيرها
الأرقام = [1, 2, 3, 4, 5]
عدد_الأرقام = len(الأرقام)  # len() تقوم بحساب عدد العناصر في القائمة
مجموع_الأرقام = sum(الأرقام)  # sum() تقوم بجمع كل الأرقام في القائمة
print(عدد_الأرقام, مجموع_الأرقام)





# الدرس الخامس عشر: حل المشكلات بالبرمجة - تحليل المشكلة
# قبل أن نبدأ بكتابة الكود، يجب علينا تحليل المشكلة وفهم ما نريد تحقيقه. لدينا قائمة من الأرقام ونريد حساب المتوسط الحسابي لهذه الأرقام.





# الدرس السادس عشر: حل المشكلات بالبرمجة - تطبيق الحل
# بعد أن فهمنا المشكلة، نستطيع الآن تطبيق الحل وكتابة الكود.
الأرقام = [1, 2, 3, 4, 5]
المجموع = sum(الأرقام)  # حساب مجموع الأرقام
العدد = len(الأرقام)  # حساب عدد الأرقام
المتوسط = المجموع / العدد  # حساب المتوسط الحسابي




# الدرس السابع عشر: التعامل مع الملفات في بايثون
# يمكنك التعامل مع الملفات في بايثون لقراءة البيانات منها أو كتابة البيانات فيها

# لفتح ملف، نستخدم الدالة open()
الملف = open('ملف.txt', 'r')  # 'r' تعني أننا نريد قراءة الملف

# يمكننا الآن قراءة محتوى الملف
محتوى_الملف = الملف.read()

# لا تنسى أن تغلق الملف بعد الانتهاء منه
الملف.close()

# الدرس الثامن عشر: استثناءات بايثون
# الاستثناءات في بايثون هي أخطاء تحدث أثناء تنفيذ البرنامج.
# يمكنك التعامل مع هذه الأخطاء باستخدام الأوامر try و except

try:
    # كود قد يسبب خطأ
   النتيجة = 5 / 0
except ZeroDivisionError:
    # ما يجب فعله في حالة حدوث الخطأ
   print("لا يمكن القسمة على الصفر")





# الدرس التاسع عشر: الوحدات في بايثون
# الوحدات في بايثون هي ملفات تحتوي على كود بايثون يمكن استيراده واستخدامه في برنامجك.

# لنستورد وحدة math مثلا
import math

# الآن يمكننا استخدام الدوال والمتغيرات في هذه الوحدة
print(math.sqrt(16))  # الجذر التربيعي للعدد 16

# الدرس العشرين: مكتبات بايثون
# المكتبات في بايثون هي مجموعات من الوحدات توفر لك وظائف وأدوات مفيدة.

# لنستورد مكتبة datetime مثلا
from datetime import datetime

# الآن يمكننا الحصول على التاريخ والوقت الحالي
الآن = datetime.now()
print(الآن)




# الدرس الحادي والعشرون: البيانات الهيكلية (Data Structures)

# في علم الحاسوب، البيانات هي المعلومات التي يمكن تخزينها ومعالجتها بواسطة الكمبيوتر.
# الهياكل البيانية هي طرق خاصة لتنظيم هذه البيانات لتكون فعالة في مختلف العمليات مثل البحث، الإدراج، الحذف.

# تعلم البيانات الهيكلية مهم جدا لأنه يساعد على كفاءة البرمجة وتحسين الأداء.
# على سبيل المثال، إذا كنت تريد البحث عن عنصر في قائمة من مليون عنصر، فإن البيانات الهيكلية المناسبة يمكن أن تجعل البحث أسرع بكثير.

# المهندس الجيد هو الذي يعرف متى يستخدم البيانات الهيكلية المناسبة.
# على سبيل المثال، إذا كنت تريد تخزين أزواج من القيم ذات الصلة، فإن القاموس (Dictionary) قد يكون الخيار الأفضل.
# ومع ذلك، إذا كنت بحاجة إلى ترتيب العناصر أو إذا كان الترتيب يهم، فإن القائمة (List) قد تكون الأنسب.

# القوائم (Lists)
# القائمة هي هيكل بيانات يحتوي على مجموعة من العناصر المرتبة. يمكن الوصول إلى العناصر في القائمة باستخدام الفهرس.
# القوائم قوية في التعامل مع الترتيب والتكرار، ولكنها قد تكون أقل كفاءة عند البحث عن عناصر معينة.

my_list = [1, 2, 3, 4, 5]

# القواميس (Dictionaries)
# القاموس هو هيكل بيانات يحتوي على مجموعة من الأزواج المفتاح / القيمة. يمكن الوصول إلى القيم باستخدام المفاتيح المرتبطة بها.

#القواميس قوية في تخزين الأزواج وتحسين عمليات البحث، ولكنها تفتقد إلى الترتيب الطبيعي للعناصر.

my_dict = {'apple': 1, 'banana': 2, 'orange': 3}

# هناك العديد من البيانات الهيكلية الأخرى التي تستخدم بشكل شائع، مثل الكومة (Heap)، الأشجار (Trees)، الرسوم البيانية (Graphs)، والتي سنتعرف عليها في الدروس القادمة.
# الاختيار الأمثل للبيانات الهيكلية يمكن أن يؤدي إلى تحسينات كبيرة في أداء البرنامج وكفاءته.
# سنقوم بالغوص أكثر في كل من هذه البيانات الهيكلية في الدروس القادمة لفهمها بشكل أفضل وكيف يمكننا استخدامها بشكل أكثر فعالية في برامجنا.




# الدرس الثاني والعشرون: الخوارزميات (Algorithms)

# الخوارزمية هي مجموعة محددة ومحدودة من الخطوات التي توصف كيفية تنفيذ المهمة. في علم الحاسوب، الخوارزميات تساعدنا في حل المشكلات وتنفيذ العمليات بكفاءة.

# تعلم الخوارزميات مهم جداً لأنها تمكننا من حل المشكلات بكفاءة وفعالية.
# على سبيل المثال، تستخدم الخوارزميات في كل مكان من أنظمة البحث مثل Google إلى الذكاء الاصطناعي.

# المهندس الجيد لديه "حزام أدوات" يحتوي على العديد من الخوارزميات التي تعلمها.
# القدرة على اختيار الخوارزمية المناسبة للمشكلة المعينة هي مهارة أساسية في البرمجة.

# خوارزمية بحث خطي (Linear Search)
# البحث الخطي هو أبسط نوع من الخوارزميات. يتضمن فحص كل عنصر في القائمة بالترتيب حتى نجد ما نبحث عنه أو نصل إلى نهاية القائمة.

def linear_search(my_list, target):
    for i in range(len(my_list)):
        if my_list[i] == target:
            return i  # إذا تم العثور على الهدف، ارجع مؤشره
    return None  # إذا لم يتم العثور على الهدف، ارجع None

# سنستخدم البحث الخطي للعثور على كتاب في قائمة من الكتب، على سبيل المثال:

كتبي = ['صحيح البخاري', 'صحيح المسلم', 'فتح الباري', 'كتاب الجاد عن ابن النحاص']
print(linear_search(كتبي, 'كتاب الجاد عن ابن النحاص'))  # يجب أن يرجع 3

# الخوارزمية تتميز ببساطتها وسهولة فهمها، ويمكن استخدامها بسرعة للعثور على شيء في قائمة صغيرة.
# لكن العيب الرئيسي للبحث الخطي هو أنه يصبح بطيئًا جدًا إذا كانت القائمة كبيرة جدًا.

# على سبيل المثال، إذا كانت القائمة تحتوي على مليون عنصر أو تريليون عنصر، فقد يستغرق البحث وقتاً طويلاً للغاية لأنه يفحص كل عنصر فردًا.




# الدرس الثالث والعشرون: التعقيد الزمني (Time Complexity)

# التعقيد الزمني يصف كم من الوقت يستغرق الكود للتشغيل بالنسبة لحجم الإدخال. بالنسبة للبحث الخطي، التعقيد الزمني هو O(n)، حيث n هو عدد العناصر في القائمة.





# الدرس الرابع والعشرون: الخوارزميات الفرعية (Recursive Algorithms)

# الخوارزمية الفرعية هي تلك التي تحل المشكلة عن طريق حل نسخ أصغر من نفس المشكلة. خوارزمية فيبوناتشي التكرارية هي مثال جيد على هذا.

def fibonacci(n):
    if n <= 1:
        return n
    else:
        return(fibonacci(n-1) + fibonacci(n-2))

# طباعة العدد الفيبوناتشي العاشر
print(fibonacci(10))




# الدرس السادس والعشرون: خوارزميات البحث والترتيب (Search and Sort Algorithms)

# خوارزمية بحث ثنائية (Binary Search)
# البحث الثنائي هو خوارزمية بحث فعالة تعمل على قائمة مرتبة.
# تقسم الخوارزمية القائمة إلى نصفين في كل خطوة حتى تجد الهدف أو تكتشف أن القائمة لا تحتوي على الهدف.

def binary_search(arr, low, high, x):
    if high >= low:
        # Compute mid index
        mid = (high + low) // 2

        # If mid index matches the target, we found it
        if arr[mid] == x:
            return mid

        # If target is smaller than mid, it must be in the left half
        elif arr[mid] > x:
            return binary_search(arr, low, mid - 1, x)

        # If target is greater than mid, it must be in the right half
        else:
            return binary_search(arr, mid + 1, high, x)
    else:
        # If we can't divide anymore, target is not present in array
        return -1

# ترتيب فقاعي (Bubble Sort)
# الترتيب الفقاعي هو خوارزمية ترتيب بسيطة تعمل عن طريق تكرار المرور عبر القائمة،
# ومقارنة كل زوج من العناصر المتجاورة وتبديلهما إذا كانوا في النظام الخاطئ.

def bubble_sort(arr):
    n = len(arr)
    # Traverse through all array elements
    for i in range(n-1):
        # Last i elements are already sorted
        for j in range(0, n-i-1):
            # Traverse the array from 0 to n-i-1
            # Swap if the element found is greater than the next element
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]
    return arr

# الدرس السابع والعشرون: تعقيد الوقت وتدوين الـ Big O (Time Complexity and Big O Notation)

# تعقيد الوقت هو تقييم كيفية تغير الوقت الذي يستغرقه تشغيل البرنامج مع تغيير حجم المدخلات.
# تدوين الـ Big O يستخدم لوصف التعقيد الأساسي للخوارزميات.

# O(1) تعني التعقيد الثابت، حيث لا يتأثر الوقت بحجم المدخلات.
# O(n) تعني التعقيد الخطي، حيث يتناسب الوقت تناسباً طردياً مع حجم المدخلات.
# O(log n) تعني التعقيد اللوغاريتمي، حيث يقل الوقت الذي يستغرقه البرنامج كلما زادت المدخلات.

# مثال: خوارزمية البحث الثنائي تكون بتعقيد O(log n) لأنها تقسم القائمة إلى نصفين في كل خطوة.
# بينما خوارزمية الترتيب الفقاعي تكون بتعقيد O(n^2) لأنها تحتاج إلى مرور عبر القائمة n مرات لكل من العناصر n.




# الدرس السابع والعشرون: تعقيد الخوارزميات وتدوينة أو الكبير

# مقدمة في تعقيد الخوارزميات:
# تعقيد الخوارزمية هو مفهوم يستخدم لوصف كمية الموارد التي تحتاجها الخوارزمية لتنفيذها.
# قد تكون هذه الموارد الوقت (الوقت الحسابي) أو المساحة (الذاكرة).
# يساعد فهم تعقيد الخوارزمية في تحديد كيف سيتأثر أداء البرنامج عند تغيير حجم المدخلات.

# تدوينة أو الكبير:
# تدوينة أو الكبير هي طريقة لوصف تعقيد الخوارزمية.
# تدوينة أو الكبير تستخدم لوصف الحد الأقصى للوقت الذي قد يستغرقه تنفيذ الخوارزمية كدالة في حجم المدخلات.

# هناك مصطلحات أخرى مثل أوميغا الكبيرة (الحد الأدنى) وثيتا (الحد المتوسط) ولكننا سنركز على أو الكبير.

# تعقيد الخوارزمية الثابت O(1):
# يعني أن الخوارزمية تأخذ وقت ثابت للتنفيذ بغض النظر عن حجم المدخلات.

def print_first_item(items):
    print(items[0])

# تعقيد الخوارزمية الخطي O(n):
# يعني أن الخوارزمية تأخذ وقتًا متناسبًا مع حجم المدخلات.

def print_all_items(items):
    for item in items:
        print(item)

# تعقيد الخوارزمية اللوغاريتمي O(log n):
# يعني أن الخوارزمية تأخذ وقتًا يقل بمعدل متسارع كلما زادت المدخلات.

def binary_search(items, target):
    low = 0
    high = len(items) - 1
    while low <= high:
        mid = (low + high) // 2
        if items[mid] == target:
            return mid
        elif items[mid] < target:
            low = mid + 1
        else:
            high = mid - 1
    return None

# تعقيد الخوارزمية اللوغاريتمي الثنائي O(n log n):
# هذا هو الحد الأقصى للوقت الذي يمكن أن تأخذه خوارزمية الفرز الفعالة.

def quicksort(items):
    if len(items) <= 1:
        return items
    pivot = items[len(items) // 2]
    left = [x for x in items if x < pivot]
    middle = [x for x in items if x == pivot]
    right = [x for x in items if x > pivot]
    return quicksort(left) + middle + quicksort(right)

# تعقيد الخوارزمية التربيعي O(n^2):
# تستخدم في بعض خوارزميات الفرز مثل فرز الفقاعة.

def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]

# تعقيد الخوارزمية الأسي O(2^n):
# تستخدم في بعض الخوارزميات مثل حل مشكلة الرحلة البيانية (Traveling Salesman Problem) عن طريق القوة الغاشمة.

def fibonacci(n):
    if n <= 1:
       return n
    else:
       return(fibonacci(n-1) + fibonacci(n-2))



# الدرس الثامن والعشرون: الأشجار في علوم الحاسوب

# الأشجار هي بنية بيانات غير خطية تستخدم لتمثيل العلاقات التي تحتوي على "الأب" و"الأطفال".
# بحيث يكون لكل عقدة واحدة على الأكثر "أب"، وعدد من الأطفال.
# هذه البنية تستخدم في العديد من الحالات، بما في ذلك تمثيل الأنظمة الأساسية في الحوسبة والرسوم البيانية والألعاب.

# سنقوم بتمثيل الشجرة باستخدام العقد في هذا الدرس.

class Node:
    def __init__(self, data):
        self.data = data
        self.children = []

    def add_child(self, node):
        self.children.append(node)

# الآن، سنقوم ببناء الشجرة:

root = Node('root')
child1 = Node('child1')
child2 = Node('child2')

root.add_child(child1)
root.add_child(child2)





# الدرس التاسع والعشرون: خوارزميات البحث في الأشجار

# تعتبر خوارزمية البحث عمق الأول (DFS) واحدة من أهم الطرق للبحث في الأشجار والرسوم البيانية.
# تبدأ خوارزمية DFS البحث من العقدة الجذر، ثم تتعمق في كل فرع حتى تصل إلى العقدة الأخيرة في ذلك الفرع قبل الانتقال إلى الفرع الآخر.

def dfs(node):
    print(node.data)
    for child in node.children:
        dfs(child)

dfs(root)

# خوارزمية البحث عرض الأول (BFS) هي خوارزمية أخرى للبحث في الأشجار والرسوم البيانية.
# تبدأ خوارزمية BFS البحث من العقدة الجذر، ثم تتحرك عبر الشجرة بمستوى واحد في كل مرة، بدءًا من اليسار إلى اليمين.

def bfs(root):
    queue = [root]
    while queue:
        current_node = queue.pop(0)
        print(current_node.data)
        queue.extend(current_node.children)

bfs(root)




# الدرس الثلاثين: البحث الثنائي
# البحث الثنائي هو نوع من خوارزميات البحث التي تستخدم للبحث عن عنصر في قائمة مرتبة. تعتمد على تقسيم القائمة إلى نصفين في كل خطوة بحث
# والتحقق من إذا كان العنصر المطلوب هو العنصر الموجود في الوسط.

# البحث الثنائي أكثر كفاءة من خوارزمية البحث الخطي، وخاصة عندما يكون لدينا قائمة طويلة جدا، لأنه يقلل من عدد العناصر التي نحتاج إلى التحقق منها بشكل كبير.

def binary_search(sorted_list, target):
    low = 0
    high = len(sorted_list) - 1

    while low <= high:
        mid = (low + high) // 2
        guess = sorted_list[mid]
        if guess == target:
            return mid
        elif guess > target:
            high = mid - 1
        else:
            low = mid + 1
    return None

# الدرس الحادي والثلاثين: خوارزميات الرسم البياني
# الرسوم البيانية هي بنية بيانات تتألف من العقد (التي قد تمثل الأشياء مثل المدن أو الأشخاص أو الصفحات الويب) والحواف (التي تمثل العلاقات بين العقد).
# تستخدم الرسوم البيانية في العديد من التطبيقات، بما في ذلك تحليل الشبكات الاجتماعية، وتحديد أقصر الطرق في خرائط الطرق، وتحليل الروابط بين صفحات الويب.

# سنستخدم القائمة الجوارة لتمثيل الرسم البياني.

graph = {
    'A': ['B', 'C'],
    'B': ['A', 'D', 'E'],
    'C': ['A', 'F'],
    'D': ['B'],
    'E': ['B', 'F'],
    'F': ['C', 'E'],
}

# خوارزمية البحث عمق الأول (DFS) يمكن استخدامها للبحث في الرسم البياني.

def dfs(graph, node, visited):
    if node not in visited:
        visited.append(node)
        for n in graph[node]:
            dfs(graph, n, visited)
    return visited

visited = dfs(graph, 'A', [])

# خوارزمية البحث عرض الأول (BFS) يمكن أيضًا استخدامها للبحث في الرسم البياني.

def bfs(graph, root):
    visited = []
    queue = [root]

    while queue:
        node = queue.pop(0)
        if node not in visited:
            visited.append(node)
            queue.extend(graph[node])

    return visited

visited = bfs(graph, 'A')






# والله غالب على أمره ولكن اكثر الناس لا يعلمون. والحمد لله رب العالمين
