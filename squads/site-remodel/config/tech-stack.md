# Tech Stack

## Core
- **Three.js** v0.160.0 — 3D rendering (ES modules via importmap CDN)
- **GSAP** v3.12.5 — Animacoes e morphing (CDN)
- **Montserrat** — Tipografia (Google Fonts)

## Estrutura
- HTML/CSS/JS puro (sem framework, sem bundler)
- ES Modules via `<script type="importmap">`
- CSS Custom Properties para design tokens

## CDNs
- `cdn.jsdelivr.net` — Three.js
- `cdnjs.cloudflare.com` — GSAP
- `fonts.googleapis.com` — Fontes

## Deploy (planejado)
- Vercel ou GitHub Pages
- Dominio customizado (a definir)

## Futuro (quando necessario)
- Vite (bundler, se modularizacao exigir)
- GSAP ScrollTrigger plugin
- Service Worker (PWA)
