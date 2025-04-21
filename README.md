# 🖼️ Image Resizer & Converter

A lightweight, browser-based tool to **resize** and **convert images** without uploading them anywhere.  
Perfect for quick editing, compression, or format changes — all client-side with no dependencies.

## 🚀 Features

- Resize images by width and height
- Maintain aspect ratio (optional)
- Convert to: **Original**, **PNG**, **JPG**, **WEBP**
- Adjust output **quality** (JPEG / WebP only)
- Drag & drop support
- Preview and download the result
- Display before/after dimensions and file size

## 📺 Live Demo

🔗 [View on GitHub Pages](https://dreamerview.github.io/imagify/)

## 🛠️ How to Use

1. Download or clone the repository
2. Open `index.html` in any modern browser
3. Upload or drag an image into the tool
4. Set the desired width, height, format, and quality
5. Click **Start Resize** to generate and download the image

## ✅ Supported Output Formats

| Format | Supported | Notes                             |
|--------|-----------|-----------------------------------|
| PNG    | ✅         | Transparent background supported  |
| JPG    | ✅         | Supports quality adjustment       |
| WEBP   | ✅         | Smaller size, good for web        |
| GIF    | ❌         | Not supported by canvas API       |
| BMP    | ❌         | Not supported by canvas API       |

> ⚠️ GIF and BMP export are not supported in modern browsers using `canvas.toDataURL()`.

## 📄 License

MIT — Free to use, modify, and distribute.
