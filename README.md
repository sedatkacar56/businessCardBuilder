# 🧬 Card Builder Pro

**A fully browser-based, zero-dependency business card designer.**  
No installs. No sign-up. No internet required after first load. Just open and design.

Built by [Nutfah Single-Cell Omics LLC](https://nutfahsinglecellomics.com) — but free for everyone to use.

---

## ✨ Live Demo

> Just download `index.html` and open it in your browser. That's it.

Or use it directly via GitHub Pages:  
👉 **[Open Card Builder Pro](https://YOUR-USERNAME.github.io/card-builder-pro)**

---

## 📸 Screenshots

| Front Designer | Background Controls |
|---|---|
| *(add screenshot here)* | *(add screenshot here)* |

---

## 🚀 Features

### 🎨 Design
- **Front & Back** sides — switch instantly
- **Drag & drop** any element anywhere on the card
- **Double-click** text to edit inline
- **Arrow keys** to nudge elements (Shift = 10px steps)
- **Delete key** to remove selected element

### ✏️ Text
- Add any text with one click
- **9 premium fonts** (Raleway, Cormorant Garamond, Playfair Display, Montserrat, Lato, Open Sans, Georgia, Arial, Courier New)
- Font size, weight (Light / Normal / Semi-Bold / Bold)
- Bold / Italic / Underline toggles
- Letter spacing & line height sliders
- Text color picker
- **Text background** with color + opacity + padding + border radius
- **Rotation** from -180° to +180°
- Opacity control
- Z-layer (bring forward / send back)
- Exact X/Y position inputs
- Center horizontal / Center vertical buttons

### 🖼️ Images & Icons
- Upload any image (PNG, JPG, SVG, WebP)
- Resize with drag handle
- 12 built-in icons: 📞 ✉️ 🌐 📍 💼 🔬 🧬 💡 📊 🏢 📱 🔗
- Quick-insert buttons for common business info

### 🌄 Backgrounds
- **2 independent background layers** (Layer 1 = base, Layer 2 = overlay)
- Per-layer: color, opacity slider, image upload
- Per-layer image controls: **zoom**, **position X/Y**, **rotation**
- Image fit: Cover / Contain / Stretch / Original
- Layer 2 blend modes: Normal, Multiply, Screen, Overlay, Soft Light, Color Dodge
- **Gradient overlay** with 2 color pickers, angle slider, opacity

### 💾 Save & Export
- **Download PNG** — current side, at 1x / 2x / 3x resolution
- **Download both sides** at once
- **Save Project** as `.nutfah` file — preserves everything
- **Load Project** — restore a saved `.nutfah` file and continue editing
- **Auto-save** to browser localStorage every 30 seconds
- **Auto-restore** on next open if unsaved work is detected

### 🃏 Card Settings
- Custom card width & height (px)
- Border radius
- Shadow intensity
- Card border width & color
- Preset sizes: Standard (600×340), Large (700×400), 3.5×2in print size
- Zoom in/out on the designer canvas (scroll wheel or buttons)

---

## 🛠️ How to Use

### 1. Open the App
Download `index.html` and open it in **Google Chrome** or **Firefox**.  
> ⚠️ Chrome is recommended for best export quality.

### 2. Design Your Card

**Add content:**
- Click **`+ Text`** to add a text box → double-click to type
- Click **`📁 Image`** to upload your logo or photo
- Click any **icon button** (📞, ✉️, etc.) to drop it on the card
- Use **Quick Insert** buttons to add your name, email, website etc. in one click

**Style your text:**
1. Click a text element to select it
2. The **Element tab** opens automatically
3. Change font, size, color, rotation, background, etc.

**Set your background:**
1. Click the **BG tab**
2. Under **Layer 1** → pick a color OR upload an image
3. Adjust Zoom, Position X/Y, Rotation sliders to reposition
4. Enable **Gradient** for a professional gradient overlay

**Switch sides:**
- Click **▪ Front** or **▪ Back** at the bottom of the sidebar

### 3. Save Your Work

**To export as image:**
- Go to **Card tab** → set Export Scale to **2x**
- Click **💾 Download Current Side PNG**

**To save and continue later:**
- Click **💾 Save Project** at the bottom of the sidebar
- A `.nutfah` file downloads to your computer
- Next time: open `index.html` again → click **📂 Load Project** → select your `.nutfah` file

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Delete` | Delete selected element |
| `Arrow keys` | Nudge element 1px |
| `Shift + Arrow keys` | Nudge element 10px |
| `Double-click` text | Edit text inline |
| `Scroll wheel` | Zoom canvas in/out |

---

## 📁 File Structure

```
card-builder-pro/
├── index.html        ← The entire app (single file, no dependencies)
├── README.md         ← This file
├── LICENSE           ← MIT License
├── .gitignore        ← Git ignore file
└── examples/
    └── sample.nutfah ← Example project file you can load
```

---

## 🔧 Technical Details

- **100% vanilla HTML/CSS/JavaScript** — no frameworks, no build steps
- **Single file** — the entire app is `index.html`
- **One CDN dependency** — [html2canvas](https://html2canvas.hertzen.com/) for PNG export
- **Google Fonts** — loaded from CDN (works offline if fonts were cached)
- **localStorage** — used for auto-save only, nothing is sent to any server
- **No backend** — fully client-side, your designs never leave your device

---

## 🖨️ Printing Your Card

1. Export at **3x scale** for best print quality
2. Upload the PNG to one of these print services:
   - [Vistaprint.com](https://vistaprint.com) — most popular, affordable
   - [Moo.com](https://moo.com) — premium quality
   - [GotPrint.com](https://gotprint.com) — good value
3. Select **Business Card** → **Upload your design**
4. Standard size: **3.5 × 2 inches**

> **Tip:** Use the **3.5×2in preset** in the Card tab before exporting to match standard print dimensions.

---

## 🤝 Contributing

Pull requests welcome! Some ideas for contributions:
- [ ] Add more fonts
- [ ] Add shape elements (rectangles, circles, lines)
- [ ] Add QR code generator
- [ ] Add undo/redo history stack
- [ ] Add snap-to-grid feature
- [ ] Add template gallery

---

## 📄 License

MIT License — free to use, modify, and distribute.  
See [LICENSE](./LICENSE) for full text.

---

## 👤 Author

**Sedat Kacar, PhD**  
Founder, Nutfah Single-Cell Omics LLC  
🌐 [nutfahsinglecellomics.com](https://nutfahsinglecellomics.com)  
✉️ sedat@nutfahsinglecellomics.com

---

*Made with ❤️ for scientists, founders, and anyone who wants a beautiful business card without paying for design software.*
