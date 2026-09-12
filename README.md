# MAX Video Downloader — Accessibility Improvements & Screen Reader Support

This repository contains accessibility enhancements and fixes for the **MAX Video Downloader** browser extension, tailored for visually impaired users and screen reader compatibility (NVDA, JAWS).

> **Disclaimer & Credit:**
> - Original Author: **Rostislav Alyaev** ([Website](https://maxvideodownloader.pro/) / [GitHub @Suwot](https://github.com/Suwot))
> - Official Extension: [Chrome Web Store](https://chromewebstore.google.com/detail/max-video-downloader-%E2%80%93-do/kjinbaahkmjgkkedfdgpkkelehofieke)
> - Companion App: [Suwot/mvd-coapp](https://github.com/Suwot/mvd-coapp)
> 
> This work is intended solely as an open contribution to assist the community and help the author integrate accessibility enhancements into the official release.

---

## 📥 Download & Installation

The ready-to-use extension is packaged and available in the **[Releases](https://github.com/komilblindev/max-video-downloader-fixed/releases)** section.

1. Go to [Releases](https://github.com/komilblindev/max-video-downloader-fixed/releases) and download `max-video-downloader-fixed.zip`.
2. Extract the archive into a folder on your computer.
3. Open Google Chrome, Microsoft Edge, or any Chromium browser and navigate to `chrome://extensions`.
4. Enable **Developer mode** in the top-right corner.
5. Click **Load unpacked** and select the extracted folder.

---

## ♿ What Has Been Improved

1. **Screen Reader Optimization (NVDA, JAWS):**
   - Verified and refined ARIA labels (`aria-label`, `aria-hidden`) on interactive buttons and controls.
   - Clear audio announcements for status indicators, format selections, and download progress.

2. **Keyboard Navigation & Hotkeys:**
   - Full keyboard accessibility across the popup interface.
   - Verified shortcuts:
     - `Alt + C`: Copy latest video URL to clipboard.
     - `Alt + F`: Copy latest FFmpeg command.
     - Configurable shortcut for downloading latest media on the active tab.

3. **User Experience for Visually Impaired Users:**
   - Better focus management and readable error/success messages.

---

## 🤝 For the Original Author (@Suwot)

Dear Rostislav, these adjustments were made by and for users with visual impairments who love and rely on your extension every day. Please feel free to review, test, and merge these changes into your official Chrome Web Store release. Thank you for your amazing work!
