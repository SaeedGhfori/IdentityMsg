پروژه باید حتما از نوع class libary باشه
طبق تصوی مود پروژه رو روی release بزارید 
![image](https://github.com/user-attachments/assets/81959029-9a32-4056-9e8c-fb3cfad7f02a)

بعد از پروژه Bulid بگیرید در سولوشن اکسپلورر و بعد به مسیر زیر بروید
~\IdentityMsg\IdentityMsg\bin\Release\net8.0
در این مسیر یک فایل dll با نام پروژه هست این dll رو به هر پروژه ای که دوست دارید اضافه کنید 

![image](https://github.com/user-attachments/assets/a3215857-24b4-4078-a099-50e830998f45)

طبق عکس بالا روی add اولی کلیک میکنیم و بعد در صفحه که باز میه از سمت چپ Browse میزنیم و بعد dll مربوطه رو انتخاب و اضافه میکنیم
![image](https://github.com/user-attachments/assets/d6740fed-d6ec-44d3-8f70-de42cdc16d7e)

حالا در کد نویسی در پروژه جدید خود اسم کلاسی که توی اون dll بود رو بنویسید مثال 
CustomIdentityError identityError= new CustomIdentityError();
و بعد ctrl + .  و using پروژه رو اضافه کنید و به همین راحتی از متد های کلاس لایبری استفاده کنید.
