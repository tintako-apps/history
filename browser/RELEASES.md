# Ink Browser: all releases

## [Ink Browser 1.1.1](https://github.com/tintako-apps/history/releases/tag/browser-v1.1.1)
Published 2026-11-19 · first released in tintako-apps/browser as v1.1.1

Files: `InkBrowser-1.1.1-1-start.png`, `InkBrowser-1.1.1-2-tabs.png`, `InkBrowser-1.1.1-3-reader.png`, `InkBrowser-1.1.1.apk`

A calm web browser made for E Ink devices. Pages turn screen by screen, and there are no Google services. It installs over 1.1.

**What's new**
- Browser is now called Ink Browser. Your tabs, bookmarks and settings stay as they are

**Fixed**
- After the app was force-stopped, pages could stay blank until the phone was restarted
- With "Open in the reader" on, a page that redirects (for example a mobile Wikipedia address) stayed white; it now opens in the reader
- The cursor in the address field no longer blinks, so the screen stays still while you type
- A link opened from another app now opens even when the app was closed, instead of the last tab

## [Browser 1.1](https://github.com/tintako-apps/history/releases/tag/browser-v1.1)
Published 2026-11-17 · first released in tintako-apps/browser as v1.1

Files: `Browser-1.1-1-start.png`, `Browser-1.1-2-tabs.png`, `Browser-1.1-3-reader.png`, `Browser-1.1.apk`

A calm web browser made for E Ink devices. Pages turn screen by screen, and there are no Google services. It installs over 1.0.1.

**What's new**
- New tab now opens a simple choice at the bottom of the screen: Classic or Private, each with a short line on what it keeps
- Settings open from a gear icon
- Messages such as "No internet" or "Picture saved" now sit in a dotted, rounded box under the top row
- While AdGuard is added or updated, or a search engine is checked, the button keeps its name and a message under the top row says what is happening
- About shows the maker, Tintako, with the contact address; the Tip jar now leads to ko-fi.com/tintako
- Saved pictures now go to Pictures/Browser; pictures saved earlier stay where they are

**Fixed**
- A page without a title showed the name of the previous page; it now shows its own address
- How to use said four tabs; the limit is three

## [Browser 1.0.1](https://github.com/tintako-apps/history/releases/tag/browser-v1.0.1)
Published 2026-11-11 · first released in tintako-apps/browser as v1.0.1

Files: `Browser-1.0.1.apk`

A calm web browser made for E Ink. It installs over 1.0.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J4V82A4UVG)

**Fixed**
- Browser no longer closes when a page offers to log in with a passkey, for example the Mudita Forum's login. Passkeys would need Google's services, which Browser leaves out, so pages now offer the usual password login instead.

## [Browser 1.0](https://github.com/tintako-apps/history/releases/tag/browser-v1.0)
Published 2026-11-09 · first released in tintako-apps/browser as v1.0

Files: `Browser-1.0.apk`

A calm web browser made for E Ink. Pages turn screen by screen, a reader mode keeps only the text, and there are no Google services. It installs over the betas and RC1.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J4V82A4UVG)

**What's new**
- A refresh button inside the address field. While a page loads, it turns into ✕ to stop.
- Bookmarks in the Tabs window have their own icon, so the list is easy to tell from the Bookmark button for the page you're on.

**Fixed**
- A tab left on "The connection isn't encrypted" now comes back the same way after the browser restarts, instead of saying the page isn't safe.
- Pressing Back while typing an address closes the field together with the keyboard, so the next tap works straight away.

**Battery**
- Not yet measured on a real device. On the emulator, nothing of the browser keeps running once it leaves the screen.

## [Browser 1.0 RC1](https://github.com/tintako-apps/history/releases/tag/browser-v1.0-rc1) (pre-release)
Published 2026-11-08 · first released in tintako-apps/browser as v1.0-rc1

Files: `Browser-1.0-rc1.apk`

A calm web browser made for E Ink. Pages turn screen by screen, a reader mode keeps only the text, and there are no Google services.

**This is a release candidate for 1.0, and testers are welcome.** It installs over the beta. Report what you find in [Issues](https://github.com/tintako-apps/browser/issues).

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J4V82A4UVG)

**What's new**
- Hold a picture on a page to save it to your gallery, in the Pictures/Preglednik folder.
- A new Downloads list with saved pictures and downloaded files. Tap one to open it; deleting asks first.
- Reader mode is now full screen. A pull-out bar at the top has text size, bookmark, and the book that closes the reader.
- Up to three tabs, so the Tabs window fits the screen.
- The browser now closes completely when it leaves the screen, so nothing runs in the background. Your tabs come back when you return.
- The About page lists all open source parts with their licence texts and the GeckoView source code.
- A new app icon: a desk globe.

**Fixed**
- The Tabs window's lists sit in one row with Bookmarks, History and Downloads.

## [Browser 0.4 beta](https://github.com/tintako-apps/history/releases/tag/browser-v0.4-beta) (pre-release)
Published 2026-11-08 · first released in tintako-apps/browser as v0.4-beta

Files: `Browser-0.4-beta.apk`

A calm web browser made for E Ink. Pages turn screen by screen, a reader mode keeps only the text, and there are no Google services.

**This is a beta, and testers are welcome.** Install it, use it, and report what you find in [Issues](https://github.com/tintako-apps/browser/issues). The final version will install over the beta, so you won't end up with two apps.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J4V82A4UVG)

**What's new**
- A new top row: Tabs on the left, the page's name in the middle and Settings on the right. Tap the name to type an address.
- The Tabs window lists your tabs, and has QR code, Bookmark and Reading view for the page you're on, plus Bookmarks and History.
- The page is now the home screen. Bookmarks and History have a back arrow that returns to it.
- The ad blocker is now AdGuard, added from Mozilla's site in Settings, Protection. uBlock Origin from earlier betas is removed on its own.
- Removing a bookmark or a visit asks first.
- Bookmarks have a magnifier that leads to the address field.
- A new app icon.

**Fixed**
- The QR code for sharing is now centred on the screen.

## [Browser 0.3 beta](https://github.com/tintako-apps/history/releases/tag/browser-v0.3-beta) (pre-release)
Published 2026-11-06 · first released in tintako-apps/browser as v0.3-beta

Files: `Browser-0.3-beta.apk`

A calm web browser made for E Ink. Pages turn screen by screen, a reader mode keeps only the text, and there are no Google services.

**This is a beta, and testers are welcome.** If you have an E Ink device and want to help, install it and report what you find in [Issues](https://github.com/tintako-apps/browser/issues). The final version will install over the beta, so you won't end up with two apps.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J4V82A4UVG)

**What's new**
- First public beta.
- A small globe beside the address turns while a page loads and stands still when it's done.
- On https pages the globe sits inside a shield. Other pages show the globe alone.
