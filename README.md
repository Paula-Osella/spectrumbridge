# SpectrumBridge

Landing page for an inclusive autism integration platform.
Built with **Astro** + **Tailwind CSS** + **AOS** (scroll animations).

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or pnpm

### Installation

```bash
# 1. Navigate to the project folder
cd spectrumbridge

# 2. Install dependencies
npm install

# 3. Start development server
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

### Build for production

```bash
npm run build
npm run preview   # preview the production build locally
```

---

## 📁 Project Structure

```
spectrumbridge/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── HowItWorks.astro
│   │   ├── Benefits.astro
│   │   ├── Testimonials.astro
│   │   ├── CTA.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

---

## ♿ Accessibility Features

- WCAG 2.2 AA compliant color contrast
- Keyboard navigation with visible focus rings
- Skip-to-content link
- Screen reader friendly (ARIA labels, semantic HTML)
- `prefers-reduced-motion` respected (AOS disabled automatically)
- AAC-compatible copy and structure

## 🎨 Design Tokens

Tailwind custom colors:
- `sage` — Primary green palette (calm, natural)
- `sky` — Secondary blue palette (trust, clarity)
- `sand` — Accent warm palette (warmth, stability)
- `mist` — Neutral/grey palette (backgrounds, text)

Fonts:
- **Display:** Fraunces (serif, editorial)
- **Body:** DM Sans (clean, readable)
- **Mono:** DM Mono (labels, tags)
