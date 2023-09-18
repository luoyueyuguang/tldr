# export

> دستور تغییر متغییرهای محلی سیستم موجود برای پروسه های جدید
> اطلاعات بیشتر: <https://www.gnu.org/software/bash/manual/bash.html#index-export>.

- ایجاد و تعیین مقدار یک متغییر جدید

`export {{متغییر}}={{مقدار}}`

- حذف یک متغییر سیستمی

`export -n {{متغییر}}`

- افزودن یک تابع شل به متغییر سیستمی

`export -f {{نام تابع}}`

- افزودن یک مسیر به متغییر $PATH

`export PATH=$PATH:{{مسیر/برای/افزودن}}`