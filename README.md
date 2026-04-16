# OpenForge

A no-code website builder that runs entirely in your browser.  
**One file · Zero dependencies · Zero server**

Try here : https://openforge-4ih.pages.dev/

---

## 📄 License

MIT License

---

## ✨ Features

- 🧱 **Block editor** — drag & drop ready-made sections (hero, features, articles, CTA…)
- 📄 **Multi-page support** — manage multiple pages within a single project
- 📁 **Multi-project support** — switch between projects, everything is saved locally
- ✏️ **Rich editor** — WYSIWYG mode and raw HTML mode in the same interface
- 🔤 **30+ Google Fonts** — typography panel with font pairing suggestions
- 🎨 **Palette & CSS** — color editor + custom CSS injection
- 🖼 **Asset manager** — drag & drop images, automatic WebP compression
- 📰 **Article system** — categories, tags, slug, featured image, excerpt
- 🌐 **Favicons** — import a favicon.io ZIP directly
- 📱 **Responsive preview** — desktop, tablet, mobile
- 📤 **HTML export** — download a clean, standalone HTML file
- 📥 **Import** — load an existing HTML file or a JSON project
- 💾 **Zero backend** — everything is stored in `localStorage`

---

## 🚀 Quick Start

No installation required.

1. Download `index.html`
2. Open it in your browser
3. Start building

**Compatible with:** Chrome, Firefox, Safari, Edge (recent versions)

---

## 🏗 Architecture

OpenForge is a single HTML file (~6,500 lines) with no external dependencies or frameworks.

It relies on:

- `localStorage` → project persistence
- Canvas API → client-side image compression (automatic WebP conversion)
- Google Fonts → dynamic font loading
- Sandboxed iframe → isolated rendering of the editor canvas

---

## 🗺 Roadmap

- [ ] Multi-page export (ZIP)
- [ ] Predefined startup themes
- [ ] Global undo/redo history
- [ ] Dark mode for exported pages
- [ ] Project templates

---

## 🤝 Contribution

Contributions are welcome.

```bash
# Fork the repository
git checkout -b feature/my-feature
git commit -m "feat: add X"
git push origin feature/my-feature
