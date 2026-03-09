# 🌍 Voices of Resilience — Refugee Life Awareness ( Also guidence for your practices and usages, you can simple follow them)

> A responsive, accessible landing page built with pure HTML5 and CSS3.  
> Created by a developer **living inside a refugee camp**, raising awareness about refugee life, resilience, and the strength of communities worldwide.

---

## 🖥️ Live Preview

<!-- Replace with your GitHub Pages URL after deploying -->
🔗 **[View Live Site](https://github.com/faisel-234/Responsive-Landing-Page)**

---


## 📁 Project Structure

```
refugee-life-awareness/
│
├── index.html          ← Main landing page (all sections)
├── css/
│   └── style.css       ← Complete stylesheet (700+ lines, well-commented)
│   ─ ( photos)   ← Add your own photos here
└── README.md           ← This file
```

---

## ✨ Features

- ✅ **Pure HTML5 + CSS3** — no JavaScript, no frameworks, no libraries
- ✅ **Mobile-first responsive design** — works on all screen sizes
- ✅ **CSS-only hamburger menu** — mobile nav without a single line of JS
- ✅ **Accessible** — semantic HTML, ARIA labels, keyboard navigation, focus rings
- ✅ **CSS custom properties** (variables) for easy theming
- ✅ **CSS animations** — fade-in, float, stagger — all CSS only
- ✅ **7 complete sections** — Nav, Hero, About, Stories, Challenges, Community, CTA, Footer
- ✅ **Well-commented code** — beginner-friendly and production-structured

---

## 🎨 Design Choices

| Element       | Choice                          | Why                                  |
|---------------|---------------------------------|--------------------------------------|
| Font (headings) | Playfair Display (serif)       | Dignified, editorial, human warmth   |
| Font (body)   | Nunito (sans-serif)             | Readable, friendly, modern           |
| Colors        | Navy + Warm Sand + Terracotta   | Humanitarian warmth, not corporate   |
| Layout        | Flexbox + CSS Grid              | Clean, responsive, semantic          |
| Style         | NGO / editorial minimal         | Honest and human, not flashy         |

---

## 📐 Sections

1. **Navigation Bar** — Sticky top nav, CSS-only mobile hamburger menu
2. **Hero Section** — Big headline, description, two CTA buttons, image + stat badge
3. **About Refugee Life** — Two-column layout, text + image, floating stat card
4. **Daily Life / Stories** — 3 story cards with image placeholders + hover effects
5. **Challenges Section** — 6 icon cards on dark navy background
6. **Community Strength** — Two-column layout showing resilience and solidarity
7. **Call to Action** — Dark gradient section with a pull quote by Warsan Shire
8. **Footer** — 4-column grid, links, social placeholders, copyright

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout                        |
|------------|-------------------------------|
| `< 768px`  | Mobile — single column, hamburger menu |
| `≥ 768px`  | Tablet — 2 columns, horizontal nav  |
| `≥ 1024px` | Desktop — 3 columns, full layout    |
| `≥ 1280px` | Large desktop — max-width, wider spacing |

---

## 🚀 How to Run Locally

No build tools needed. Just open the file:

```bash
# Clone the repo
git clone https://github.com/your-username/refugee-life-awareness.git

# Open in browser
cd refugee-life-awareness
open index.html     # macOS
# or double-click index.html on Windows/Linux
```

---


## 🖼️ Adding Your Own Photos

Each image placeholder in the HTML has a comment telling you exactly what photo to add and where:

```html
<!--
  IMAGE PLACEHOLDER — Hero
  Replace with your own photo later.
  Suggested: A wide camp landscape or a portrait at dawn.
  <img src="images/hero-photo.jpg" alt="Morning light at the camp" />
-->
<div class="img-placeholder img-placeholder--hero">
```

**To replace a placeholder:**
1. Copy your photo to the `images/` folder
2. Replace the `<div class="img-placeholder ...">` block with:
   ```html
   <img src="images/your-photo-name.jpg" alt="Descriptive alt text" class="section-img" />
   ```
3. Add this to your CSS:
   ```css
   .section-img {
     width: 100%;
     height: 100%;
     object-fit: cover;
     border-radius: 12px;
   }
   ```

---

## ♿ Accessibility

This project follows accessibility best practices:

- Semantic HTML (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- `aria-label` and `aria-labelledby` attributes throughout
- Visible focus indicators for keyboard navigation
- `prefers-reduced-motion` media query respected
- `forced-colors` (high contrast mode) support
- Alt text on all image placeholders
- Color contrast ratios meet WCAG AA standards

---

## 🛠️ Tech Stack

```
HTML5      ████████████████████  100%
CSS3       ████████████████████  100%
JavaScript ░░░░░░░░░░░░░░░░░░░░  0%   (intentionally — none used!)
```

---

## 👤 About the Developer

This project was built by a developer named Noor Faisel living inside a refugee camp in Bangladesh.

The goal is not just to demonstrate front-end skills — it is to tell a real human story through code, because technology can be a voice for those who are rarely heard.

> *"I built this with my own hands, from inside a camp, to show the world that talent and ambition survive displacement."*

---

## 📄 License

## License
The code in this project is open-source under the MIT License.  
Images and personal stories © Noor Faisel and should not be reused without permission.
Some images are public and can be used anyway.
You are free to use the code, modify, and share — please give credit.

---

## 🤝 Contributing

If you'd like to suggest improvements or translations into other languages, feel free to open an issue or pull request.

---

*Built with HTML, CSS, and purpose. No frameworks — just humanity.*
