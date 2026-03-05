# ✦ AR Gallery

A **universal marker-based AR gallery** that works in any modern smartphone browser — no app install required.

🔗 **Live Demo:** [https://tcode-motion.github.io/ar-photo/](https://tcode-motion.github.io/ar-photo/)

📦 **Repository:** [https://github.com/Tcode-Motion/ar-photo](https://github.com/Tcode-Motion/ar-photo)

---

## 📱 How to Use

1. **Open the live link** on your phone: [tcode-motion.github.io/ar-photo](https://tcode-motion.github.io/ar-photo/)
2. **Open the Hiro Marker** on your PC browser:  
   👉 [https://ar-js-org.github.io/AR.js/data/images/HIRO.jpg](https://ar-js-org.github.io/AR.js/data/images/HIRO.jpg)
3. Tap **"Launch Camera"** on your phone and **allow camera access**.
4. **Point your phone camera** at the Hiro marker on your PC screen.
5. The AR gallery will appear floating on the marker!

---

## 🖼️ Features

| Feature | Description |
|---|---|
| **Single Mode** | Browse photos one at a time with Prev / Next |
| **Gallery Mode** | All 5 photos displayed in a fan arrangement |
| **Ultra Stable** | Advanced 30-frame smoothing — no hand-shake jitter |
| **Universal** | Works on Android & iOS — any phone, any browser |
| **No App Needed** | 100% web-based, zero install |

---

## 📂 Project Structure

```
ar-photo/
├── index.html          ← Main app (single file, no build)
├── images/
│   ├── photo1.jpg      ← Personal photo
│   ├── gallery1.png    ← Mountain Lake
│   ├── gallery2.png    ← Abstract Art
│   ├── gallery3.png    ← Cyberpunk City
│   └── gallery4.png    ← Architecture
├── README.md
└── .nojekyll
```

---

## ➕ Adding Your Own Photos

1. Put your image into the `images/` folder.
2. In `index.html`, add inside `<a-assets>`:
   ```html
   <img id="img5" src="images/your-photo.jpg" crossorigin="anonymous">
   ```
3. Add it to the gallery ring `<a-entity id="galleryRing">`.
4. Update the `IMAGE_IDS` and `IMAGE_NAMES` arrays in `<script>`.

---

## 🛠️ Tech Stack

- [A-Frame 1.3](https://aframe.io/) — WebXR / 3D scene framework
- [AR.js](https://ar-js-org.github.io/AR.js-Docs/) — Marker-based AR in the browser
- No build tools, no backend, no app install.

---

## 📄 License

MIT — free to use and modify.
