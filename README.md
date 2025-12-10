# Prime Grid Visualizer

A fast and interactive **prime number grid visualizer** that runs entirely in your browser. It uses an optimized Sieve of Eratosthenes to generate primes and displays them in a color‑coded, scrollable grid.

🎨 **Prime = Green**
❌ **Composite = Red**
⬜ **Beyond n = Grey**

---

## 🔗 Live Demo

```
https://abhrankan-chakrabarti.github.io/prime-grid-visualizer/
```

---

## 🚀 Features

* Adjustable **n**, **columns**, and **cell size**
* Smooth scrolling with auto-sizing canvas
* Hover tooltip showing number + classification
* "Jump to number" navigation with highlight
* **Export grid as PNG**
* Works fully offline
* Canvas‑based rendering for high performance

---

## 📸 Screenshot

```
![Prime Grid Screenshot](screenshot.png)
```

---

## 📂 Project Structure

```
index.html   # Main application
README.md    # Documentation
```

---

## 🧠 How It Works

### 1. Prime Sieve

The app uses a fast JavaScript Sieve of Eratosthenes.

### 2. Canvas Rendering

Each number is drawn as a colored square using `<canvas>` for maximum performance.

### 3. Smooth Navigation

Jump navigation scrolls and centers the target cell and briefly highlights it.

---

## 🛠 Hosting on GitHub Pages

1. Open **Settings → Pages**
2. Set:

   * **Source:** Deploy from branch
   * **Branch:** `main`
   * **Folder:** `/root`
3. Save and open the published link.

---

## 📄 License

MIT License

---

## 👤 Author

**Abhrankan Chakrabarti**

---

## ⭐ Support the Project

If you enjoy this visualizer, leave a **star** on GitHub!
