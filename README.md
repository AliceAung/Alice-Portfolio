# 🌹 Alice Aung — Portfolio Website

A premium, multi-page portfolio website for **Alice Aung (Ku Mudra Aung)** — a Marketing & Business Development professional. Built with [Astro.js](https://astro.build) and styled with a warm **Rose Tanned** color theme.

## ✨ Features

- 🌸 **Rose Tanned Design System** — Warm rose, blush, and tan palette with glassmorphic effects
- 📱 **Fully Responsive** — Optimized for desktop, tablet, and mobile
- 🎨 **Premium Aesthetics** — Gradient text, floating animations, card hover effects, micro-interactions
- 🔤 **Modern Typography** — Inter + Playfair Display from Google Fonts
- 📝 **Blog with MDX** — Markdown & MDX support for content authoring
- 🗺️ **SEO-Friendly** — Canonical URLs, Open Graph, Twitter cards, sitemap, RSS feed
- ⚡ **100/100 Lighthouse** — Static site generation for blazing-fast performance

## 📄 Pages

| Page | Route | Description |
|------|-------|-------------|
| **Home** | `/` | Hero section, skills grid, featured projects, testimonials, blog preview |
| **About** | `/about` | Professional bio, career timeline, skills & expertise, education |
| **Portfolio** | `/portfolio` | Filterable project showcase with process methodology |
| **Blog** | `/blog` | Featured post hero, article cards, individual post pages |
| **Contact** | `/contact` | Contact form, info cards, availability status |

## 🚀 Project Structure

```text
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/             # Images (profile photo, portfolio covers, blog placeholders)
│   ├── components/
│   │   ├── BaseHead.astro       # <head> with meta tags & fonts
│   │   ├── Header.astro         # Glassmorphic navbar + mobile menu
│   │   ├── Footer.astro         # Multi-column footer
│   │   ├── HeaderLink.astro     # Nav link with animated underline
│   │   ├── HeroSection.astro    # Homepage hero with photo & stats
│   │   ├── SkillsSection.astro  # 6-card skills/services grid
│   │   ├── TestimonialsSection.astro  # Client testimonials
│   │   ├── PortfolioCard.astro  # Reusable project card
│   │   ├── ContactForm.astro    # Styled contact form
│   │   └── FormattedDate.astro  # Date formatter
│   ├── content/
│   │   └── blog/            # Markdown & MDX blog posts
│   ├── layouts/
│   │   └── BlogPost.astro   # Blog post layout
│   ├── pages/
│   │   ├── index.astro      # Home
│   │   ├── about.astro      # About
│   │   ├── portfolio.astro  # Portfolio
│   │   ├── contact.astro    # Contact
│   │   ├── blog/
│   │   │   ├── index.astro       # Blog listing
│   │   │   └── [...slug].astro   # Dynamic blog post
│   │   └── rss.xml.js       # RSS feed
│   ├── styles/
│   │   └── global.css       # Rose Tanned design system
│   ├── consts.ts            # Site title & description
│   └── content.config.ts    # Content collection schema
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🎨 Color Theme — Rose Tanned

| Token | Hex | Usage |
|-------|-----|-------|
| `--rose-400` | `#fb7185` | Primary accent, CTA buttons |
| `--rose-500` | `#f43f5e` | Bold accent, active states |
| `--rose-600` | `#e11d48` | Deep accent, links |
| `--tan-50` | `#fdf8f4` | Page background |
| `--tan-100` | `#f5ebe0` | Secondary background |
| `--text-primary` | `#2d2024` | Headings |
| `--text-secondary` | `#6b5560` | Body text |

## 🧞 Commands

All commands are run from the root of the project:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`       |
| `npm run build`           | Build production site to `./dist/`               |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 🛠️ Tech Stack

- **Framework**: [Astro v6](https://astro.build)
- **Content**: Markdown & [MDX](https://mdxjs.com/)
- **Styling**: Vanilla CSS with custom properties
- **Fonts**: [Inter](https://fonts.google.com/specimen/Inter) & [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) via Google Fonts
- **Integrations**: `@astrojs/mdx`, `@astrojs/sitemap`, `@astrojs/rss`
- **Image Optimization**: [Sharp](https://sharp.pixelplumbing.com/)

## 📝 License

This project is based on the [Astro Blog Starter](https://github.com/withastro/astro/tree/main/examples/blog) template, originally inspired by [Bear Blog](https://github.com/HermanMartinus/bearblog/).
