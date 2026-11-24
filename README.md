# OsLatex

**A LaTeX editor for Windows that compiles with a real LaTeX engine on your own PC, with live collaboration.**

**[Download OsLatex.exe (latest version)](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)**

> OsLatex is a LaTeX editor for Windows. It compiles with a real LaTeX engine on your machine, lets you work on the same project live with friends, and keeps all your files local—no compile time limits, no subscriptions, and full Arabic support.

<br>

**محرر LaTeX لنظام ويندوز يكمبايل باستخدام محرك LaTeX حقيقي على جهازك الشخصي، مع ميزة العمل الجماعي المباشر.**

**[تحميل OsLatex.exe (أحدث إصدار)](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)**

> **بالعربي:** OsLatex برنامج لكتابة LaTeX على ويندوز. يكمبايل بمحرك LaTeX حقيقي على جهازك، وتقدر تشتغل فيه مع خوياك على نفس المشروع لايف. وكل ملفاتك تظل عندك، بدون حدود وقت كمبايل، وبدون اشتراك. ويدعم العربي بالكامل.

---

## Why OsLatex? / ليش OsLatex؟

### English
| | OsLatex | Online editors |
|---|---|---|
| **Where your files are** | On your PC | On someone's server |
| **Compile time limit** | None, even for a 100+ page thesis | Free plans time out on big documents |
| **Works offline** | Yes, after the one-time setup | No |
| **Live collaboration** | Yes, free, through your own PC | Often a paid plan |
| **Arabic** | Built in (XeLaTeX + Amiri, right-to-left lines) | Depends on setup |
| **Price** | Free | Free plans with limits |

* **Your files stay with you:** Projects are on your machine, not on someone's server.
* **No compile time limits:** Even if your graduation project is over 100 pages.
* **Works offline:** After the one-time setup.
* **Free live collaboration:** Friends join your project from their homes.
* **Full Arabic support** out of the box.

### بالعربي
| | OsLatex | المحررات السحابية |
|---|---|---|
| **مكان ملفاتك** | على جهازك الشخصي | على سيرفرات شخص آخر |
| **حد وقت الكمبايل** | لا يوجد حد، حتى لرسالة تتجاوز 100 صفحة | الخطط المجانية تنتهي مهلتها في المستندات الكبيرة |
| **العمل بدون إنترنت** | نعم، بعد التثبيت الأولي لمرة واحدة | لا |
| **العمل الجماعي المباشر** | نعم، مجاناً، من خلال جهازك | غالباً تتطلب خطة مدفوعة |
| **اللغة العربية** | مدعومة من البداية (XeLaTeX + خط أميري، مع دعم RTL) | تعتمد على الإعدادات |
| **السعر** | مجاني | خطط مجانية بحدود |

* **ملفاتك عندك:** المشاريع على جهازك مو على سيرفر أحد.
* **بدون حد وقت للكمبايل:** حتى لو مشروع التخرج حقك فوق 100 صفحة.
* **يشتغل بدون نت:** بعد ما تركّب المكونات مرة وحدة.
* **شغل جماعي لايف ببلاش:** خوياك يدخلون على مشروعك من بيوتهم.
* **العربي مدعوم من البداية.**

---

## Features / المزايا

### Writing / الكتابة

**English:**
- **A full LaTeX editor:** syntax colours, autocomplete for commands, `\ref` labels, `\cite` keys, file paths and packages, code folding, search & replace, and multiple cursors.
- **Formatting toolbar:** headings, bold/italic, math, a symbol palette (Greek, arrows, ℝ…), lists, tables, figures, links and citations.
- **Paste a screenshot (Ctrl+V)** into the editor: it's saved in `figures/` and the figure code is written for you.
- **Add a reference from a DOI or arXiv ID:** OsLatex fetches it, adds it to your `.bib` with a clean key such as `Vaswani_2017`, and inserts `\cite{…}`.
- **Outline** of the whole document and **search across all files**.
- **Arabic:** right-to-left lines and Arabic templates, and the right engine is picked automatically.

**بالعربي:**
- **محرر LaTeX متكامل:** ألوان للصيغة البرمجية، إكمال تلقائي للأوامر، وسوم `\ref`، مفاتيح `\cite`، مسارات الملفات والحزم، طي الكود، بحث واستبدال، ومؤشرات متعددة.
- **شريط أدوات للتنسيق:** العناوين، غامق/مائل، رياضيات، لوحة رموز، قوائم، جداول، أشكال، روابط واستشهادات.
- **لصق لقطة شاشة (Ctrl+V):** يتم حفظها في مجلد `figures/` ويتم كتابة كود الشكل تلقائياً لك.
- **إضافة مرجع من DOI أو arXiv ID:** يجلب المرجع، ويضيفه لملف `.bib` بمفتاح نظيف، ويدرج أمر `\cite{…}` في مكان المؤشر.
- **المخطط التفصيلي (Outline)** للمستند بأكمله و**البحث في جميع الملفات**.
- **اللغة العربية:** سطور من اليمين إلى اليسار (RTL) وقوالب عربية، ويتم اختيار محرك الكمبايل المناسب تلقائياً.

### Compiling / الكمبايل

**English:**
- **Real LaTeX engines:** pdfLaTeX, XeLaTeX, LuaLaTeX, BibTeX and Biber. The PDF is the real one, not an approximation.
- **Auto engine:** XeLaTeX for Arabic and `fontspec`, LuaLaTeX when needed, otherwise pdfLaTeX. Runs as many passes as needed.
- **Clear errors:** each problem with its file and line (click to jump there) and a plain-language hint.
- **Missing package?** One click installs it automatically.
- **PDF preview** with zoom, search and links. **Double-click the PDF** to jump to that line in the source.
- **Safe:** compiles run in a sandbox that can't read your other files or use the internet.

**بالعربي:**
- **محركات LaTeX حقيقية:** pdfLaTeX، XeLaTeX، LuaLaTeX، BibTeX و Biber. ملف الـ PDF الناتج حقيقي وليس تقديرياً.
- **محرك تلقائي:** يستخدم XeLaTeX للعربية، و LuaLaTeX عند الحاجة، وإلا pdfLaTeX. يقوم بتشغيل العدد المطلوب من المرات.
- **أخطاء واضحة:** كل مشكلة تظهر مع اسم الملف ورقم السطر (اضغط للانتقال) مع تلميح مبسط للخطأ.
- **حزمة مفقودة؟** ضغطة زر واحدة تقوم بتثبيتها تلقائياً.
- **معاينة PDF** مع تكبير، بحث وروابط. **انقر نقراً مزدوجاً على الـ PDF** للانتقال إلى السطر في الكود.
- **آمن:** الكمبايل يعمل في بيئة معزولة (Sandbox) لا يمكنها قراءة ملفاتك الأخرى أو استخدام الإنترنت.

### Working together / الشغل الجماعي

**English:**
- **Live co-editing:** everyone types in the same project at once, and edits merge without conflicts.
- **See each other:** coloured cursors with names, and **Follow** mode.
- **Comments & Chat:** leave notes on text, chat inside the project, and share one live PDF.
- **Invite links** that can edit or only view. Remove a link and that person is out immediately.
- It runs over **Tailscale** (free): the project stays on your PC and friends connect from home.

**بالعربي:**
- **تعديل مباشر مشترك:** الجميع يكتبون في نفس المشروع في نفس الوقت، ويتم دمج التعديلات دون تعارض.
- **شوف بعضكم:** مؤشرات ملونة بأسماء المشاركين، ووضع **المتابعة (Follow)**.
- **تعليقات ودردشة:** اترك ملاحظات على النص، دردش داخل المشروع، وشارك ملف PDF واحد يتحدث للجميع.
- **روابط دعوة** تسمح بالتعديل أو المشاهدة فقط. أزل الرابط ليخرج الشخص فوراً.
- يعمل عبر **Tailscale** (مجاناً): يبقى المشروع على جهازك ويتصل أصدقاؤك من منازلهم.

### Safety net / الأمان

**English:**
- **Automatic saving & History:** saves a version every compile and every 10 minutes. Compare versions line by line and restore any of them.
- **Undo per person:** Ctrl+Z only undoes *your* changes.
- **Recently deleted:** restore a deleted project from the start page.
- **Automatic updates:** OsLatex checks once a day and updates itself with one click.

**بالعربي:**
- **حفظ تلقائي وسجل (History):** يحفظ نسخة عند كل كمبايل وكل 10 دقائق. قارن بين الإصدارات سطراً بسطر واستعد أي منها.
- **تراجع لكل شخص:** Ctrl+Z يقوم بالتراجع عن تغييراتك *أنت* فقط.
- **المحذوفة حديثاً:** استعد مشروعاً محذوفاً من صفحة البداية.
- **تحديثات تلقائية:** يتحقق البرنامج يومياً ويحدث نفسه بضغطة زر.

---

## Install / التثبيت

**English:**
1. **Download** `OsLatex.exe` from [Releases](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest) and put it in its own folder (e.g., `Documents\OsLatex`).
2. **Run it.** If Windows shows *"Windows protected your PC"*, click **More info → Run anyway** (the app isn't commercially code-signed).
3. **First time only:** choose **Standard** and click **Install**. It's about 0.6 GB and takes 10–20 minutes.

**بالعربي:**
1. **قم بالتحميل:** نزّل `OsLatex.exe` من صفحة [Releases](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)، وحطه في مجلد لحاله (مثلاً `Documents\OsLatex`).
2. **شغّله:** إذا طلع لك "Windows protected your PC"، اضغط **More info** بعدين **Run anyway** (لأن التطبيق غير موقّع تجارياً).
3. **أول مرة فقط:** اختر **Standard** واضغط **تثبيت (Install)**. حجمه تقريباً 0.6 GB، ويأخذ بين 10 و20 دقيقة.

---
**Requirements / المتطلبات:**
- Windows 10 or 11 (64-bit) / ويندوز 10 أو 11 (إصدار 64-بت).
- About 2 GB of free disk space for the LaTeX environment / مساحة تقريباً 2 GB من مساحة القرص الحرة لبيئة LaTeX.

---
*This repository only holds the downloads; OsLatex's source code is private.*
*هذا المستودع يحتوي فقط على ملفات التحميل؛ الكود المصدري لـ OsLatex خاص.*
