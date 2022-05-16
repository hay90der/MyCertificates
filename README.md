# مولد الشهادات
اداة تسمح لك بتوليد الشهادات بمختلف اللغات (العربية كذلك) ، كشهادات الكورسات، شهادات اتمام كورس معين، شهادة اتمام موضوع...الخ وبصورة سريعة جداً وبجودة عالية. <br/>
هذا ليس كل شيء فهذه الاداة تولد لك الشهادات وبدون حد يذكر ، حيث يمكنك توليد اكثر من 500 شهادة بضغطة زر واحدة. <br/>
هل هذا كل شيء؟ ؛) بالتأكيد كلا ليس كل شيء ، من خلال هذه الاداة يمكنك الكتابة باللغات العربية والهندية والإنجليزية وغيرها  <br/>
وهل هذا كل شيء ؟! بالطبع لا، فهناك ميزة اضافية وهي ارسال الشهادات بصورة مباشرة لأيميلات الطلاب او المشاركين في دوراتك وندواتك <br/>
هي مفتوحة المصدر ويمكن التعديل عليها حسب الرغبة <br/> 
مكتوبة مع <3 بلغة بايثون <br/>

# المكتبات المطلوبة
<div align='right'>
<i> pip install arabic-reshaper </i><br/>
<i> pip install hashlib </i><br/>
<i> pip install qrcode </i><br/>
<i> pip install python-bidi </i><br/>
<i> pip install PIL </i><br/>
<i> pip install pandas </i><br/>
<i> pip install smtplib </i><br/>
<i> pip install imghdr </i><br/>
</div>

# كيفية الاستخدام

<div align='right' dir='rtl'>
<li>اولا قم بتثبيت المكتبات المطلوبة</li>
<li>قم بتحضير ملف الاسماء والايميلات والذي يجب ان يكون بصيغة سي اس في ، ولكي يدعم اللغة العربية يجب استخدام احدى الادوات المجانية المتاحة على الانترنت  وقم بتحويل الملف من صيغة الاكسل الى صيغة سي اس في</li>
<li>قم بتحضير صورة الشهادة المراد استخدامها ، وقم بتسميتها <b><i>certificate.jpg</i></b> </li>
<li> استخدم الخط المرفق الذي قمت برفعه مع الملفات ، او يمكنك ببساطة استخدام اي خط آخر
<li><b> xy=(525,440) </b> قم بالتعديل على مكان وضع الكتابة على صورة الشهادة من خلال تعديل الكود التالي وحسب ابعاد الصورة</li>
<li>اذا كنت تروم ارسال هذه الشهادات عن طريق خدمة الجيميل 
<a href='https://stackoverflow.com/questions/16512592/login-credentials-not-working-with-gmail-smtp' alt='stackoverflow'>فيجب اتباع الرابط التالي لمزيد من المعلومات</a> </li>

</div>

# MyCertificates
Certificates Generator A tool that allows you to generate certificates with multiple languages (Arabic as well) such as course certificates, certificates of completing a specific course, certificate of completion of a topic ... etc. Very quickly, with high quality. 
This is not all, this tool generates certificates for you without a limit, where you can generate more than 500 certificates with the click of a button.
Is that all ?! Of course not, there is an additional advantage which is sending certificates directly to the emails of students or participants in your courses and seminars 
And is that all ? ;) its not all, you can write in arabic, hindi, english and more
It is open source and can be modified as desired.
Written with &lt;3 in Python.

# Required Libraries
<i> pip install arabic-reshaper </i><br/>
<i> pip install hashlib </i><br/>
<i> pip install qrcode </i><br/>
<i> pip install python-bidi </i><br/>
<i> pip install PIL </i><br/>
<i> pip install pandas </i><br/>
<i> pip install smtplib </i><br/>
<i> pip install imghdr </i><br/>


# How to use
<li>Imports all required libraries</li>
<li>Prepare the CSV file (which contains names & emails), <b><i>for arabic language please use any online tools to convert from xlsx to csv to support arabic</i></b></li>
<li>Prepare your certificate image and name it as <b><i>certificate.jpg</i></b> </li>
<li>Use the font <b><i>arial.ttf</i></b> that I've palced already in this repository , <i> or just simply use any font you wanted ;) </i> </li>
<li>Adjust the text position in <b> xy=(525,440) </b></li>
<li>If you are sending from <b>Gmail</b>, you will need to <a href='https://stackoverflow.com/questions/16512592/login-credentials-not-working-with-gmail-smtp' alt='stackoverflow'>check this link out</a> </li>
