# Iron & Ink — Premium Tattoo Studio

A production-ready landing page for **Iron & Ink**, a fictional premium tattoo studio in Brooklyn, NY. Dark luxury aesthetic with gold accents, smooth animations, and fully responsive design — all in a single HTML file with zero dependencies.

![Iron & Ink Preview](screenshot-placeholder.png)

## Live Demo

[View Live Demo](#) <!-- Replace with your deployment URL -->

## Features

- Elegant dark mode design with grain texture overlay
- Staggered hero entrance animations
- Scroll-reveal animations using `IntersectionObserver`
- Fully responsive mobile-first layout
- Functional hamburger menu with smooth transitions
- Smooth scroll navigation
- Micro-interactions on hover states (buttons, cards, gallery items)
- SVG placeholders — no external image dependencies
- Semantic HTML with accessibility considerations
- Single-file architecture — no build step required

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations, `backdrop-filter`
- **Vanilla JavaScript** — `IntersectionObserver`, event delegation, no frameworks
- **Google Fonts** — Playfair Display + Outfit

## Run Locally

No build tools or dependencies required.

```bash
# Clone the repository
git clone https://github.com/KDG0/iron-and-ink-landing.git

# Open in your browser
cd iron-and-ink-landing
open index.html
# or on Windows:
start index.html
# or simply drag index.html into your browser
```

Alternatively, use any local server:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
```

## Project Structure

```
iron-and-ink-landing/
├── index.html      # Complete landing page (HTML + CSS + JS)
├── .gitignore
└── README.md
```

## Sections

1. **Hero** — Staggered title animation, dual CTAs, scroll indicator
2. **About** — Studio story with statistics (6+ years, 2,000+ tattoos, 15+ awards)
3. **Services** — Fine Line, Japanese Traditional, Neo-Traditional, Blackwork
4. **Gallery** — 6-piece portfolio grid with hover overlays
5. **Testimonials** — 3 client reviews with star ratings
6. **Booking CTA** — Contact details and consultation CTA
7. **Footer** — Organized link columns, social media, legal

## 🤖 AI Virtual Assistant

This landing page includes an embedded AI chatbot powered by a **RAG (Retrieval-Augmented Generation)** pipeline. The assistant can answer questions about the studio's services, pricing, artists, hours, and more — all based on real business data.

### How it works:

1. Customer messages are processed by an **AI Agent** running on **N8N**
2. The agent searches a **vector knowledge base** for relevant business information
3. **Claude (Anthropic)** generates natural, accurate responses using the retrieved context
4. Responses are delivered in real-time through an embedded **chat widget**

**Built with:** N8N · Claude API (Anthropic) · OpenAI Embeddings · Vector Store · Custom CSS theming

## Author

**Kevin Guifarro**
[guifarro.dev](https://guifarro.dev)

---

Built with precision. No frameworks. No shortcuts.
