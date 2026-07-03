# 🏠 PropSplit

**The MLS & Social Real Estate Photo Splitter**

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![JSZip](https://img.shields.io/badge/JSZip-Compression-orange)
![Offline](https://img.shields.io/badge/Works-Offline-success)
![No Server](https://img.shields.io/badge/Server-None_Required-critical)

---

<p align="center">
  <img src="https://img.shields.io/badge/🔒_100%25_Privacy-Client_Side_Only-black?style=for-the-badge" alt="Privacy First"/>
  <img src="https://img.shields.io/badge/☕_Support-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi"/>
</p>

---

## 🎯 The Problem

Real estate agencies need to publish the same photos to two channels with **opposite requirements**:

| MLS / Listing Portals | Social Media |
|-----------------------|--------------|
| ❌ No watermarks | ✅ Logo & branding required |
| ❌ No metadata | ✅ Agent contact info |
| ✅ Standard dimensions | ✅ Platform-specific ratios |
| ✅ Clean, professional | ✅ Enhanced, eye-catching |

**Result?** Hours of manual Photoshop work for every property.

---

## ✨ The Solution

**PropSplit** processes a batch of photos and generates **two ready-to-use folders** in a single click:

```
📦 PropSplit_Export.zip
├── 📁 MLS_Clean_Ready/
│   ├── living-room_MLS.jpg      ← EXIF stripped, resized, clean
│   ├── kitchen_MLS.jpg
│   └── exterior_MLS.jpg
│
└── 📁 Social_Branded_Ready/
    ├── living-room_Social.jpg   ← Logo, headshot, filters applied
    ├── kitchen_Social.jpg
    └── exterior_Social.jpg
```

**From 45+ minutes of manual work → 30 seconds.**

---

## 🖥️ Screenshot

<p align="center">
  <i>Dual-viewport workspace: MLS preview (left) + Social branded preview (right)</i>
</p>

<!-- Add your screenshot here -->
<!-- ![PropSplit Screenshot](screenshot.png) -->

---

## 🚀 Features

### 📸 MLS Pipeline
- ✅ Automatic **EXIF/GPS metadata removal**
- ✅ Uniform resize to listing standards (1024×768, 1280×960, 1920×1080, 1600×1200)
- ✅ **Zero watermarks** guaranteed
- ✅ JPEG/PNG/WebP output with quality control

### 🎨 Social Pipeline
- ✅ **Agency Logo** — PNG/SVG upload, adjustable opacity & scale
- ✅ **Agent Headshot** — Circle/rounded/square/free shapes, transparent PNG support
- ✅ **Contact Text** — Company name + contact info with shadow effects
- ✅ **Photo Enhancements** — Sky Boost, Golden Hour Warmth, Brightness, Contrast
- ✅ **Aspect Ratios** — Original, 1:1, 4:5 (Instagram), 9:16 (Stories/Reels), 16:9
- ✅ **Drag & Drop Positioning** — Place elements anywhere on the canvas
- ✅ **Image Pan** — Reframe cropped photos with drag or sliders

### ⚡ Technical
- 🔒 **100% Client-Side** — No uploads, complete privacy, works offline
- 🚀 **Parallel Batch Processing** — Process dozens of high-res photos simultaneously
- 📦 **Dual-ZIP Export** — One click, two organized folders
- 🌙 **Dark/Light Theme**
- 🌐 **English/Italian** language switcher

---

## 📖 How to Use

1. **Open** `index.html` in any modern browser
2. **Drop** your property photos
3. **Upload** logo and/or agent headshot *(PNG with transparent background recommended)*
4. **Adjust** positions, filters, aspect ratio as needed
5. **Click** "Export Dual-ZIP Pack"
6. **Done** — Two folders ready for MLS upload and social posting

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 Canvas | Image processing engine |
| Vanilla JavaScript (ES6+) | Zero dependencies, maximum performance |
| CSS3 + CSS Variables | Theming & responsive design |
| JSZip (CDN) | Client-side ZIP generation |

**Single file. No build step. No npm. No server.**

---

## 📁 Project Structure

```
propsplit/
├── index.html    ← The entire application (single file)
├── README.md     ← You are here
└── LICENSE       ← MIT License
```

---

## 🚀 Deployment

### GitHub Pages (Free)

1. Push to GitHub
2. Go to **Settings → Pages**
3. Select **Branch: main** → **/ (root)**
4. Your app is live at `https://yourusername.github.io/propsplit/`

### Any Static Host

Just upload `index.html`. That's it.

Works on: **Netlify, Vercel, Cloudflare Pages, Firebase Hosting, AWS S3, or any web server.**

---

## 📄 License

```
MIT License

Copyright (c) 2025 Noemi Marcolini

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## ☕ Support

**PropSplit** is free and open source.

If it saved you time, consider buying me a coffee:

<p align="center">
  <a href="https://ko-fi.com/noemimarcolini" target="_blank">
    <img src="https://img.shields.io/badge/☕_Buy_me_a_coffee-€1-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi"/>
  </a>
</p>

---

## 🤝 Contributing

Found a bug? Have a feature idea?

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 👤 Author

**Noemi Marcolini**

- Ko-fi: [@noemimarcolini](https://ko-fi.com/noemimarcolini)
- GitHub: [@noemimarcolini](https://github.com/noemimarcolini)

---

<p align="center">
  Made with ❤️ for real estate professionals
</p>
