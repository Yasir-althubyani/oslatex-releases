# OsLatex

**A LaTeX editor for Windows that compiles with a real LaTeX engine on your own PC, with live collaboration.**

**[⬇ Download OsLatex.exe (latest version)](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)**
**[⬇ تحميل OsLatex.exe (أحدث إصدار)](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)**

> **About:** OsLatex is a LaTeX editor for Windows. It compiles with a real LaTeX engine on your machine, lets you work on the same project live with friends, and keeps all your files local—no compile time limits, no subscriptions, and full Arabic support.
>
> **بالعربي:** OsLatex برنامج لكتابة LaTeX على ويندوز. يكمبايل بمحرك LaTeX حقيقي على جهازك، وتقدر تشتغل فيه مع خوياك على نفس المشروع لايف. وكل ملفاتك تظل عندك، بدون حدود وقت كمبايل، وبدون اشتراك. ويدعم العربي بالكامل.

---

## Why OsLatex? / ليش OsLatex؟

| | OsLatex | Online editors / المحررات السحابية |
|---|---|---|
| Where your files are / مكان ملفاتك | **On your PC** / على جهازك | On someone's server / على سيرفر شخص آخر |
| Compile time limit / حد وقت الكمبايل | **None**, even for a 100+ page thesis / لا يوجد، حتى لرسالة تتجاوز 100 صفحة | Free plans time out on big documents / الخطط المجانية تنتهي مهلتها في المستندات الكبيرة |
| Works offline / العمل بدون إنترنت | **Yes**, after the one-time setup / نعم، بعد التثبيت الأولي لمرة واحدة | No / لا |
| Live collaboration / العمل الجماعي المباشر | **Yes**, free, through your own PC / نعم، مجاناً، من خلال جهازك | Often a paid plan / غالباً تتطلب خطة مدفوعة |
| Arabic / اللغة العربية | **Built in** (XeLaTeX + Amiri, right-to-left lines) / مدعومة من البداية (XeLaTeX + خط أميري، مع دعم RTL) | Depends on setup / تعتمد على الإعدادات |
| Price / السعر | **Free** / مجاني | Free plans with limits / خطط مجانية بحدود |

- **Your files stay with you:** Projects are on your machine, not on someone's server.
- **No compile time limits:** Even if your graduation project is over 100 pages.
- **Works offline:** After the one-time setup.
- **Free live collaboration:** Friends join your project from their homes.
- **Full Arabic support** out of the box.

- **ملفاتك عندك:** المشاريع على جهازك مو على سيرفر أحد.
- **بدون حد وقت للكمبايل:** حتى لو مشروع التخرج حقك فوق 100 صفحة.
- **يشتغل بدون نت:** بعد ما تركّب المكونات مرة وحدة.
- **شغل جماعي لايف ببلاش:** خوياك يدخلون على مشروعك من بيوتهم.
- **العربي مدعوم من البداية.**

---

## Features / المزايا

### Writing / الكتابة
- **A full LaTeX editor:** syntax colours, autocomplete for commands, `\ref` labels, `\cite` keys, file paths and packages, code folding, search & replace, and multiple cursors.
- **Formatting toolbar:** headings, bold/italic, math, a symbol palette (Greek, arrows, ℝ…), lists, tables (pick the size on a grid), figures, links and citations.
- **Paste a screenshot (Ctrl+V)** into the editor: it's saved in `figures/` and the figure code is written for you.
- **Add a reference from a DOI or arXiv ID:** OsLatex fetches it, adds it to your `.bib` with a clean key such as `Vaswani_2017`, and inserts `\cite{…}`.
- **Outline** of the whole document (chapters, sections…) and **search across all files**.
- **Arabic:** right-to-left lines and Arabic templates, and the right engine is picked automatically.

- **محرر LaTeX متكامل:** ألوان للصيغة البرمجية (Syntax colors)، إكمال تلقائي للأوامر، وسوم `\ref`، مفاتيح `\cite`، مسارات الملفات والحزم، طي الكود (Code folding)، بحث واستبدال، ومؤشرات متعددة.
- **شريط أدوات للتنسيق:** العناوين، غامق/مائل، رياضيات، لوحة رموز (يونانية، أسهم، ℝ...)، قوائم، جداول (اختر الحجم من شبكة)، أشكال، روابط واستشهادات.
- **لصق لقطة شاشة (Ctrl+V)** مباشرة في المحرر: يتم حفظها في مجلد `figures/` ويتم كتابة كود الشكل تلقائياً لك.
- **إضافة مرجع من DOI أو arXiv ID:** يقوم OsLatex بجلبه، وإضافته إلى ملف `.bib` الخاص بك بمفتاح نظيف مثل `Vaswani_2017`، وإدراج أمر `\cite{…}` في مكان المؤشر.
- **المخطط التفصيلي (Outline)** للمستند بأكمله (الفصول، الأقسام...) و**البحث في جميع الملفات**.
- **اللغة العربية:** سطور من اليمين إلى اليسار (RTL) وقوالب عربية، ويتم اختيار محرك الكمبايل المناسب تلقائياً.

### Compiling / الكمبايل
- **Real LaTeX engines:** pdfLaTeX, XeLaTeX, LuaLaTeX, BibTeX and Biber. The PDF is the real one, not an approximation.
- **Auto engine:** XeLaTeX for Arabic and `fontspec`, LuaLaTeX when needed, otherwise pdfLaTeX. It runs as many passes as references and bibliographies need.
- **Clear errors:** each problem with its file and line (click to jump there) and a plain-language hint about what's wrong.
- **Missing package?** One click installs it automatically.
- **PDF preview** with zoom, search and links. **Double-click the PDF** to jump to that line in the source.
- **Safe:** compiles run in a sandbox that can't read your other files, run programs or use the internet.

- **محركات LaTeX حقيقية:** pdfLaTeX، XeLaTeX، LuaLaTeX، BibTeX و Biber. ملف الـ PDF الناتج هو ملف حقيقي، وليس مجرد تقدير.
- **محرك تلقائي:** يستخدم XeLaTeX للغة العربية و `fontspec`، و LuaLaTeX عند الحاجة، وإلا يستخدم pdfLaTeX. يقوم بتشغيل العدد المطلوب من المرات حسب المراجع وقوائم المصادر.
- **أخطاء واضحة:** كل مشكلة تظهر مع اسم الملف ورقم السطر (اضغط للانتقال إليها) مع تلميح بلغة بسيطة يشرح ما هو الخطأ.
- **هل الحزمة مفقودة؟** ضغطة زر واحدة تقوم بتثبيتها تلقائياً.
- **معاينة PDF** مع تكبير، بحث وروابط. **انقر نقراً مزدوجاً على الـ PDF** للانتقال إلى ذلك السطر في الكود المصدري.
- **آمن:** يتم تشغيل الكمبايل في بيئة معزولة (Sandbox) لا يمكنها قراءة ملفاتك الأخرى، أو تشغيل برامج، أو استخدام الإنترنت.

### Working together / الشغل الجماعي
- **Live co-editing:** everyone types in the same project at once, and edits merge without conflicts.
- **See each other:** coloured cursors with names, who is in which file, and **Follow** mode.
- **Comments:** select text and leave a note; friends reply and resolve it.
- **Chat** inside the project, plus one shared PDF that updates for everyone.
- **Invite links** that can edit or only view. Remove a link and that person is out immediately.
- It runs over **Tailscale** (free): the project stays on your PC and friends connect from home.

- **تعديل مباشر مشترك:** الجميع يكتبون في نفس المشروع في نفس الوقت، ويتم دمج التعديلات دون تعارض.
- **شوف بعضكم:** مؤشرات ملونة بأسماء المشاركين، ومن في أي ملف، ووضع **المتابعة (Follow)**.
- **تعليقات:** حدد النص واترك ملاحظة؛ يرد أصدقاؤك ويحلونها.
- **دردشة (Chat)** داخل المشروع، بالإضافة إلى ملف PDF مشترك واحد يتم تحديثه للجميع.
- **روابط دعوة** تسمح بالتعديل أو المشاهدة فقط. قم بإزالة الرابط ويخرج هذا الشخص فوراً.
- يعمل عبر **Tailscale** (مجاناً): يبقى المشروع على جهازك الشخصي ويتصل أصدقاؤك من منازلهم.

### Safety net / الأمان
- **Automatic saving** and **History:** every compile and every 10 minutes of work saves a version. Compare versions line by line and restore any of them.
- **Undo per person:** Ctrl+Z only undoes *your* changes.
- **Recently deleted:** restore a deleted project from the start page.
- **Automatic updates:** OsLatex checks once a day and updates itself with one click.

- **حفظ تلقائي** و **سجل (History):** يتم حفظ نسخة عند كل عملية كمبايل وكل 10 دقائق من العمل. قارن بين الإصدارات سطراً بسطر واستعد أي منها.
- **تراجع لكل شخص:** Ctrl+Z يقوم بالتراجع عن تغييراتك *أنت* فقط.
- **المحذوفة حديثاً:** استعد مشروعاً محذوفاً من صفحة البداية.
- **تحديثات تلقائية:** يتحقق OsLatex مرة واحدة يومياً ويقوم بتحديث نفسه بضغطة زر واحدة.

---

## Install / التثبيت

1. **Download** `OsLatex.exe` from [Releases](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest) and put it in its own folder, for example `Documents\OsLatex`.
2. **Run it.** If Windows shows *"Windows protected your PC"*, click **More info → Run anyway**. This appears because the app isn't commercially code-signed.
3. **First time only:** choose **Standard** and click **Install**. It's about 0.6 GB and usually takes 10–20 minutes, and the app is ready when it finishes.

1. **قم بالتحميل:** نزّل `OsLatex.exe` من صفحة [Releases](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)، وحطه في مجلد لحاله، مثلاً `Documents\OsLatex`.
2. **شغّله:** إذا طلع لك "Windows protected your PC"، اضغط **More info** بعدين **Run anyway**. تظهر هذه الرسالة لأن التطبيق غير موقّع تجارياً.
3. **أول مرة فقط:** اختر **Standard** واضغط **تثبيت (Install)**. حجمه تقريباً 0.6 GB، ويأخذ عادةً بين 10 و20 دقيقة، ويكون التطبيق جاهزاً عند الانتهاء.

**Needs:** Windows 10 or 11 (64-bit). About 2 GB of free disk space for the LaTeX environment.
**المتطلبات:** ويندوز 10 أو 11 (إصدار 64-بت). مساحة تقريباً 2 GB من مساحة القرص الحرة لبيئة LaTeX.

---

*This repository only holds the downloads; OsLatex's source code is private.*
*هذا المستودع (Repository) يحتوي فقط على ملفات التحميل؛ الكود المصدري لـ OsLatex خاص.*
