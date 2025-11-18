# SDG 13: Climate Action — Multimedia Responsive Project

Overview
- This project is a responsive multimedia webpage showcasing community-level
  climate action initiatives. It demonstrates advanced CSS layout techniques
  (Flexbox and CSS Grid), responsive media queries, custom fonts, and
  multimedia embedding (audio and video).

Files
- `index.html`: A full-page layout with a navigation header, hero section,
  content area with audio and embedded video, a gallery of 6 media cards, and
  a footer.
- `styles.css`: Advanced styles using CSS Grid for the layout and responsive
  breakpoints, pseudo-classes for interactivity, a custom Google Font, and
  visual enhancements (shadows, overlays, transitions).
- `assets/`: Local images used by the hero and gallery.

Approach
- I built a semantic, accessible HTML structure with clear landmarks (`header`,
  `main`, `section`, `footer`). The hero uses a background image with an
  overlay and a call-to-action. The content area presents text and an audio
  sample; a responsive iframe embeds a YouTube video. The gallery uses a CSS
  Grid to present 6 cards that reflow across breakpoints.

Responsive behavior
- Desktop: two-column content and a three-column gallery.
- Tablet: stacked content and a two-column gallery.
- Mobile: single-column flow for all sections; navigation collapses for small
  screens (links are hidden to keep the demo simple).

How to view locally
1. Open a terminal in the project folder (`/workspaces/web_development`).
2. Start a simple static server (Python 3):

```bash
python3 -m http.server 8000
```

3. Open your browser to `http://localhost:8000` and open `index.html`.

Notes
- Images in `assets/` are from Unsplash (placeholder examples). If you want
  higher control, I can add optimized thumbnails and Local `video`/`audio` files.
- I can also push this project to a GitHub repository or create a hosted demo
  on CodeSandbox — tell me which you prefer.

