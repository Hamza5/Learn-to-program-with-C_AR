# <div dir='rtl'>تعلّم البرمجة بلغة الـC</div>

## <div dir='rtl'>عن المشروع</div>

<div dir='rtl'>
هذا الكتاب هو ترجمة لـ
<a href='https://openclassrooms.com/courses/apprenez-a-programmer-en-c'>درس تعلّم البرمجة لغة الـC</a>
 الخاص بموقع OpenClassrooms من الفرنسيّة إلى العربية. الترجمة ليست حرفية في كثير من الفقرات و قد تكون مختصرة نسبيا مقارنة بالنص الأصلي خصوصا في حالات وجود التكرار، رغم ذلك، فقد حرصنا على نقل كلّ الأفكار التي قدّمها الكاتب في الدرس الأصلي من بدايته إلى نهايته. كما بذلنا جهدنا في أن يكون النص بسيطا قدر الإمكان و مفهوما للقارئ العربي العادي.
</div>

## <div dir='rtl'>التقدّم</div>

<div dir='rtl'>
ترجمة الدرس و مراجعته تمّت بشكل متقطع على مدى السنوات الثلاث الأخيرة و الآن يتم تحضيرها على شكل كتاب رقمي.
</div>

#### <div dir='rtl'> فصول الكتاب (الفصول المكتملة تم تعليمها) </div>

- [x] <span dir='rtl'>مقدمة المترجمة</span>
- [x] <span dir='rtl'>مقدمة المؤلف</span>
- [ ] <span dir='rtl'>أساسيّات البرمحة بلغة الـC</span>
    - [x] <span dir='rtl'>قلت برمجة ؟</span>
    - [ ] <span dir='rtl'>الحصول على الأدوات اللازمة</span>
    - [x] <span dir='rtl'>برنامجك الأوّل</span>
    - [x] <span dir='rtl'>عالم المتغيّرات</span>
    - [ ] <span dir='rtl'>حسابات سهلة</span>
    - [ ] <span dir='rtl'>الشروط</span>
    - [ ] <span dir='rtl'>الحلقات التكراريّة</span>
    - [ ] <span dir='rtl'>عمل تطبيقي: "أكثر أو أقل"، لعبتك الأولى</span>
    - [ ] <span dir='rtl'>الدوال</span>
- [ ] <span dir='rtl'>تقنيات متقدّمة في لغة الـC</span>
    - [x] <span dir='rtl'>البرمجة المجزأة</span>
    - [x] <span dir='rtl'>المؤشّرات</span>
    - [x] <span dir='rtl'>الجداول</span>
    - [x] <span dir='rtl'>السلاسل المحرفيّة</span>
    - [x] <span dir='rtl'>المعالج القبلي</span>
    - [ ] <span dir='rtl'>انشئ أنواع متغيّرات خاصة بك</span>
    - [ ] <span dir='rtl'>قراءة و كتابة الملفّات</span>
    - [ ] <span dir='rtl'>الحجز الحيّ للذاكرة</span>
    - [ ] <span dir='rtl'>عمل تطبيقي: لعبة الـPendu</span>
    - [ ] <span dir='rtl'>ادخال نص بشكل أكثر أمانا</span>
- [ ] <span dir='rtl'>إنشاء ألعاب 2D في SDL</span>
    - [ ] <span dir='rtl'>تثبيت SDL</span>
    - [ ] <span dir='rtl'>انشاء نافذة و مساحات</span>
    - [ ] <span dir='rtl'>اظهار صور</span>
    - [ ] <span dir='rtl'>التحكّم في الاحداث</span>
    - [ ] <span dir='rtl'>عمل تطبيقي: Mario Sokoban</span>
    - [ ] <span dir='rtl'>تحكّم في الوقت</span>
    - [ ] <span dir='rtl'>كتابة نصوص باستخدام SDL_ttf</span>
    - [ ] <span dir='rtl'>تشغيل الصوت بـFMOD</span>
    - [ ] <span dir='rtl'>عمل تطبيقي: الاظهار الطيفيّ للصوت</span>
- [ ] <span dir='rtl'>هياكل البيانات</span>
    - [ ] <span dir='rtl'>السلاسل المتّصلة</span>
    - [ ] <span dir='rtl'>المكدّسات و الطوابير</span>
    - [ ] <span dir='rtl'>جداول التجزئة</span>

## <div dir='rtl'>الترخيص</div>

<div dir='rtl'>
نظرا لأن محتوى الدرس الأصلي مرخّص تحت
<a href='https://creativecommons.org/licenses/by-nc-sa/2.0/'>ترخيص المشاع الإبداعي، نسب المصنف - غير تجاري - الترخيص بالمثل، النسخة الثانية (CC-BY-NC-SA 2.0)</a>
 فإن المحتوى المترجم مرخّص بذات الرخصة.
</div>

## <div dir='rtl'>البناء</div>

<div dir='rtl'>
الملفات المصدرية في هذا المشروع مكتوبة بلغة LaTeX، لكن يجب ترجمتها بمترجم XeLaTex أو LuaLaTex لأنها تحتوي على محارف Unicode (هذا لأنها مكتوبة بالعربيّة)، و يفترض أنّ هذين المترجمين يكونان مرفقين في أي توزيعة TexLive أو MikTex.
<br>
نحن نترجمها بالأمر التالي باستخدام المترجم XeLaTex:
</div>
```
xelatex book.tex
```
<div dir='rtl'>
ينتج عن هذا الأمر ملف book.pdf يمثّل الكتاب، أما بقيّة الملفات فغير ضرورية و يمكن التخلّص منها.
</div>

#### <div dir='rtl'>الاعتماديّات</div>

<div dir='rtl'>يجب أن تكون الحزم التالية متوفرة في توزيعتك لكي تتم عملية الترجمة بنجاح:</div>

* fontspec
* tcolorbox
* graphicx
* adjustbox
* hyperref
* fancyhdr
* polyglossia
* geometry
* listings
* bidi
* float
* xcolor
* tabu
* booktabs

## <div dir='rtl'>المساهمة</div>

<div dir='rtl'>
إذا عثرت على أية أخطاء في هذا الكتاب، علمية كانت أو لغوية، أو أيّا كان نوعها، فيسرنا أن تقوم بإبلاغنا بها.
</div>
