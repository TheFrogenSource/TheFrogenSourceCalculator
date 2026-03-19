# 🐸 Frogen Calculator

A modern, minimalist, and multilingual calculator designed specifically for the **GNOME 40+** ecosystem. Built with Electron and styled following **Libadwaita** design principles.

## ✨ Features

- **Universal Interface**: Uses standard mathematical symbols and icons to be usable in any language without translation.
- **GNOME Integration**: Automatically adapts to system Light and Dark mode preferences.
- **Audio Feedback**: Features satisfying UI sound effects on button presses.
- **Linux Ready**: Optimized for Linux Mint, Ubuntu, and other GNOME-based distributions.

## 🛠️ Installation & Build

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (included with Node.js)

### Local Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/TheFrogenSource/TheFrogenSourceCalculator.git
   cd TheFrogenSourceCalculator
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Development

To run the calculator in development mode:

```bash
npm start
```

### Build AppImage

To generate a standalone executable for Linux:

```bash
npm run dist
```

The resulting `.AppImage` file will be located in the `dist/` directory.

## 🎵 Credits & Assets

- **Sound Effects**: Created by [Kenney](https://kenney.nl/) under the [CC0 1.0 License](https://creativecommons.org/publicdomain/zero/1.0/).
- **Application Icon**: Based on a Public Domain SVG and edited for this project. [Here] (https://www.svgrepo.com/svg/485651/calculator)

## 📜 License

This project is licensed under the [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.html). See the `LICENSE` file for the full text.

---

## ⚖️ Legal Notice
This application is built using **Electron**, which bundle components of **Chromium** and **Node.js**. 
These components are licensed under various open-source licenses (MIT, BSD, etc.). 
The source code of this calculator is licensed under **GPL-3.0**.
