# 🌍 EGS Stations Map – Iframe Integration Demo

This repository provides a demonstration of how the **EGS Stations Map application** can be embedded into external websites using an iframe.

---

## 🚀 Live Demo Links

### 🔹 1. Branded Demo (Client-ready UI)
[![Open Live Demo - Blue badge with white text linking to the branded EGS Stations Map demo](https://img.shields.io/badge/Demo-Live-blue)](https://swapnilgatha.github.io/egs-map-iframe-demo/)

*(Tip: Ctrl/Cmd + Click to open in a new tab)*

**Description:**
- Fully styled UI aligned with Eurogas design
- Includes header, navigation buttons, and layout
- Demonstrates real-world embedding experience
- Suitable for client presentations

---

### 🔹 2. Fullscreen Demo (Simple Embed Test)
[![Open Live Demo - Simple - Green badge linking to the fullscreen EGS Stations Map demo](https://img.shields.io/badge/Demo-Simple-green)](https://swapnilgatha.github.io/egs-map-iframe-demo/simple.html)

*(Tip: Ctrl/Cmd + Click to open in a new tab)*

**Description:**
- Lightweight iframe-only page
- No styling or layout distractions
- Useful for testing iframe compatibility
- Helps debug embedding or header issues

---

## 🧩 How to Embed

You can embed the application in any website using the following iframe:

```html
<iframe 
  src="https://your-app.netlify.app"
  width="100%"
  height="600"
  frameborder="0">
</iframe>

```

---

## ⚙️ Requirements
To allow iframe embedding, the application must be configured with appropriate HTTP headers:
```
Content-Security-Policy: frame-ancestors *
```
