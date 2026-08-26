# MathSprint — Installable PWA

This is the PWA version of MathSprint.

## Android installation
1. Host this folder on an HTTPS website.
2. Open the website in Chrome on Android.
3. Choose **Install app** or **Add to Home screen**.
4. MathSprint will appear with its own icon and open in standalone app mode.

A normal `file://` HTML file is not enough for standard PWA installation. HTTPS is required for deployment; localhost is suitable for development.

## Files
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png
