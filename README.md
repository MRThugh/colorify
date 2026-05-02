<p align="center">
  <img 
    src="https://raw.githubusercontent.com/MRThugh/MRThugh/main/badge.svg"
    width="50%" 
  />
</p>

# 🎨 Colorify v3 Pro — Intelligent Color Palette Studio

*A place where colors are not random — they are crafted.*


![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-blue.svg)
![Language](https://img.shields.io/badge/Language-JavaScript-yellow)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen)
![Last Commit](https://img.shields.io/github/last-commit/MRThugh/Colorify)
![Repo Size](https://img.shields.io/github/repo-size/MRThugh/Colorify)
![Stars](https://img.shields.io/github/stars/MRThugh/Colorify?style=social)
![Forks](https://img.shields.io/github/forks/MRThugh/Colorify?style=social)

---

## Philosophy

*Design begins with color — Colorify helps you discover the perfect palette effortlessly.*

---

# Table of Contents

- About  
- Features  
- Getting Started  
- Usage Example  
- Tech Stack  
- Contributing  
- License  
- Author  

---

# About

**Colorify v3 Pro** is a modern browser‑based color palette generator and management tool designed for designers and developers.

It generates harmonious color palettes, analyzes accessibility contrast, and allows exporting palettes in multiple formats.

With an elegant interface, smart color generation, and built‑in analysis tools, Colorify transforms color exploration into a smooth and enjoyable experience.

---

# Features

- 🎨 **Smart Palette Generator** — create beautiful random palettes instantly  
- 🔒 **Color Locking** — keep selected colors while generating new ones  
- 📊 **Advanced Color Analysis** — luminance, hue range, and WCAG contrast  
- 📈 **Harmony Visualization** — interactive color wheel harmony chart  
- 💾 **Palette Storage** — save palettes locally with categories  
- 📦 **JSON Export / Import** — share palettes across projects  
- 🖼️ **PNG Export** — download palettes as image assets  
- 📋 **One‑Click Copy** — copy HEX colors instantly  
- 🌗 **Dark / Light Mode** — smooth theme switching  
- ⚡ **Instant Interaction** — keyboard shortcuts and animations  

---

# Getting Started

Clone the repository and open the project in your browser.

```bash
git clone https://github.com/MRThugh/colorify.git

cd colorify

# open the main file
index.html
```

That's it.

No build process.  
No dependencies to install.

Just open the file and start generating palettes.

---

# Usage Example

Generate a palette programmatically:

```javascript
function randomColor(){
  const h = randInt(0,360)
  const s = randInt(55,85)
  const l = randInt(35,70)
  return hslToHex(h,s,l)
}

palette.push(randomColor())
renderPalette()
```

*simple, fast, elegant.*

---

# Tech Stack

- ⚡ **JavaScript (Vanilla)**  
- 🎨 **TailwindCSS**  
- 🧠 **Canvas API**  
- 🌐 **HTML5**  
- 💾 **LocalStorage API**  

---

# Contributing

Contributions are welcome.

If you want to improve Colorify — whether by enhancing the UI, optimizing palette algorithms, or adding new export formats — feel free to open an issue or submit a pull request.

Creative ideas are always appreciated.

---

# License

This project is **Open Source** and released under the **MIT License**.

You are free to use, modify, and distribute it according to the license terms.

---

# Author

**Ali Kamrani**  
*The Silent Architect*  

GitHub:  
https://github.com/MRThugh

---

*Design tools come and go — but good color always remains.*
