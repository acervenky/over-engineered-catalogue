# 🌐 Over Engineered by Venky — Portfolio Page

### *The Unnecessarily Elaborate Project Index*

A static GitHub Pages portfolio for the **Over Engineered by Venky** series — because a plain list of GitHub links would have been proportionate, and proportionality is not the brand.

---

**Part of the *Over Engineered by Venky* Series**

> *Need a portfolio page? Sure, a pinned README would work. But why not build a single-file amber-glow retro-terminal HTML page with CRT scanlines, Bebas Neue headers, staggered scroll animations, a real-time AI review section sourced from Claude Opus, Gemini 3.1 Pro, and ChatGPT, and a terminal log that prints their verdicts like a system boot sequence? Every project in this series exists because "but I could over-engineer that" is a lifestyle. Efficiency? Optional. Style points? Mandatory.*

---

[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)](#)
[![Type](https://img.shields.io/badge/Type-GitHub_Pages-black?style=for-the-badge&logo=github)](https://pages.github.com/)
[![Stack](https://img.shields.io/badge/Stack-Vanilla_HTML%2FCSS%2FJS-orange?style=for-the-badge)](#)
[![Theme](https://img.shields.io/badge/Theme-Retro_Terminal-yellow?style=for-the-badge)](#)

---

## 📖 What Is This

A single `index.html` portfolio page that serves as the front door to the Over Engineered series. It features:

- **Project cards** for Smart Solar PCU, EcoSphere, and Air Memory — with tech stacks, live metrics, and GitHub links
- **AI Review Panel** — real verdicts from Claude Opus 4, Gemini 3.1 Pro, and ChatGPT on the portfolio's gloriously disproportionate engineering
- **Per-project review table** — one punchy one-liner per model per project, like a Rotten Tomatoes critic board for IoT overkill
- **Terminal log** — a fake-but-accurate boot sequence summarising all three AI verdicts
- **Retro terminal aesthetic** — IBM Plex Mono, Bebas Neue, amber CRT glow, scanline overlay, noise texture, grid background

Zero frameworks. Zero dependencies. Zero npm install. One file.

---

## 🏗️ Stack

| Layer | Choice | Why |
|---|---|---|
| Markup | HTML5 | It's a static page. A relay would have worked. |
| Styling | Vanilla CSS + CSS Variables | No build step. No Tailwind config. Just vibes. |
| Fonts | IBM Plex Mono + Bebas Neue | Loaded from Google Fonts. One `<link>` tag. |
| Animations | CSS keyframes + IntersectionObserver | No JS animation libraries needed. |
| Hosting | GitHub Pages | Free, zero config, embarrassingly simple. |

**Total dependencies: 0** *(two Google Fonts, which is basically cheating)*

---

## 🚀 How to Deploy on GitHub Pages

**Live URL will be:** `https://acervenky.github.io/over-engineered-catalogue`

**1. Create the repo**

Go to [github.com/new](https://github.com/new) and create a repo named:

```
over-engineered-catalogue
```

**2. Clone it, add the files, and push**

```bash
git clone https://github.com/acervenky/over-engineered-catalogue
cd over-engineered-catalogue
# Drop index.html and README.md into this folder
git add index.html README.md
git commit -m "feat: launch OE portfolio page"
git push origin main
```

**3. Enable GitHub Pages**

- Go to your repo → **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Branch: `main` — Folder: `/ (root)`
- Click **Save**

**4. Done.** Wait ~60 seconds. Visit `https://acervenky.github.io/over-engineered-catalogue`.

---

## 📁 File Structure

```
acervenky.github.io/          # or your repo root
└── index.html                # The entire portfolio. That's it. One file.
```

No build step. No `node_modules`. No `package.json`. A relay would have worked.

---

## ✏️ Updating the Page

### Adding a new project
Find the `<!-- PROJECTS -->` section and copy an existing `.project-card` block. Update the number, icon, name, tagline, description, tech badges, meta stats, and GitHub link.

### Adding a new AI review
When you get a new model's verdict:
1. Update the reviewer card — swap `badge-pending` → `badge-verified`, replace the placeholder quote, add the score
2. Fill in the three mini one-liners in the per-project table
3. Add a line to the terminal log block at the bottom of the reviews section

### Changing stats
The hero stats (kWh, months of data, BOM total) are plain text in the `.hero-stats` block — update them directly.

---

## 🎨 Design Decisions

The aesthetic is **retro-futuristic terminal** — the kind of screen you'd see in a 90s sci-fi film running on hardware that definitely doesn't exist. Key choices:

- **Amber** as the primary accent — warm, CRT-authentic, reads well on near-black backgrounds
- **IBM Plex Mono** for everything — monospace enforces the terminal illusion throughout
- **Bebas Neue** for the hero title only — the contrast between the wide display font and tight mono is the whole personality
- **Scanline overlay + noise texture** — pure CSS, fixed position, pointer-events none, doesn't affect interaction
- **Grid background on hero** — masked with a radial gradient so it fades at the edges cleanly
- **No purple gradients** — this is a design principle, not a coincidence

---

## 📄 License

**CC BY-NC 4.0** — Free for personal and educational use. Commercial use prohibited.

See [http://creativecommons.org/licenses/by-nc/4.0/](http://creativecommons.org/licenses/by-nc/4.0/) for full terms.

---

<div align="center">

**Over Engineered with 💚 by Venky**

*Because a pinned README would have sufficed.*

</div>
