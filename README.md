مراحل انجام پروژه 
یک : ساخت کلاس های مستطیل و مربع
دو: افزودن ویژگی های مورد نیاز مانند طول و عرض
سه: نوشتن توابع مورد نیاز مانند محاسبه مساحت
چهار: افزودن کلاس تست 
شش: افزودن توابع در کلاس تست
هفت: تست توابع با مقادیر متفاوت



اصول solid
اصول SOLID که قصد رفع کردن این مشکلات و بسیاری مسائل گوناگون را دارد عبارت اند از:

    Single Responsibility Principle
    Open-Closed Principle
    Liskov Substitution Principle
    Interface Segregation Principle
    Dependency Inversion Principle

با کنار هم گذاشتن حرف اول هر کدام از این اصول کلمه ی SOLID ایجاد می شود. با در نظر گرفتن این پنج اصل و پیاده سازی آنها در برنامه های خود می توانید به یک طراحی شی گرا پاک و درست دست پیدا کنید.



S  مخفف Single responsibility principle یا SRP 
به معنی اینکه هر کلاس بایستی فقط یک کار انجام دهد نه بیشتر

O  مخفف Open/closed principle یا OCP
به معنی اینکه کلاس ها جوری نوشته بشن که قابل گسترش باشند اما نیاز به تغییر نداشته باشند.

L مخفف Liskov Substitution Principle یا LSP
به مفهوم اینکه هر کلاسی که از کلاس دیگر ارث بری میکند هرگز نباید رفتار کلاس والد را تغییر دهد.

I  مخفف Interface Segregation Principle با ISP
به مفهوم اینکه چند اینترفیس کوچک و خورد شده همیشه بهتر از یک اینترفیس کلی و بزرگ است.

D  مخفف Dependency inversion principle یا DIP 
به معنی اینکه از اینترفیس ها به خوبی استفاده کن!



سوال دوم :
این اصول در تمام مراحل تولید نرم افزار(تحلیل، طراحی، پیاده سازی،تست و استقرار) استفاده میشوند 
و کاربرد بیشتری در پیاده سازی دارند.

سوال سوم:
خیر تناقضی ندارند و هر دو از بهترین روشها هستند و هرکدام مزایای مربوط به خودش را دارد و گاها
تست هم در ابتدا و هم در انتها انجام میشود.

سوال چهارم:
توابع set get  را پیاده سازی نمیکردیم و در طراحی از این توابع استفاده نمیشد.
