# 🏠 PropSplit

**The MLS & Social Real Estate Photo Splitter**

A zero-server, privacy-first web application that solves the double-export bottleneck for real estate professionals. Process property photos into two optimized variants simultaneously:

- **MLS Clean** → EXIF/GPS stripped, uniformly resized, zero watermarks
- **Social Branded** → Logo, agent headshot, contact text, color enhancements

## ✨ Features

### Core Processing
- 🔒 **100% Client-Side** — No uploads, complete privacy, works offline
- ⚡ **Parallel Batch Processing** — Handle dozens of high-res photos simultaneously
- 📦 **Dual-ZIP Export** — One click generates `MLS_Clean_Ready/` + `Social_Branded_Ready/`

### MLS Pipeline
- Automatic EXIF/GPS metadata sanitization
- Uniform resize to listing-friendly resolutions (1024×768, 1280×960, 1920×1080, 1600×1200)
- Clean output guaranteed — no watermarks or branding

### Social Pipeline
- **Agency Logo** — Upload PNG/SVG, adjustable opacity & scale, free drag positioning
- **Agent Headshot** — Circle/rounded/square/free shapes, border customization, supports transparent PNGs
- **Contact Text** — Company name + contact info with shadow effects
- **Photo Enhancements** — Sky/Color Boost, Golden Hour Warmth, Brightness, Contrast
- **Aspect Ratios** — Original, 1:1, 4:5 (Instagram), 9:16 (Stories/Reels), 16:9
- **Image Repositioning** — Drag or slider controls to frame the perfect crop

### UI/UX
- 🎨 Cinematic dual-viewport preview (MLS left, Social right)
- 🌙 Dark/Light theme toggle
- 🌐 English/Italian language switcher
- 📱 Responsive design

## 🚀 Usage

1. Open `index.html` in any modern browser
2. Drop property photos
3. Upload logo and/or agent headshot (PNG with transparent BG recommended)
4. Adjust branding positions, enhancements, aspect ratio
5. Click "Export Dual-ZIP Pack"
6. Done — two folders, ready for MLS upload and social posting

## 🛠️ Tech Stack

- HTML5 Canvas API
- Vanilla JavaScript (ES6+)
- CSS3 with CSS Variables
- JSZip (CDN)
- Zero dependencies, single file

## 📄 License

MIT
