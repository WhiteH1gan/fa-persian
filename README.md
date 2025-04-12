<div lang="fa" dir="rtl">

سالیدیتی
========

| توجه داشته باشید | 
| ------------- | 
| شاید شما جدیدترین نسخه این اسناد را نمی خوانید. این نسخه 0.8.29 است.  |


سالیدیتی  یک زبان شیء گرا و سطح بالا  برای پیاده سازی قراردادهای هوشمند  می‌باشد. قرارداد‌های هوشمند، برنامه‌هایی هستند که رفتار حساب‌ها  در داخل حالت اتریوم  را کنترل می‌کنند.

سالیدیتی یک زبان آکلادی(curly-bracket language) می‌باشد که از زبان‌هایی مانند سی پلاس پلاس، پایتون و جاوا اسکریپت تأثیر گرفته و برای هدف قراردادن EVM  یا ماشینِ مجازیِ اتریوم  طراحی شده‌است.

سالیدیتی از نوع استاتیک   می‌باشد. از ویژگی‌های ارث بری، کتابخانه‌ها  و انواع نوع‌های پیچیده تعریف شده توسط کاربر  پشتیبانی می‌کند.

با سالیدیتی می‌توانید قراردادهایی را برای کاربردهایی از قبیل رأی‌گیری، سرمایه گذاری جمعی، مزایده کور  و کیف پول‌ با امضای چندگانه  استفاده کنید.

هنگام استقرار  قرارداد‌ها، باید از آخرین نسخه سالیدیتی منتشر شده استفاده کنید. به این دلیل که تغییرات جدید، ویژگی‌های جدید  و رفع اشکال ‌ها  به طور منظم معرفی می‌شوند. ما در حال حاضر از نسخه 0.X برای نشان دادن این تغییرات سریع استفاده می‌کنیم.


| هشدار  | 
| ------------- | 
| سالیدیتی به تازگی نسخه 0.8.X را منتشر کرده که تغییرات جدید را معرفی می‌کند. حتماً لیست کامل را مطالعه کنید.  |


ایده‌های بهبود سالیدیتی یا این مستند همیشه مورد استقبال قرار میگیرد، برای جزئیات بیشتر راهنمای همکاری را مطالعه کنید.

|راهنمایی|

|با کلیک بر روی منوی نسخه ها در گوشه سمت راست پایین و انتخاب فرمت دانلود ترجیحی، می توانید این اسناد را به شکل صفحات وب, پی دی اف و کتاب الکترونیکی دریافت کنید. |

# شروع 

1.	درک مبانی قراردادهای هوشمند

اگر با مفهوم قراردادهای هوشمند آشنا هستید، به شما توصیه می‌کنیم که با جستجوی بخش "معرفی قراردادهای هوشمند" شروع به کار کنید، که شامل موارد زیر است:
* 	یک مثال ساده از قرارداد هوشمند که با سالیدیتی نوشته شده‌است.
* 	مبانی بلاکچین.
* 	ماشین مجازی اتریوم.

2.	آشنایی با سالیدیتی

هنگامی که با مبانی اولیه آشنا شدید، توصیه می‌کنیم برای درک مفاهیم اصلی زبان، بخش‌های "سالیدیتی با مثال" و "شرح زبان" را بخوانید.

3.	نصب کامپایلر سالیدیتی

روش های مختلفی برای نصب کامپایلر سالیدیتی وجود دارد، به سادگی گزینه مورد نظر خود را انتخاب کنید و مراحل ذکر شده در صفحه نصب را دنبال کنید.

| راهنمایی  | 
| ------------- | 
| می‌توانید نمونه‌های کد را به شکل مستقیم در مرورگر خود با  ویرایشگر کد ریمیکس  امتحان کنید. ریمیکس یک ویرایشگر کد مبتنی بر مرورگر وب است که به شما امکان می‌دهد، بدون نیاز به نصب سالیدیتی به صورت محلی، قراردادهای هوشمند سالیدیتی را بنویسید، دیپلوی و مدیریت کنید.  |

| هشدار | 
| ------------- | 
| نرم افزار به عنوان نوشته‌ی انسان، می‌تواند دارای اشکالاتی باشد. هنگام نوشتن قراردادهای هوشمند، باید بهترین شیوه‌های توسعه نرم افزار را دنبال کنید. شیوه‌های توسعه نرم افزار شامل بازبینی، آزمایش، حسابرسی  و اثبات صحتِ  کد می‌باشد. کاربران قرارداد هوشمند گاهی اوقات به خود کد نسبت به نویسندگان آن‌ها اطمینان بیشتری دارند. بلاکچین‌ها و قراردادهای هوشمند مسائل منحصر به فرد خود را دارند، که باید مراقب آنها باشید. بنابراین قبل از کار بر روی تولید کد، حتماً قسمت ملاحظات امنیتی را مطالعه کنید.  |

4.	یادگیری بیشتر

اگر می‌خواهید در مورد ساخت برنامه‌های غیرمتمرکز در اتریوم اطلاعات بیشتری کسب کنید، منابع توسعه دهنده اتریوم می‌توانند به شما در تهیه مستندِ عمومیِ بیشتر در مورد اتریوم و انتخاب گسترده‌ای از آموزش‌ها، ابزارها و چارچوب‌های توسعه (development frameworks) کمک کنند.
 اگر پرسشی دارید، می‌توانید جواب‌ها را جستجو کنید یا از طریق Ethereum StackExchange یا کانال Gitter ما بپرسید.

# ترجمه‌ها

داوطلبان جامعه سالیدیتی به ترجمه این مستند به چندین زبان کمک می‌کنند. این‌ سندها سطوح مختلفی از کامل و بروز بودن را دارند. نسخه انگلیسی به عنوان مرجع می‌باشد.
با کلیک بر روی منوی نسخه ها در گوشه سمت راست پایین و انتخاب زبان مورد نظر, میتوانید بین زبان ها جا به جا شوید.

* 	چینی
* 	فرانسوی
* 	اندونزیایی
*  ژاپنی
* 	کره‌ای
* 	فارسی
* 	روسی
* 	اسپانیایی
* 	ترکی


# فهرست

فهرست کلمات کلیدی، صفحه جستجو

## مبانی

* [مقدمه‌ای بر قرارد‌اد‌های هوشمند](https://github.com/solidity-docs/fa-persian/wiki/%D9%85%D9%82%D8%AF%D9%85%D9%87%E2%80%8C%D8%A7%DB%8C-%D8%A8%D8%B1-%D9%82%D8%B1%D8%A7%D8%AF%E2%80%8C%D9%87%D8%A7%DB%8C-%D9%87%D9%88%D8%B4%D9%85%D9%86%D8%AF)
   * [یک قرارداد هوشمند ساده](https://github.com/solidity-docs/fa-persian/wiki/%D9%85%D9%82%D8%AF%D9%85%D9%87%E2%80%8C%D8%A7%DB%8C-%D8%A8%D8%B1-%D9%82%D8%B1%D8%A7%D8%AF%E2%80%8C%D9%87%D8%A7%DB%8C-%D9%87%D9%88%D8%B4%D9%85%D9%86%D8%AF#%DB%8C%DA%A9-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF-%D9%87%D9%88%D8%B4%D9%85%D9%86%D8%AF-%D8%B3%D8%A7%D8%AF%D9%87)
   * [مبانی بلاکچین](https://github.com/solidity-docs/fa-persian/wiki/%D9%85%D9%82%D8%AF%D9%85%D9%87%E2%80%8C%D8%A7%DB%8C-%D8%A8%D8%B1-%D9%82%D8%B1%D8%A7%D8%AF%E2%80%8C%D9%87%D8%A7%DB%8C-%D9%87%D9%88%D8%B4%D9%85%D9%86%D8%AF#%D9%85%D8%A8%D8%A7%D9%86%DB%8C-%D8%A8%D9%84%D8%A7%DA%A9%DA%86%DB%8C%D9%86)
   * [ماشین مجازی اتریوم](https://github.com/solidity-docs/fa-persian/wiki/%D9%85%D9%82%D8%AF%D9%85%D9%87%E2%80%8C%D8%A7%DB%8C-%D8%A8%D8%B1-%D9%82%D8%B1%D8%A7%D8%AF%E2%80%8C%D9%87%D8%A7%DB%8C-%D9%87%D9%88%D8%B4%D9%85%D9%86%D8%AF#%D9%85%D8%A7%D8%B4%DB%8C%D9%86-%D9%85%D8%AC%D8%A7%D8%B2%DB%8C-%D8%A7%D8%AA%D8%B1%DB%8C%D9%88%D9%85)
* [سالیدیتی با مثال](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C-%D8%A8%D8%A7-%D9%85%D8%AB%D8%A7%D9%84)
   * [رای گیری](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C-%D8%A8%D8%A7-%D9%85%D8%AB%D8%A7%D9%84#%D8%B1%D8%A7%DB%8C-%DA%AF%DB%8C%D8%B1%DB%8C)
   * [مزایده کور](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C-%D8%A8%D8%A7-%D9%85%D8%AB%D8%A7%D9%84#%D9%85%D8%B2%D8%A7%DB%8C%D8%AF%D9%87-%DA%A9%D9%88%D8%B1)
   * [خرید امن از راه دور](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C-%D8%A8%D8%A7-%D9%85%D8%AB%D8%A7%D9%84#%D8%AE%D8%B1%DB%8C%D8%AF-%D8%A7%D9%85%D9%86-%D8%A7%D8%B2-%D8%B1%D8%A7%D9%87-%D8%AF%D9%88%D8%B1)
   * [کانال پرداخت خرد](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C-%D8%A8%D8%A7-%D9%85%D8%AB%D8%A7%D9%84#%DA%A9%D8%A7%D9%86%D8%A7%D9%84-%D9%BE%D8%B1%D8%AF%D8%A7%D8%AE%D8%AA-%D8%AE%D8%B1%D8%AF)
   * [قراردادهای ماژولی](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C-%D8%A8%D8%A7-%D9%85%D8%AB%D8%A7%D9%84#%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF%D9%87%D8%A7%DB%8C-%D9%85%D8%A7%DA%98%D9%88%D9%84%DB%8C)

* [نصب کامپایلر سالیدیتی](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C)
   * [نسخه بندی](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D9%86%D8%B3%D8%AE%D9%87-%D8%A8%D9%86%D8%AF%DB%8C)
   * [ریمیکس](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%B1%DB%8C%D9%85%DB%8C%DA%A9%D8%B3)
   * [npm / Node.js](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#npm--nodejs)
   * [داکر](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%AF%D8%A7%DA%A9%D8%B1)
   * [بسته‌های لینوکس](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%A8%D8%B3%D8%AA%D9%87%D9%87%D8%A7%DB%8C-%D9%84%DB%8C%D9%86%D9%88%DA%A9%D8%B3)
   * [بسته‌های مک‌او اس](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%A8%D8%B3%D8%AA%D9%87%D9%87%D8%A7%DB%8C-%D9%85%DA%A9%D8%A7%D9%88-%D8%A7%D8%B3) 
   * [باینری‌های استاتیک](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%A8%D8%A7%DB%8C%D9%86%D8%B1%DB%8C%D9%87%D8%A7%DB%8C-%D8%A7%D8%B3%D8%AA%D8%A7%D8%AA%DB%8C%DA%A9)
   * [نسخه از منبع](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D9%86%D8%B3%D8%AE%D9%87-%D8%A7%D8%B2-%D9%85%D9%86%D8%A8%D8%B9)
   * [گزینه‌های CMake](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%DA%AF%D8%B2%DB%8C%D9%86%D9%87%D9%87%D8%A7%DB%8C-cmake)
   * [رشته نسخه با جزئیات](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%B1%D8%B4%D8%AA%D9%87-%D9%86%D8%B3%D8%AE%D9%87--%D8%A8%D8%A7-%D8%AC%D8%B2%D8%A6%DB%8C%D8%A7%D8%AA)
   * [اطلاعات مهم در مورد نسخه بندی](https://github.com/solidity-docs/fa-persian/wiki/%D9%86%D8%B5%D8%A8-%DA%A9%D8%A7%D9%85%D9%BE%D8%A7%DB%8C%D9%84%D8%B1-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%A7%D8%B7%D9%84%D8%A7%D8%B9%D8%A7%D8%AA-%D9%85%D9%87%D9%85-%D8%AF%D8%B1-%D9%85%D9%88%D8%B1%D8%AF-%D9%86%D8%B3%D8%AE%D9%87-%D8%A8%D9%86%D8%AF%DB%8C)

توضیحات زبان

* [چیدمان یک فایل منبع سالیدیتی](https://github.com/solidity-docs/fa-persian/wiki/%DA%86%DB%8C%D8%AF%D9%85%D8%A7%D9%86-%DB%8C%DA%A9-%D9%81%D8%A7%DB%8C%D9%84-%D9%85%D9%86%D8%A8%D8%B9-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C)
   * [مشخص کننده‌ی لایسنس  SPDX](https://github.com/solidity-docs/fa-persian/wiki/%DA%86%DB%8C%D8%AF%D9%85%D8%A7%D9%86-%DB%8C%DA%A9-%D9%81%D8%A7%DB%8C%D9%84-%D9%85%D9%86%D8%A8%D8%B9-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D9%85%D8%B4%D8%AE%D8%B5-%DA%A9%D9%86%D9%86%D8%AF%D9%87%DB%8C-%D9%84%D8%A7%DB%8C%D8%B3%D9%86%D8%B3--spdx)
   * [پراگماها](https://github.com/solidity-docs/fa-persian/wiki/%DA%86%DB%8C%D8%AF%D9%85%D8%A7%D9%86-%DB%8C%DA%A9-%D9%81%D8%A7%DB%8C%D9%84-%D9%85%D9%86%D8%A8%D8%B9-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D9%BE%D8%B1%D8%A7%DA%AF%D9%85%D8%A7%D9%87%D8%A7)
   * [ایمپورت کردن سایر فایل‌های منبع](https://github.com/solidity-docs/fa-persian/wiki/%DA%86%DB%8C%D8%AF%D9%85%D8%A7%D9%86-%DB%8C%DA%A9-%D9%81%D8%A7%DB%8C%D9%84-%D9%85%D9%86%D8%A8%D8%B9-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%D8%A7%DB%8C%D9%85%D9%BE%D9%88%D8%B1%D8%AA-%DA%A9%D8%B1%D8%AF%D9%86-%D8%B3%D8%A7%DB%8C%D8%B1-%D9%81%D8%A7%DB%8C%D9%84%D9%87%D8%A7%DB%8C-%D9%85%D9%86%D8%A8%D8%B9)
   * [کامنت‌ها](https://github.com/solidity-docs/fa-persian/wiki/%DA%86%DB%8C%D8%AF%D9%85%D8%A7%D9%86-%DB%8C%DA%A9-%D9%81%D8%A7%DB%8C%D9%84-%D9%85%D9%86%D8%A8%D8%B9-%D8%B3%D8%A7%D9%84%DB%8C%D8%AF%DB%8C%D8%AA%DB%8C#%DA%A9%D8%A7%D9%85%D9%86%D8%AA%D9%87%D8%A7)
* [ساختار قرارداد](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF)
   * [متغیرهای حالت](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D9%85%D8%AA%D8%BA%DB%8C%D8%B1%D9%87%D8%A7%DB%8C-%D8%AD%D8%A7%D9%84%D8%AA)
   * [توابع](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D8%AA%D9%88%D8%A7%D8%A8%D8%B9)
   * [توابع اصلاح کننده](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D8%AA%D9%88%D8%A7%D8%A8%D8%B9-%D8%A7%D8%B5%D9%84%D8%A7%D8%AD-%DA%A9%D9%86%D9%86%D8%AF%D9%87)
   * [خطاها](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D8%AE%D8%B7%D8%A7%D9%87%D8%A7)
   * [رویداد ها](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D8%B1%D9%88%DB%8C%D8%AF%D8%A7%D8%AF%D9%87%D8%A7)
   * [انواع Struct](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D8%A7%D9%86%D9%88%D8%A7%D8%B9-struct)
   * [انواع Enum](https://github.com/solidity-docs/fa-persian/wiki/%D8%B3%D8%A7%D8%AE%D8%AA%D8%A7%D8%B1-%D9%82%D8%B1%D8%A7%D8%B1%D8%AF%D8%A7%D8%AF#%D8%A7%D9%86%D9%88%D8%A7%D8%B9-enum)
* [انواع](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9)
   * [انواع مقدار](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9#%D8%A7%D9%86%D9%88%D8%A7%D8%B9-%D9%85%D9%82%D8%AF%D8%A7%D8%B1)
   * [انواع مرجع](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9#%D8%A7%D9%86%D9%88%D8%A7%D8%B9-%D9%85%D8%B1%D8%AC%D8%B9)
   * [انواع نگاشت‌ها](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9#%D8%A7%D9%86%D9%88%D8%A7%D8%B9--%D9%86%DA%AF%D8%A7%D8%B4%D8%AA%D9%87%D8%A7)
   * [اپراتورهایی شامل LValues](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9#%D8%A7%D9%BE%D8%B1%D8%A7%D8%AA%D9%88%D8%B1%D9%87%D8%A7%DB%8C%DB%8C-%D8%B4%D8%A7%D9%85%D9%84--lvalues)
   * [تبدیل بین نوع‌های اصلی](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9#%D8%AA%D8%A8%D8%AF%DB%8C%D9%84-%D8%A8%DB%8C%D9%86-%D9%86%D9%88%D8%B9%D9%87%D8%A7%DB%8C-%D8%A7%D8%B5%D9%84%DB%8C)
   * [تبدیل بین لیترال‌ها و نوع‌های اصلی](https://github.com/solidity-docs/fa-persian/wiki/%D8%A7%D9%86%D9%88%D8%A7%D8%B9#%D8%AA%D8%A8%D8%AF%DB%8C%D9%84-%D8%A8%DB%8C%D9%86-%D9%84%DB%8C%D8%AA%D8%B1%D8%A7%D9%84%D9%87%D8%A7-%D9%88-%D9%86%D9%88%D8%B9%D9%87%D8%A7%DB%8C-%D8%A7%D8%B5%D9%84%DB%8C)
* Units and Globally Available Variables
   * Ether Units
   * Time Units
   * Special Variables and Functions
   * Reserved Keywords

* Expressions and Control Structures
   * Control Structures
   * Function Calls
   * Creating Contracts via new
   * Order of Evaluation of Expressions
   * Assignment
   * Scoping and Declarations
   * Checked or Unchecked Arithmetic
   * Error handling: Assert, Require, Revert and Exceptions

* Contracts
   * Creating Contracts
   * Visibility and Getters
   * Function Modifiers
   * Transient Storage
   * Composability of Smart Contracts and the Caveats of Transient Storage
   * Constant and Immutable State Variables
   * Custom Storage Layout
   * Functions
   * Events
   * Errors and the Revert Statement
   * Inheritance
   * Abstract Contracts
   * Interfaces
   * Libraries
   * Using For

* Inline Assembly
   * Example
   * Access to External Variables, Functions and Libraries
   * Things to Avoid
   * Conventions in Solidity
   * Advanced Safe Use of Memory

* Cheatsheet
   * Order of Precedence of Operators
   * ABI Encoding and Decoding Functions
   * Members of `bytes` and `string`
   * Members of address
   * Block and Transaction Properties
   * Validations and Assertions
   * Mathematical and Cryptographic Functions
   * Contract-related
   * Type Information
   * Function Visibility Specifiers
   * Modifiers

* Language Grammar

کامپایلر 

* Using the Compiler
   * Using the Commandline Compiler
   * Setting the EVM Version to Target
   * Compiler Input and Output JSON Description
  
* Analysing the Compiler Output
* Solidity IR-based Codegen Changes
   * Semantic Only Changes
   * Internals


Internals

* Layout of State Variables in Storage
   * Mappings and Dynamic Arrays
   * JSON Output
* Layout in Memory
   * Differences to Layout in Storage
* Layout of Call Data
* Cleaning Up Variables
* Source Mappings
* The Optimizer
   * Benefits of Optimizing Solidity Code
   * Differences between Optimized and Non-Optimized Code
   * Optimizer Parameter Runs
   * Opcode-Based Optimizer Module
   * Yul-Based Optimizer Module
   * Codegen-Based Optimizer Module
* Contract Metadata
   * Encoding of the Metadata Hash in the Bytecode
   * Usage for Automatic Interface Generation and NatSpec
   * Usage for Source Code Verification
* Contract ABI Specification
   * Basic Design
   * Function Selector
   * Argument Encoding
   * Types
   * Design Criteria for the Encoding
   * Formal Specification of the Encoding
   * Function Selector and Argument Encoding
   * Examples
   * Use of Dynamic Types
   * Events
   * Errors
   * JSON
   * Strict Encoding Mode
   * Non-standard Packed Mode
   * Encoding of Indexed Event Parameters

توصیه ها

* Security Considerations
   *Pitfalls
   *Recommendations
* List of Known Bugs
* Solidity v0.5.0 Breaking Changes
   * Semantic Only Changes
   * Semantic and Syntactic Changes
   * Explicitness Requirements
   * Deprecated Elements
   * Interoperability With Older Contracts
   * Example
* Solidity v0.6.0 Breaking Changes
   * Changes the Compiler Might not Warn About
   * Explicitness Requirements
   * Semantic and Syntactic Changes
   * New Features
   * Interface Changes
   * How to update your code
* Solidity v0.7.0 Breaking Changes
   * Silent Changes of the Semantics
   * Changes to the Syntax
   * Removal of Unused or Unsafe Features
   * Interface Changes
   * How to update your code
* Solidity v0.8.0 Breaking Changes
   * Silent Changes of the Semantics
   * New Restrictions
   * Interface Changes
   * How to update your code

مطالب کمکی

* NatSpec Format
   * Documentation Example
   * Tags
Documentation Output
* SMTChecker and Formal Verification
   * Tutorial
   * SMTChecker Options and Tuning
   * Abstraction and False Positives
   * Real World Assumptions
* Yul
   * Motivation and High-level Description
   * Simple Example
   * Stand-Alone Usage
   * Informal Description of Yul
   * Specification of Yul
   * Specification of Yul Object
   * Yul Optimizer
   * Complete ERC20 Example
* Import Path Resolution
   * Virtual Filesystem
   * Imports
   * Base Path and Include Paths
   * Allowed Paths
   * Import Remapping
   * Using URLs in imports

منابع

* Style Guide
   * Introduction
   * Code Layout
   * Order of Layout
   * Naming Conventions
   * NatSpec
* Common Patterns
   * Withdrawal from Contracts
   * Restricting Access
   * State Machine
* Resources
   * General Resources
   * Integrated (Ethereum) Development Environments
   * Editor Integrations
   * Solidity Tools
   * Third-Party Solidity Parsers and Grammars
* Contributing
   * Team Calls
   * How to Report Issues
   * Workflow for Pull Requests
   * Running the Compiler Tests
   * Running the Fuzzer via AFL
   * Whiskers
   * Documentation Style Guide
   * Solidity Language Design
* Language Influences
* Solidity Brand Guide
   * The Solidity Brand
   * Solidity Brand Name
   * Solidity Logo License
   * Solidity Logo Guidelines
   * Credits

</div>


