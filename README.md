# OS5
## محمدعلی عطار علیایی
### تمرین پنجم
سوال1 : با استفاده از دو دستور زیر میتوان نام کاربری و پسورد خود را در گیت ست کرد

git config --global user.name "YourName"

git config --global user.email "YourEmail"

و بعد از اون نیازی نیست برای هر بار پوش کردن مجدد نام کاربری و پسورد را وارد کرد

---------------------------------------------------------------------------------

سوال 2:

.gitignor:

گیت با استفاده از این فایل از بررسی برخی از فایل ها یا فولدر ها صرف نظر میکند
و تغییرات انها را نادیده میگیرد وانها را دنبال نمیکند

.git:

بعد از ایجاد گیت در پروژه این فایل برای ما به صورت هاید ایجاد میشود که تمام تغییرات پروژه رو دنبال میکند

و تمام اطلاعات را در خود دارد و با پاک کردن ان سابقه آن پروژه نیز پاک میشود

git pull :

با استفاده از این دستور میتوانید پروژه خود را بروزرسانی کنید و اخرین تغییرات را از سرور دریافت کنید

branch:

زمانی که با گیت یک ریپازیتوری جدید می سازیم ، به صورت خودکار یک برنچ (شاخه) مستر ساخته می شود

که نقش شاخه اصلی است و هر کامیتی که انجام می دهیم نیز روی این شاخه اعمال میشود . و میتوانیم با دستور

git branch 

شاخه جدیدی مانند مستر ایجاد کرده و تغییرات را روی ان کامیت کنیم . با دستور چک اوت بین شاخه ها جا به جا شویم 

و در اخر در صورت نیاز میتوان این شاخه را با شاخه اصلی مرج کرد

-----------------------------------------------------------------------------------------------------------------
سوال 3 :
ابتدا باید در گیت هاب یک ریپازیتوری جدید ایجاد کرده . سپس با استفاده از دستور زیر وارد پوشه میشویم

cd empty

و دستورات زیر را وارد ترمینال میکنیم

git init

git add --all

git commit -m "this is a test for os5"

git remote add origin https://*****

git push -u origin master

و وارد گیت هاب شده و پروژه خود را رفرش میکنیم تا تغییرات اعمال شود

------------------------------------------------------------------------------------------------------------------

سوال 4:

با استفاده از دستور

uptime

میتوان مشخص کرد از لحظه روشن شدن سیستم و بوت شدن سیستم عامل چه مدت میگذرد

