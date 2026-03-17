<div align="center">

# 🔗 GitHub RAW Link Converter

**EN:** A professional web tool to instantly convert GitHub RAW links into Repository & File links.  
**AR:** أداة ويب احترافية لتحويل روابط GitHub RAW فوراً إلى روابط المستودع والملف.

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br/>

![Demo Preview](https://raw.githubusercontent.com/abdulrahman20242/github-raw-link-converter/main/preview.png)

</div>

---

## 🌐 Language / اللغة

- [🇺🇸 English](#-about-the-project)
- [🇸🇦 العربية](#-نبذة-عن-المشروع)

---

---

# 🇺🇸 English

---

## 📋 About the Project

**GitHub RAW Link Converter** is a free, lightweight, browser-based tool that instantly converts `raw.githubusercontent.com` links into:

- 🏠 The **Repository** link on GitHub
- 📄 The direct **File** link inside the repository

Designed with a sleek dark Arabic UI inspired by GitHub's own design language.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ⚡ **Instant Conversion** | Convert links instantly on input or button press |
| 📦 **Batch Mode** | Convert dozens of links at once |
| 📋 **One-click Copy** | Copy any result link with a single click + confirmation toast |
| 🕓 **History Log** | Automatically saves the last 10 converted links |
| 📎 **Paste from Clipboard** | Paste links directly from clipboard with a dedicated button |
| ⌨️ **Keyboard Shortcut** | `Ctrl + Enter` to trigger conversion quickly |
| 🌑 **Full Dark Mode** | Eye-friendly dark design |
| 📱 **Responsive** | Works on mobile, tablet, and desktop |
| 🔒 **No Server Upload** | Everything runs 100% locally in the browser |

---

## 🚀 Getting Started

### Installation

No installation needed! Simply:

```bash
git clone https://github.com/abdulrahman20242/github-raw-link-converter.git
```

Then open `GitHub_RAW_Link_Converter.HTML` directly in your browser.

---

### Basic Usage

**1. Paste a RAW link** from GitHub like this:

```
https://raw.githubusercontent.com/username/repo/branch/path/to/file.js
```

**2. Press the "Convert" button** or `Ctrl + Enter`

**3. Get your results:**

```
🏠 Repository:  https://github.com/username/repo
📄 File:        https://github.com/username/repo/blob/branch/path/to/file.js
```

---

### Batch Mode

Enable the **Batch toggle**, then enter multiple links — one per line:

```
https://raw.githubusercontent.com/user/repo/main/index.html
https://raw.githubusercontent.com/user/repo/main/style.css
https://raw.githubusercontent.com/user/repo/main/app.js
```

Press **Convert** and all results appear at once with a **Copy All** button.

---

## 🛠️ Tech Stack

- **HTML5** — Page structure
- **CSS3** — Styling & animations (Animations, Glassmorphism effects)
- **Vanilla JavaScript** — Conversion logic & history management
- **LocalStorage** — Persist conversion history locally
- **Google Fonts** — `Inter` & `JetBrains Mono`

---

## 📐 Project Structure

```
github-raw-link-converter/
│
├── GitHub_RAW_Link_Converter.HTML   # Full tool (Single-file app)
├── README.md                        # This file
└── preview.png                      # Preview image (optional)
```

---

## 🔍 Supported Link Examples

```
✅ https://raw.githubusercontent.com/torvalds/linux/master/README
✅ https://raw.githubusercontent.com/facebook/react/main/packages/react/index.js
✅ https://raw.githubusercontent.com/microsoft/vscode/main/package.json
```

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a suggestion:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push: `git push origin feature/feature-name`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and distribute.

---
---

# 🇸🇦 العربية

---

## 📋 نبذة عن المشروع

**GitHub RAW Link Converter** هي أداة ويب مجانية وخفيفة تعمل مباشرة في المتصفح، تمكّنك من تحويل روابط `raw.githubusercontent.com` بشكل فوري إلى:

- 🏠 رابط **المستودع** على GitHub
- 📄 رابط **الملف** المباشر داخل المستودع

مصممة بواجهة عربية داكنة أنيقة مستوحاة من تصميم GitHub نفسه.

---

## ✨ المميزات

| الميزة | الوصف |
|--------|--------|
| ⚡ **تحويل فوري** | تحويل الرابط لحظياً بمجرد الإدخال أو الضغط على زر التحويل |
| 📦 **وضع الدُفعات** | تحويل عشرات الروابط دفعة واحدة |
| 📋 **نسخ بنقرة** | نسخ أي رابط ناتج بزر واحد مع إشعار تأكيد |
| 🕓 **سجل التحويلات** | حفظ آخر 10 روابط تم تحويلها تلقائياً |
| 📎 **لصق من الحافظة** | لصق الرابط مباشرة من الحافظة بزر مخصص |
| ⌨️ **اختصار لوحة المفاتيح** | `Ctrl + Enter` لتشغيل التحويل سريعاً |
| 🌑 **وضع داكن كامل** | تصميم Dark Mode مريح للعين |
| 📱 **متجاوب** | يعمل على الهاتف والتابلت والحاسوب |
| 🔒 **لا رفع للسيرفر** | كل شيء يعمل محلياً في المتصفح 100% |

---

## 🚀 كيفية الاستخدام

### التثبيت

لا يحتاج أي تثبيت! فقط:

```bash
git clone https://github.com/abdulrahman20242/github-raw-link-converter.git
```

ثم افتح ملف `GitHub_RAW_Link_Converter.HTML` مباشرة في المتصفح.

---

### الاستخدام الأساسي

**1. الصق رابط RAW** من GitHub بهذا الشكل:

```
https://raw.githubusercontent.com/username/repo/branch/path/to/file.js
```

**2. اضغط زر "تحويل"** أو `Ctrl + Enter`

**3. احصل على النتائج:**

```
🏠 رابط المستودع:  https://github.com/username/repo
📄 رابط الملف:     https://github.com/username/repo/blob/branch/path/to/file.js
```

---

### وضع الدُفعات (Batch Mode)

فعّل **مفتاح Batch** ثم أدخل روابط متعددة، كل رابط في سطر:

```
https://raw.githubusercontent.com/user/repo/main/index.html
https://raw.githubusercontent.com/user/repo/main/style.css
https://raw.githubusercontent.com/user/repo/main/app.js
```

اضغط **تحويل** وستظهر جميع النتائج دفعة واحدة مع إمكانية **نسخ الكل**.

---

## 🛠️ التقنيات المستخدمة

- **HTML5** — هيكل الصفحة
- **CSS3** — التصميم والتحريكات (Animations، Glassmorphism)
- **Vanilla JavaScript** — منطق التحويل وإدارة السجل
- **LocalStorage** — حفظ سجل التحويلات محلياً
- **Google Fonts** — خطوط `Inter` و `JetBrains Mono`

---

## 📐 هيكل المشروع

```
github-raw-link-converter/
│
├── GitHub_RAW_Link_Converter.HTML   # ملف الأداة الكامل (Single-file app)
├── README.md                        # هذا الملف
└── preview.png                      # صورة المعاينة (اختياري)
```

---

## 🔍 أمثلة على الروابط المدعومة

```
✅ https://raw.githubusercontent.com/torvalds/linux/master/README
✅ https://raw.githubusercontent.com/facebook/react/main/packages/react/index.js
✅ https://raw.githubusercontent.com/microsoft/vscode/main/package.json
```

---

## 🤝 المساهمة

المساهمات مرحب بها! إذا وجدت مشكلة أو لديك اقتراح:

1. Fork المستودع
2. أنشئ Branch جديدة: `git checkout -b feature/اسم-الميزة`
3. Commit التغييرات: `git commit -m 'إضافة ميزة جديدة'`
4. Push: `git push origin feature/اسم-الميزة`
5. افتح Pull Request

---

## 📄 الرخصة

هذا المشروع مرخص تحت [MIT License](LICENSE) — يمكنك استخدامه وتعديله وتوزيعه بحرية.

---

<div align="center">

Made with ❤️ for the developer community · صُنع بـ ❤️ لمجتمع المطورين

⭐ If you like this project, give it a star! · إذا أعجبك المشروع لا تنسَ تعطيه نجمة!

</div>
