# KCORO — NFT & Digital Art Platform

> **Unleash Digital Creativity** — A collection of landing page projects built with pure HTML and CSS, focusing on responsive design, CSS animations, and clean UI.

---

## 🔗 Links

| Resource | URL |
|---|---|
| 🎨 **Figma Design File** | [View on Figma →](https://www.figma.com/design/j7BWZsPNiutaLusuRrWkqL/HTML-CSS-Layout?node-id=78-903) |

---

## 📸 Preview

![KCORO Hero Section](./IMG/kcoro_preview.png)

---

## 📁 Project Structure

```
KCORO_website/
├── index.html            # Markup — original structure + CSS-only hamburger toggle
├── styles.css            # All styles: base · animations · responsive
└── IMG/
    ├── desktop.png       # Hero 3D illustration
    ├── phone.png         # Trading feature illustration
    ├── smart_insight.png # Analytics feature illustration
    ├── sofia.png         # Testimonial — Sofia Rodriguez
    ├── rahul.png         # Testimonial — Rahul Kapoor
    ├── emma.png          # Testimonial — Emma Thompson
    ├── techcrunch.png    # Press logo
    ├── fastcompany.png   # Press logo
    ├── mit.png           # Press logo
    ├── forbes.png        # Press logo
    └── bg-grad.svg       # Background radial gradient overlay
```

---

## ✨ Features

### CSS-Only Animations
All motion is written entirely in CSS — zero JavaScript animation libraries.

| Element | Animation | Trigger |
|---|---|---|
| Hero image | Floating up/down | Page load · infinite |
| Brand logos | Fade + slide up (staggered) | Page load |
| Buttons | Lift + glow + shine sweep | Hover |
| Nav links | Underline draws left → right | Hover |
| Brand logos | Greyscale → colour + scale | Hover |
| Feature images | Zoom + rotate | Hover |
| Testimonial cards | Lift + glowing gradient border | Hover |
| Footer links | Slide right + opacity | Hover |
| Newsletter input | Purple focus ring | Focus-within |

### CSS-Only Mobile Menu
The hamburger uses a hidden `<input type="checkbox">` + `<label>` pattern. The `:checked` pseudo-class drives open/close state and animates the burger icon into an ✕ — no JavaScript required.

### Responsive Breakpoints

| Breakpoint | Changes |
|---|---|
| `> 1024px` | Full desktop layout |
| `≤ 1024px` | Tighter gaps, nav links compress, footer padding adjusts |
| `≤ 768px` | Hero stacks vertically · features stack · testimonials single-column · footer column |
| `≤ 480px` | Hamburger menu · full-width buttons · footer links in 2-col grid · all sections single-column |

---

## 🎨 Design Tokens

| Token | Value |
|---|---|
| `--bg-color` | `#2d0070` |
| `--primary-color` | `#9f3ee7` |
| `--foreground-color` | `#ffffff` |
| Card background | `#3e057f` |
| Footer background | `linear-gradient(135deg, #1a003d, #0d001f)` |
| Heading font | Outfit (Google Fonts) |
| Body font | Roboto (Google Fonts) |

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup, no frameworks
- **CSS3** — custom properties · flexbox · grid · `@keyframes` · `@media` · `:checked` toggle
- **Zero JavaScript** — all animations and mobile nav are pure CSS
- **Google Fonts** — Outfit + Roboto + Cabin

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/Latwal2004/Landing-Pages-Practice-HTML-CSS-git

# 2. Navigate into the project folder
cd Landing-Pages-Practice-HTML-CSS-

# 3.In This Repo Open KCORO Project Open in browser — no build step needed.
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or install the **Live Server** extension in VS Code and click **Go Live**.

---

## 📄 License

MIT — free to use and modify.