# 7CGPA Labs — Static Org Website (GitHub Pages)

## Problem
Single-page static site for GitHub org 7CGPA-Labs. Dark mode + neon blue. Single index.html (embedded CSS/JS). Live repo fetch via GitHub API.

## Delivered (2026-06)
- /app/index.html — full single-file site, no backend/build step
- Sections: Hero (terminal visual), About (mission/vision + values), Projects (live GitHub repos w/ fallback), Team grid, CTA/Contact, Footer
- Live GitHub API fetch (orgs/7CGPA-Labs/repos) with static fallback + skeleton loaders
- Mobile hamburger nav, smooth scroll, scroll-reveal, card hover glow, responsive
- Fonts: Sora + Manrope + JetBrains Mono. Icons: Lucide CDN
- Editable CONFIG object at bottom of <script> (org, repos, team)

## Deploy
Push index.html to repo root (or docs/) → Settings > Pages > deploy from branch.

## Backlog / P1
- Real team member names/avatars (currently placeholders)
- Optional: separate style.css/script.js split if preferred
- Optional: language-color dots matching GitHub's real palette
