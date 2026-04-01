# Familieopskrifter

**A family recipe app that lives in a single HTML file.**

> Live at [cyberfarfan.github.io/familie-opskrifter](https://cyberfarfan.github.io/familie-opskrifter)

---

## What is this?

A minimal Progressive Web App (PWA) for collecting and browsing family recipes. No accounts, no servers, no tracking — just recipes.

Built as a single `index.html` file with everything inline: markup, styles, and logic. Open the URL, add it to your home screen, and it works like a native app.

## How it works

| | |
|---|---|
| **Data storage** | `localStorage` in your browser — recipes stay on your device |
| **Backend** | None. It's a static file served via GitHub Pages |
| **Login** | None. No accounts, no passwords |
| **Tracking** | None. No analytics, no cookies, no third-party calls |
| **PWA support** | Full Apple meta tags — add to iPhone home screen for app-like experience |
| **Offline** | Works offline once loaded (cached by the browser) |

## For the family

Just open the link on your phone or computer. That's it.

To use it as an app on iPhone: open the link in Safari, tap the share button, and choose **Add to Home Screen**.

Recipes are stored locally on each device. The maintainer pushes updates to the app itself — your saved recipes stay on your phone.

## Tech details

- Single HTML file, zero dependencies, zero build steps
- Dark theme with warm tones, designed for mobile-first use
- Playfair Display + DM Sans typography
- CSS custom properties for theming
- Vanilla JavaScript — no frameworks
- Responsive layout with `safe-area-inset` support for modern iPhones
- Portion scaling for ingredients

## Maintained by

[@CyberFarFaN](https://github.com/CyberFarFaN)

---

*Velbekomme!*
