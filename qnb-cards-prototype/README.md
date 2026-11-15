# Cards screen — interactive prototype

An interactive, mobile-first prototype of a debit cards screen for a banking app (Arabic, RTL).

> **Unofficial concept.** Not affiliated with or endorsed by QNB. All names, numbers and transactions are fictional.

## Run it

Open `index.html` in any modern browser. It is a single self-contained file (fonts, icons and images are embedded), so it works offline.

- **Phone:** opens full-screen. Best viewed on a real device.
- **Desktop:** shows the screen inside a phone frame.

## What to try

- **Swipe between cards** (or use the ← → keys). The header color, accent, balance, limit and transactions follow the active card.
- **Tap the active card** or **عرض البيانات** to lift and flip it and see the card details. They hide again after 20 seconds.
- **تجميد** freezes the card (frost, snow and a status flip); tap again to unfreeze.
- **الرقم السري** reveals the PIN digit by digit, then hides it after 10 seconds.
- **الإعدادات** opens card controls and a daily-limit slider that updates the spending bar live.

## Built with

Plain HTML, CSS and JavaScript, no framework. Fonts: IBM Plex Sans Arabic and Inter (falls back from thmanyah sans / Inter Display when those aren't installed). Icons: Phosphor.

Design and prototype by Ahmed Tarek.
