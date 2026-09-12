# MAX Video Downloader — Accessibility Improvements & Screen Reader Support

This repository contains accessibility enhancements and fixes for the **MAX Video Downloader** browser extension, tailored for visually impaired users and screen reader compatibility (NVDA, JAWS).

> **Disclaimer & Credit:**
> - Original Author: **Rostislav Alyaev** ([Website](https://maxvideodownloader.pro/) / [GitHub @Suwot](https://github.com/Suwot))
> - Official Extension: [Chrome Web Store](https://chromewebstore.google.com/detail/max-video-downloader-%E2%80%93-do/kjinbaahkmjgkkedfdgpkkelehofieke)
> - Companion App: [Suwot/mvd-coapp](https://github.com/Suwot/mvd-coapp)
> 
> This work is intended solely as an open contribution to assist the visually impaired community and help the author integrate accessibility enhancements into the official release.

---

## 📥 Download & Installation Guide / Инструкция по установке

The packaged extension is available in the **[Releases](https://github.com/komilblindev/max-video-downloader-fixed/releases)** section.

### 🇬🇧 English: Step-by-Step (Keyboard & Screen Reader Friendly)

1. **Download:** Go to the [Releases](https://github.com/komilblindev/max-video-downloader-fixed/releases) page and download `max-video-downloader-fixed.zip`.
2. **Extract:** Unzip the archive into any folder on your computer.
3. **Open Extensions Page:** Open Google Chrome, Microsoft Edge, Brave, or Yandex Browser and navigate to:
   `chrome://extensions` (or `edge://extensions` for Edge).
4. **Enable Developer Mode:** Press `Tab` until your screen reader announces **"Developer mode"** toggle switch, then press `Space` to enable it.
5. **Load Unpacked:** Press `Tab` until you reach the **"Load unpacked"** button and press `Enter`.
6. **Select Folder:** In the folder picker dialog, select the extracted folder and press `Enter` (or click "Select Folder").
7. **Done:** The extension will appear in your extensions list, ready to use!

---

### 🇷🇺 Русский: Пошаговая инструкция (с клавиатуры и скринридера)

1. **Скачивание:** Перейдите в раздел [Releases](https://github.com/komilblindev/max-video-downloader-fixed/releases) и скачайте архив `max-video-downloader-fixed.zip`.
2. **Распаковка:** Распакуйте скачанный ZIP-архив в любую удобную папку на компьютере.
3. **Страница расширений:** Откройте браузер (Chrome, Edge, Яндекс или Brave) и перейдите по адресу:
   `chrome://extensions` (для Edge: `edge://extensions`).
4. **Режим разработчика:** Клавишей `Tab` найдите переключатель **«Режим разработчика»** (Developer mode) в правом верхнем углу и включите его клавишей `Пробел`.
5. **Загрузка папки:** Нажимайте `Tab`, пока не услышите кнопку **«Загрузить распакованное расширение»** (Load unpacked), и нажмите `Enter`.
6. **Выбор папки:** В стандартном диалоговом окне проводника выберите распакованную папку и нажмите кнопку «Выбор папки» (`Enter`).
7. **Готово:** Расширение установлено и доступно в списке расширений!

---

## ⌨️ Hotkeys & Keyboard Shortcuts (Горячие клавиши)

You can manage downloads completely without a mouse:

* `Alt + C` — **Copy Latest Video URL:** Instantly copies the direct link of the detected video to your clipboard.
* `Alt + F` — **Copy Latest FFmpeg Command:** Copies a ready-to-run FFmpeg command for command-line downloading.
* **Custom Shortcut for Downloading:** Navigate to `chrome://extensions/shortcuts` to bind your favorite key combination to the **"Download latest on tab"** action.

---

## ♿ What Has Been Improved (Что улучшено)

1. **Screen Reader Optimization (NVDA, JAWS, Narrator):**
   - Verified and refined ARIA labels (`aria-label`, `aria-hidden`) on all interactive buttons and popup controls.
   - Clear audio announcements for status indicators, format selections, and download progress.
2. **Keyboard Navigation:**
   - Logical `Tab` order throughout popup and settings pages.
   - High-contrast focus outlines for visually impaired users.
3. **CoApp Compatibility:**
   - Works smoothly with the official companion app for DASH and high-quality muxing: [Suwot/mvd-coapp](https://github.com/Suwot/mvd-coapp/releases/latest).

---

## 🤝 For the Original Author (@Suwot)

Dear Rostislav, these adjustments were made by and for users with visual impairments who love and rely on your extension every day. Please feel free to review, test, and merge these changes into your official Chrome Web Store release. Thank you for your amazing work!
