<h1 dir="rtl">شیوه‌ نگارش</h1>

<p dir="rtl">
برای حفظ یکپارچگی ترجمه در تمام صفحات و همچنین میان سایر زبان‌ها، لطفا قوانین زیر را مدنظر داشته‌باشید.
</p>

<h2 dir="rtl">شناسه عنوان‌ها</h2>

<p dir="rtl">هر عنوانی یک شناسه منحصربه‌فرد دارد، مانند زیر:</p>

```md
## Try React {#try-react}
```
<p dir="rtl">از ترجمه شناسه‌ها <b>بپرهیزید</b>! از آن‌ها برای هدایت به بخش‌های مختلف یک صفحه استفاده می‌شود. به خصوص اگر کاربر از یک لینک خارجی به یک بخش مورد نظر از صفحه هدایت شده‌باشد، این قابلیت از کار خواهد افتاد.</p>


<p dir="rtl">✅ صحیح:</p>

```md
## ری‌اکت را امتحان کنید {#try-react}
```

<p dir="rtl">❌ غلط:</p>

```md
## ری‌اکت را امتحان کنید {#react-ra-emtehan-konid}
```
<p dir="rtl">ترجمه باعث از کار افتادن لینک بالا شده‌است.</p>


<h2 dir="rtl">متن در کد</h2>
<p dir="rtl">
فقط کامنت‌های یک کد را ترجمه کنید. از ترجمه دیگر بخش‌های کد بپرهیزید.
</p>

<p dir="rtl">مثال:</p>

```js
// Example
const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

<p dir="rtl">✅ صحیح:</p>

```js
// مثال
const element = <h1>Hello, world</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

<p dir="rtl">❌ غلط:</p>

```js
// مثال
const element = <h1>سلام، دنیا</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

<p dir="rtl">❌ غلط:</p>

```js
// مثال
const element = <h1>سلام، دنیا</h1>;
// "root" به شناسه یک تگ اشاره دارد
// نباید آن را ترجمه کرد!
ReactDOM.render(element, document.getElementById('ریشه'));
```

<p dir="rtl">❌ کاملا غلط:</p>

```js
// مثال
const eleman = <h1>سلام، دنیا</h1>;
ReactDOM.render(eleman, sanad.yaftanElemeanBaId('ریشه'));

```
<h2 dir="rtl">لینک‌های خارجی</h2>
<p dir="rtl">
اگر یک لینک خارجی به یک مقاله از منابعی مانند <a href="https://developer.mozilla.org/fa/" taget="_blank">شبکه توسعه‌دهنگان موزیلا (MDN)</a> و <a href="https://en.wikipedia.org/wiki/Main_Page" taget="_blank">ویکی‌پدیا (Wikipedia)</a>  ارجاع داده‌  شده‌است، در صورتی که نسخه فارسی آن مقاله موجود و از کیفیت مناسبی برخوردار است، به نسخه فارسی ارجاع داده‌شود.
</p>

<p dir="rtl">مثال:</p>

<p>
A stateful component inherits <code>Component</code> <a href="https://en.wikipedia.org/wiki/Class_(computer_programming)" target="_blank">class</a>.
</p>



<p dir="rtl">✅ صحیح:</p>
<p dir="rtl">
یک کامپوننت دارای state از <a href="https://fa.wikipedia.org/wiki/%DA%A9%D9%84%D8%A7%D8%B3_(%D8%A8%D8%B1%D9%86%D8%A7%D9%85%D9%87%E2%80%8C%D9%86%D9%88%DB%8C%D8%B3%DB%8C)" target="_blank">کلاس</a> <code>Component</code> ارث می‌برد.
</p>
<br />
<p dir="rtl">
برای لینک‌هایی که معادل فارسی ندارند مثل Stack Overflow و ویدیو‌های YouTube، از همان لینک انگلیسی استفاده‌شود.
</p>

<h2 dir="rtl">زبان فارسی</h2>
<p dir="rtl">
هدف تمام مشارکت‌کنندگان تولید محتوای فارسی با بهترین کیفیت ممکن است تا به منبعی قابل استفاده برای همگان تبدیل شود. قطعا دستیابی به این هدف بدون رعایت شیوه‌ نگارش استاندارد فارسی میسر نخواهد‌شد. اگر نیاز به یک یادآوری داشتید، مقاله <a href="https://virastaran.net/a/v/m/e/eh/148/" target="_blank">شیوه‌نامۀ «ویراستاران» برای نگارش در وب</a> منبع مناسبی است.
</p>
<p dir="rtl">
اگر فکر می‌کنید چیزی فراموش شده‌است یا نیاز به تصحیح دارد، حتما نظر خود را با ما درمیان بگذارید.
</p>