# 📖 Holy Quran – Chapters Web App

A simple, fast, SEO-optimised directory of the first 30 Quran chapters hosted at **quran.akibworks.in**.  
Click any card to open the chapter PDF in a new browser tab.

---

## 📁 Project Structure

```
quran/
├── index.html          ← Main page (SEO-complete, all chapter cards)
├── robots.txt          ← Search-engine crawl rules
├── sitemap.xml         ← XML Sitemap
├── pdf/                ← PDF files  (1.pdf … 30.pdf)
└── thumbnail/          ← WebP thumbnails (1.webp … 30.webp)
```

---

## 🖥️ Run Locally

This is a pure static website. You don’t need any build tools, databases, or frameworks to run it.

Because everything is embedded directly using HTML, CSS (Tailwind CDN), and Vanilla JS, you don't even need a local server.

Simply double-click the `index.html` file to open it in your browser!

---

## 🚀 Deploy to Smilehostie (or any static host)

Since this app is purely static (HTML, CSS, JS, Images, PDFs), deploying it to shared hosting like Smilehostie (via cPanel or DirectAdmin) is extremely simple.

### Option A: Using the File Manager (Easiest)

1. Log in to your Smilehostie control panel.
2. Navigate to **File Manager**.
3. Open the `public_html` directory (or the root folder for your `quran.akibworks.in` domain).
4. Compress all files in your local `quran` folder into a single `.zip` file (do not zip the folder itself, zip the _contents_ inside it).
5. **Upload** the `.zip` file into the `public_html` folder.
6. **Extract** the `.zip` file.
7. You should now see `index.html`, the `pdf/` folder, etc., directly inside `public_html`.
8. Delete the `.zip` file to save space.
9. Visit `https://quran.akibworks.in` to see your live site!

### Option B: Using FTP

1. Open your FTP client (like FileZilla).
2. Connect to your Smilehostie FTP account.
3. Open the `public_html` folder on the remote server.
4. Drag and drop all the contents of your local `quran` folder into `public_html`.

---

## 🔍 SEO Checklist

| Item                                                           | Status |
| -------------------------------------------------------------- | ------ |
| `<title>` tag                                                  | ✅     |
| `<meta description>`                                           | ✅     |
| Open Graph tags                                                | ✅     |
| Twitter Card tags                                              | ✅     |
| JSON-LD structured data                                        | ✅     |
| Semantic HTML (`<header>`, `<main>`, `<section>`, `<article>`) | ✅     |
| Alt text on all images                                         | ✅     |
| `robots.txt`                                                   | ✅     |
| `sitemap.xml`                                                  | ✅     |
| Lazy-loaded thumbnails                                         | ✅     |
| Canonical URL                                                  | ✅     |

---

## ♿ Accessibility

- Keyboard navigation (Tab + Enter/Space to open PDFs)
- Screen reader labels (`aria-label`, `role`, `<label>`)
- High-contrast text
- Large tap targets (mobile-first)
- `lang="en"` on `<html>`

---

## ⚡ Performance

- No JavaScript framework (< 3 KB of JS)
- Tailwind CSS via CDN (cached by browser across sites)
- WebP thumbnails with lazy loading

---

## 📝 License

© AkibWorks. All rights reserved.
