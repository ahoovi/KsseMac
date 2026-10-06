# KsseMac release notes

KsseMac is a macOS menu-bar app that fixes text typed in the wrong keyboard layout, Hebrew ⇄ English. Get it at [kssemac.com](https://kssemac.com). This repository has no source code.

Each version is listed in English, followed by the original Hebrew text from kssemac.com.

## 1.4.8 · 6 October 2026 · build 6 (current)

- Fix in WhatsApp and Teams: conversion works even when the cursor is at the end of the line. In the previous version the text was only selected and not converted.
- The same fix in the Dia and Arc browsers and in other apps built on Chromium.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- תיקון בוואטסאפ וב-Teams: ההמרה עובדת גם כשהסמן בסוף השורה. בגרסה הקודמת הטקסט רק סומן ולא הומר.
- אותו תיקון גם בדפדפנים Dia ו-Arc ובאפליקציות נוספות שבנויות על Chromium.

</div>
</details>

## 1.4.7 · 27 September 2026

- Full support for Chrome, Edge, Brave, Opera and Vivaldi, including Gmail, WhatsApp Web and ChatGPT in the browser.
- Conversion works again in messages in the Mail app.
- In Google Docs: an explanation of what to turn on so that conversion works.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- תמיכה מלאה ב-Chrome, Edge, Brave, Opera ו-Vivaldi - כולל Gmail, WhatsApp Web ו-ChatGPT בדפדפן.
- ההמרה חוזרת לעבוד בהודעות באפליקציית Mail.
- ב-Google Docs: הסבר מה להפעיל כדי שההמרה תעבוד.

</div>
</details>

## 1.4.6 · 25 September 2026

- Fix to keyboard detection, which could prevent conversion both from the shortcut and from the menu.
- Improved setup process, with a direct jump to System Settings.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- תיקון זיהוי המקלדות, שעלול היה למנוע המרה גם מהקיצור וגם מהתפריט.
- תהליך הגדרה משופר, עם מעבר ישיר להגדרות המערכת.

</div>
</details>

## 1.4.5

- Fix for false triggers of the shortcut.
- Full preservation of the clipboard on the fallback path.
- Remembers the last input source that was in use.
- Option to launch automatically at login.
- Built-in update check.
- New menu-bar icon.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- תיקון הפעלות שווא של הקיצור.
- שמירה מלאה של לוח ההעתקה במסלול הגיבוי.
- זכירת מקור הקלט האחרון שהיה בשימוש.
- אפשרות הפעלה אוטומטית בכניסה למחשב.
- בדיקת עדכונים מובנית.
- אייקון חדש לשורת התפריטים.

</div>
</details>

## 1.4.4

- Uniform keyboard mapping for US and ISO: no more partial or wrong conversions.
- The choice of keyboard type was removed from onboarding and from the settings.
- Privacy: the text you converted is no longer written to any local log.
- The shortcut is now detected also when the app itself is in focus.
- Security cleanup of the app package.
- The app stays active in the background.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- מיפוי מקלדת אחיד ל-US ול-ISO - סוף להמרות חלקיות או שגויות.
- בחירת סוג המקלדת ירדה מהאונבורדינג ומההגדרות.
- פרטיות: הטקסט שהמרת לא נכתב יותר לשום לוג מקומי.
- הקיצור מזוהה עכשיו גם כשהאפליקציה עצמה בפוקוס.
- ניקוי אבטחה של החבילה.
- האפליקציה נשארת פעילה ברקע.

</div>
</details>

## 1.4

- A separate Setup Assistant for macOS permissions.
- A clear separation between the basic Accessibility permission and the Input Monitoring of smart detection.
- Shortcuts in the top menu: Settings, Check for Updates and the home website.
- Initial support for the Adobe Illustrator app.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- Setup Assistant נפרד להרשאות macOS.
- הפרדה ברורה בין הרשאת Accessibility הבסיסית לבין Input Monitoring של הזיהוי החכם.
- קיצורים בתפריט העליון: הגדרות, בדיקת עדכונים ואתר הבית.
- תמיכה ראשונית באפליקציית Adobe Illustrator.

</div>
</details>

## 1.3.3

- After conversion, the input language switches to the language of the text, and you keep typing without a break.
- The onboarding screen adapts itself to Light and Dark Mode.
- New app icon, matching macOS Tahoe.
- Start of signed and notarized distribution.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- אחרי המרה, שפת הקלט עוברת לשפת הטקסט - וממשיכים להקליד ברצף.
- מסך האונבורדינג מתאים את עצמו ל-Light ול-Dark Mode.
- אייקון אפליקציה חדש, תואם macOS Tahoe.
- תחילת ההפצה החתומה והמאושרת נוטריונית.

</div>
</details>

## 1.3.2

- The Accessibility permission request no longer opens behind the onboarding window.
- A smoother first launch, with fewer repeated permission requests.
- Updated text in the help and onboarding screens.

<details>
<summary>Original (Hebrew)</summary>

<div dir="rtl">

- בקשת הרשאת Accessibility כבר לא נפתחת מאחורי חלון האונבורדינג.
- הפעלה ראשונה חלקה יותר, עם פחות בקשות הרשאה חוזרות.
- עדכון הטקסטים במסכי העזרה והאונבורדינג.

</div>
</details>
