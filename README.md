# Climate Action — Multimedia Responsive Webpage

This project is a responsive, multimedia webpage built to showcase community
climate action initiatives (SDG 13). It includes a hero, embedded video and
audio, a gallery of project cards, project detail pages, an events list, and an
interactive map of community reports.

How to run locally
1. From the project root (`/workspaces/web_development`) start a simple server:

```bash
python3 -m http.server 8000
```

2. Open your browser to `http://localhost:8000/index.html`

Files of interest
- `index.html` — Main site (hero, media, gallery, events, map)
- `styles.css` — All styling (responsive grid, hero, gallery)
- `assets/` — Local images used in the project
- `projects/` — Individual project pages
- `data/reports.geojson` — Sample GeoJSON used to populate the Leaflet map

Deployment
- The site is a static site and can be deployed to GitHub Pages, Netlify, or
  any static host. To use GitHub Pages, enable Pages for the repository and
  select the `main` branch (or push to a `gh-pages` branch).

Notes
- The embedded YouTube video includes a fallback link in case embedding is
  restricted by the environment.
- The interactive map uses Leaflet with data from `data/reports.geojson`.

Repository
- https://github.com/jyoti0612/web_development
