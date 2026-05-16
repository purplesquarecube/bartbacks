[Bart Backs]

# Bart Backs v1.3

Just a .html file of Bart Backs. Open in browser.
I will be working on versions for different operating systems.

**CODE TO GET IN: 9745**

**LINK TO PLAY WITHOUT DOWNLOAD:** https://2703492.playcode.io

## What's New in v1.3.1
- 🌈 Rainbow Barts (0.5% spawn chance, 50x bonus points!)
- 🎭 4 New character skins: Maggie, Homer, Lisa, Bartman
- 🏫 New location: Springfield Elementary (x5,000 multiplier)
- ☢️ New location: Nuclear Plant (x25,000 multiplier)
- 💦 New UI: Liquid Glass
 # BartBacks AppImage Build

## Build Instructions

### 1. Install dependencies

```bash
npm install
```

### 2. Build the AppImage

```bash
npm run build
```

### 3. Find the AppImage

The compiled AppImage will appear in:

```bash
dist/
```

Example:

```bash
dist/BartBacks-1.0.0.AppImage
```

### 4. Run the AppImage

```bash
chmod +x dist/BartBacks-1.0.0.AppImage
./dist/BartBacks-1.0.0.AppImage
```

---

## Requirements

- Linux
- Node.js 20+
- npm

---

## Install Node.js

https://nodejs.org

---

## GitHub Actions

This repo includes a GitHub Actions workflow that automatically builds the AppImage on push.
