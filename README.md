# Nexon — Modern Infrastructure Platform

**DecodeLabs Frontend Development Internship — Project 1**
Batch 2026

A fully responsive landing page built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no external UI libraries. Built to demonstrate a polished, production-quality frontend with dark-mode aesthetics, fluid layouts, and accessible markup.


---

## 🎯 Project Goal

Build a high-quality, responsive landing page for a fictional infrastructure platform — demonstrating semantic HTML, a custom design system with CSS variables, multi-column grid layouts, and an accessible mobile navigation — all without relying on any CSS or JS frameworks.

## ✨ Features

- **Responsive layout** — adapts from a single-column mobile view to a full multi-column desktop layout via a `max-width: 768px` media query
- **CSS Grid** for macro page layout (features grid, about section, contact form layout)
- **Flexbox** for component-level alignment (header bar, footer, buttons, nav)
- **Custom design system** — CSS Custom Properties for colors, spacing, typography, and transitions, all defined in a single `:root` block
- **Vanilla JS hamburger navigation** — lightweight DOM toggle for the mobile menu with a fluid backdrop blur effect
- **Custom local font** — `Daytona` (light, regular, bold) loaded via `@font-face` with `font-display: swap` for performance
- **Accessible by default** — semantic HTML5 elements, explicit `aria-*` attributes, visible focus rings, and screen-reader-only utility class (`.sr-only`)

## 🛠️ Tech Stack

- HTML5 (semantic markup)
- CSS3 (Grid, Flexbox, Custom Properties, keyframe animations, media queries)
- JavaScript (vanilla — DOM manipulation for mobile nav toggle only)
- Custom local fonts (`Daytona` — woff2)
- Zero CSS frameworks, zero JS libraries

## 📁 Project Structure

```
├── index.html          # Page structure and content
├── master.css          # All styling — design tokens, layout, responsiveness
├── fonts/              # Local font assets
│   ├── daytona-light.woff2
│   ├── daytona-regular.woff2
│   └── daytona-bold.woff2
└── README.md
```

## 📱 Responsive Breakpoints

| Breakpoint | Behavior |
|---|---|
| `> 768px` (default) | Multi-column desktop layout, desktop nav visible |
| `≤ 768px` | Single column, stacked layout, hamburger menu replaces desktop nav |

## 🚀 Running Locally

No build step or dependencies required.

1. Clone the repo:
   ```bash
   git clone https://github.com/KaPu-24/decodelabs_p1.git
   ```
2. Open `index.html` directly in a browser, or serve it locally:
   ```bash
   npx serve .
   ```

## 👤 Author

Built as part of the DecodeLabs Frontend Development Internship, Batch 2026.