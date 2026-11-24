# OsLatex

**A LaTeX editor for Windows that compiles with real TeX Live on your own PC, with live collaboration like Overleaf.**

**[⬇ Download OsLatex.exe (latest version)](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)**

> **بالعربي:** OsLatex برنامج لكتابة LaTeX على ويندوز. يكمبايل بـTeX Live الحقيقي على جهازك، وتقدر تشتغل فيه مع خوياك على نفس المشروع لايف مثل Overleaf. وكل ملفاتك تظل عندك، بدون حدود وقت كمبايل، وبدون اشتراك. ويدعم العربي بالكامل.

---

## Why OsLatex? / ليش OsLatex؟

| | OsLatex | Online editors |
|---|---|---|
| Where your files are | **On your PC** | On someone's server |
| Compile time limit | **None**, even for a 100+ page thesis | Free plans time out on big documents |
| Works offline | **Yes**, after the one-time setup | No |
| Live collaboration | **Yes**, free, through your own PC | Often a paid plan |
| Arabic | **Built in** (XeLaTeX + Amiri, right-to-left lines) | Depends on setup |
| Price | **Free** | Free plans with limits |

- **ملفاتك عندك:** المشاريع على جهازك مو على سيرفر أحد.
- **بدون حد وقت للكمبايل:** حتى لو مشروع التخرج حقك فوق 100 صفحة.
- **يشتغل بدون نت** بعد ما تركّب TeX مرة وحدة.
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

### Compiling / الكمبايل
- **Real TeX Live:** pdfLaTeX, XeLaTeX, LuaLaTeX, BibTeX and Biber. The PDF is the real one, not an approximation.
- **Auto engine:** XeLaTeX for Arabic and `fontspec`, LuaLaTeX when needed, otherwise pdfLaTeX. It runs as many passes as references and bibliographies need.
- **Clear errors:** each problem with its file and line (click to jump there) and a plain-language hint about what's wrong.
- **Missing package?** One click installs it from TeX Live.
- **PDF preview** with zoom, search and links. **Double-click the PDF** to jump to that line in the source.
- **Safe:** compiles run in a sandbox that can't read your other files, run programs or use the internet.

### Working together / الشغل الجماعي
- **Live co-editing** like Overleaf: everyone types in the same project at once, and edits merge without conflicts.
- **See each other:** coloured cursors with names, who is in which file, and **Follow** mode.
- **Comments:** select text and leave a note; friends reply and resolve it.
- **Chat** inside the project, plus one shared PDF that updates for everyone.
- **Invite links** that can edit or only view. Remove a link and that person is out immediately.
- It runs over **Tailscale** (free): the project stays on your PC and friends connect from home.

### Safety net / الأمان
- **Automatic saving** and **History:** every compile and every 10 minutes of work saves a version. Compare versions line by line and restore any of them.
- **Undo per person:** Ctrl+Z only undoes *your* changes.
- **Recently deleted:** restore a deleted project from the start page.
- **Automatic updates:** OsLatex checks once a day and updates itself with one click.

---

## Install / التثبيت

1. **Download** `OsLatex.exe` from [Releases](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest) and put it in its own folder, for example `Documents\OsLatex`.
2. **Run it.** If Windows shows *"Windows protected your PC"*, click **More info → Run anyway**. This appears because the app isn't commercially code-signed.
3. **First time only:** choose **Standard** and click **Install TeX Live**. It's about 0.6 GB and usually takes 10–20 minutes, and the app is ready when it finishes.

1. نزّل `OsLatex.exe` من صفحة [Releases](https://github.com/Yasir-althubyani/oslatex-releases/releases/latest)، وحطه في مجلد لحاله.
2. شغّله. إذا طلع لك "Windows protected your PC"، اضغط **More info** بعدين **Run anyway**.
3. أول مرة بس: اختر **Standard** واضغط **Install TeX Live**. تقريباً 0.6 GB، وتاخذ بين 10 و20 دقيقة.

**Needs:** Windows 10 or 11 (64-bit). About 2 GB of free disk space for TeX Live.

---

*This repository only holds the downloads; OsLatex's source code is private.*
