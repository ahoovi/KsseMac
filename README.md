# KsseMac

**KsseMac is a macOS menu-bar app that fixes a line you typed in the wrong keyboard layout, Hebrew ⇄ English.** You meant `שלום` and got `akuo`? Double-tap the KsseMac shortcut, and KsseMac converts the line in place and switches your keyboard to the right language.

In other words: a wrong-keyboard-layout fixer for Hebrew and English on the Mac.

> **This repository has no source code.** It holds KsseMac's release notes, requirements and support links. To get the app, go to **[kssemac.com](https://kssemac.com)**.

KsseMac is an app you install, and it works through its own shortcut: a double tap on the modifier key you pick (Command, Shift, Option or Control).

## Who it's for

Anyone who types both Hebrew and English on a Mac, and keeps discovering which language the keyboard was on only after typing a whole line. KsseMac supports both US (ANSI) and ISO physical keyboards.

## How it works

1. **You type in the wrong layout.** A whole line.
2. **You double-tap the KsseMac shortcut.** You choose the key during setup: Shift, Command, Option or Control. KsseMac converts the text in place, on the line where you typed it.
3. **You keep typing.** KsseMac has already switched the input source to the language of the corrected text.

A few things worth knowing:

- **KsseMac converts in both directions.** `akuo akuo` becomes `שלום שלום`, and `יקךךם` becomes `hello`.
- **KsseMac remaps keys. It does not translate.** It maps the physical keys you pressed back to the language you meant. If you wrote real English and want it in Hebrew, you need a translator.
- **KsseMac acts only when you press the shortcut.** It never converts on its own.
- **When an app doesn't expose its text** through the macOS accessibility interfaces, KsseMac falls back to the clipboard: select, copy, convert, paste. Since 1.4.5, KsseMac keeps your clipboard contents intact on that path.

## Requirements

- **KsseMac requires macOS 14 (Sonoma) or later.**
- Intel and Apple Silicon (Universal). About 1.1 MB.
- Permissions:

| Permission | Required? | Why KsseMac asks for it |
|---|---|---|
| **Accessibility** | Yes | macOS requires it from any app that reads or replaces text in other apps. KsseMac uses it to reach the active text field at the moment you press the shortcut, and to replace the line you asked to fix. |
| **Input Monitoring** | No. Only for "smart" mode | Lets KsseMac see what was originally typed, so it can also fix words that macOS autocorrect already changed. Basic mode doesn't track your typing at all, and misses those words. You choose the mode. |

## Where it works

Most macOS text fields work directly. These apps are named in KsseMac's release notes:

- **WhatsApp and Microsoft Teams:** since 1.4.8, conversion works also when the cursor is at the end of the line.
- **Browsers:** Chrome, Edge, Brave, Opera and Vivaldi, including Gmail, WhatsApp Web and ChatGPT in the browser (1.4.7). Dia, Arc and other apps built on Chromium (1.4.8).
- **Apple Mail:** in message bodies (1.4.7).
- **Google Docs:** after you turn on two accessibility settings inside Docs. In a document: Tools → Accessibility, then turn on both *Screen reader support* and *Braille support*. Docs saves this to your account, so you do it once.
- **Adobe Illustrator:** initial support (1.4). Select the text first.

Known limits:

- Without a selection, KsseMac converts everything from the start of the paragraph up to the cursor, including any part that was already right. In that case, select only the wrong part first.
- Password and other secure fields are excluded on purpose. KsseMac doesn't read or touch them.
- In a browser, the first conversion after the browser opens may take a second.

## Download and install

KsseMac is sold at [kssemac.com](https://kssemac.com). Right after payment you get an email with a download link to a DMG that is signed and notarized by Apple.

1. **Buy** at [kssemac.com](https://kssemac.com).
2. **Drag KsseMac.app to Applications** and run it from there, not from Downloads. macOS runs apps from Downloads in a temporary, random location (App Translocation), and the permissions you grant don't stick.
3. **A short onboarding** walks you through the Accessibility permission and the choice of shortcut key.
4. **That's it.** KsseMac sits in the menu bar. Nothing in the Dock.

**Updating:** download the new version from the link in your order email, drag it to Applications and choose "Replace". To hear about new versions, leave your email at [kssemac.com/#updates](https://kssemac.com/#updates). One email per release.

## Price

**15 ₪, one-time.** No subscription, no auto-renewal, no account. Full refund on any request made within 14 days of purchase. See the [terms](https://kssemac.com/terms) (in Hebrew).

## Support

Start with the [troubleshooting page](https://kssemac.com/trouble) (in Hebrew). It covers the six most common issues: the app won't open, the Accessibility permission doesn't appear, the shortcut doesn't work, why the app must be in Applications, Chrome/Gmail/Mail, and Google Docs.

Still stuck? Use the [form at the bottom of that page](https://kssemac.com/trouble#contact): your Mac model, your macOS version, and what happened.

## Privacy

- The conversion runs locally on your Mac. KsseMac sends no text anywhere. No server, no cloud, no account.
- KsseMac reaches your text only at the moment you press the shortcut. Not in the background.
- Nothing is uploaded and nothing is saved.
- Password and secure fields are excluded.
- Since 1.4.4, the text you convert is not written to any local log.

## Release notes

See [CHANGELOG.md](CHANGELOG.md), or "What's new in each version" at [kssemac.com/#releases](https://kssemac.com/#releases).

## Who made it

KsseMac is designed and built by [Amit Brin](https://www.amitbrin.com).

---

## בעברית

<div dir="rtl">

הקלדתם שורה שלמה בשפה הלא נכונה? לוחצים על הקיצור של KsseMac, והשורה מומרת במקום שבו נכתבה. KsseMac גם מעבירה את המקלדת לשפה הנכונה, וממשיכים להקליד.

KsseMac היא אפליקציה שמתקינים, והיא פועלת בקיצור משלה: לחיצה כפולה על המקש שבחרתם (Command, ‏Shift, ‏Option או Control). KsseMac דורשת macOS 14 ומעלה. ההמרה מקומית, ושום טקסט לא עוזב את המחשב.

הורדה, מחיר ותמיכה: [kssemac.com](https://kssemac.com). פתרון תקלות: [kssemac.com/trouble](https://kssemac.com/trouble).

</div>
