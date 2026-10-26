# CAD & SURVEY Tools — public files

Public companion of **CAD & SURVEY Tools**, the AutoCAD / Civil 3D plugin for surveyors by Eng. Ali.
The plugin itself is not in this repo. This repo holds only:

| File | What it is |
|---|---|
| `links.txt` | Online copy of the plugin's links file. The tools read it in the background (`source =` line), so new video links, the latest version and the plans page reach every user without a new download. Keep the format: `key = value`, lines starting with `#` are notes. |
| `plans.html` | **Price & plans** page (PRO yearly, launch offer, payment methods, how to activate, contact). The only place where prices are written. |
| `index.html` | Short landing page: what the tools are, the 20 tools, links to Plans, Videos, PDF guide, Download. |
| `assets/` | Logo and favicon used by the pages. |
| `pay_zaincash.png` | *(upload it yourself)* the Zain Cash QR shown on `plans.html`. Until it is uploaded the page shows a neutral box. |

Live pages (after GitHub Pages is on):
- https://cadsurvey-ali.github.io/cadsurvey-public/
- https://cadsurvey-ali.github.io/cadsurvey-public/plans.html

## Edit the price page on github.com

1. Open `plans.html` in this repo on github.com.
2. Click the **pencil icon** (Edit this file).
3. Press `Ctrl + F` and search for **`OWNER:`** — every place you may change is marked with it
   (price in IQD, price in USD, offer price, seats left, show/hide the launch offer, WhatsApp number, Western Union receiver name).
4. Change only the text next to the mark. To hide the launch offer, add the word `hidden`:
   `<section class="offer" id="offer" hidden>`.
5. Click **Commit changes…** → **Commit changes**. The live page updates in about a minute.

The same way works for `links.txt` (for example `latest =`, `download =`, `playlist =`, `video.CLABEL =`)
and for `index.html` (the PDF guide and Download links: replace `#` with the link).

Never write a card number or a full account number in this repo — it is public.

## Switch on GitHub Pages (once)

1. Repo → **Settings** → **Pages**.
2. **Source:** *Deploy from a branch*.
3. **Branch:** `main`, folder **`/ (root)`** → **Save**.
4. After 1–2 minutes the address appears at the top of the Pages screen.

---

## بالعراقي

هذا المستودع العام مال **CAD & SURVEY Tools**. البرنامج نفسه مو هنا، بس:

- **`links.txt`**: نسخة الروابط اللي الأدوات تقراها من النت (فيديوهات، آخر نسخة، صفحة الأسعار). لا تغيّر الشكل: `key = value`، والسطر اللي يبدي بـ `#` ملاحظة.
- **`plans.html`**: صفحة الأسعار والاشتراك. الأسعار تنكتب هنا بس، مو بالأداة ولا بالدليل.
- **`index.html`**: صفحة تعريف قصيرة بالأدوات.
- **`assets/`**: اللوگو والأيقونة.
- **`pay_zaincash.png`**: صورة QR مال زين كاش، ارفعها انت بنفس الاسم.

### شلون تعدّل الأسعار من github.com

1. افتح `plans.html` بالموقع.
2. اضغط **القلم** (Edit).
3. اضغط `Ctrl + F` ودوّر على **`OWNER:`**، كل مكان تبدّله مأشّر بيها: السعر بالدينار، السعر بالدولار، سعر العرض، المقاعد الباقية، إظهار/إخفاء العرض، رقم الواتساب، اسمك للويسترن يونيون (مثل الجواز بالضبط).
4. بدّل بس الكلام اللي يم العلامة. حتى تخفي عرض الإطلاق ضيف كلمة `hidden` مثل: `<section class="offer" id="offer" hidden>`.
5. اضغط **Commit changes** مرتين. الصفحة تتحدث خلال دقيقة تقريباً.

لا تكتب أبداً رقم بطاقة أو رقم حساب كامل هنا، المستودع عام ويشوفه الكل.

### شلون تشغّل GitHub Pages (مرة وحدة)

**Settings** ← **Pages** ← Source: **Deploy from a branch** ← Branch: **main** والمجلد **/ (root)** ← **Save**. بعد دقيقة أو دقيقتين يطلع رابط الصفحة فوق.

By Eng. Ali · eng.alicadsurvey@gmail.com · [YouTube @Eng.alicadsurvey](https://www.youtube.com/@Eng.alicadsurvey)
