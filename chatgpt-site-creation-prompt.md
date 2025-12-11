You are building a small, static, corporate-style website for a completely fictional company called **Quantalyx Industries**. The site will be hosted on **GitHub Pages** under the real domain **quantalyx-industries.site** and used as a private, ethical phishing / recon training lab.

## High-level requirements

- Generate a **pure static site**:
  - Plain HTML, CSS, and a little vanilla JavaScript if needed.
  - No backend, no database, no frameworks.
  - Must work when the repository is pushed to GitHub and served via GitHub Pages.
- The codebase must **NOT mention Replit anywhere** (no logos, comments, or text).
- All content, history, products, and people must be **completely fictional** and a bit futuristic.
- The company profile:
  - Name: **Quantalyx Industries**
  - Domain: **quantalyx-industries.site**
  - Vibe: Futuristic industrial / AI / cyber-manufacturing mega-corp.
  - Focus areas: autonomous robotics, industrial IoT, predictive maintenance, SCADA analytics, AI-driven manufacturing optimization.

## File & project structure

Create a project with at least the following files in the root:

- `index.html`           (Home)
- `about.html`           (About Quantalyx)
- `team.html`            (Leadership & team)
- `history.html`         (Company history & timeline)
- `login.html`           (Quantalyx Client Portal login)
- `styles.css`           (shared styling)
- `robots.txt`
- `sitemap.xml`
- Optionally `favicon.ico` or a simple SVG logo.
- Optionally `.nojekyll` (empty file) to ensure GitHub Pages serves everything as-is.

All pages must link to `styles.css` and use consistent navigation.

## Design & layout

- Professional, clean, slightly futuristic B2B style.
- Use semantic HTML (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- Use a top navigation bar on all main pages with links to:
  - Home (`index.html`)
  - About (`about.html`)
  - Team (`team.html`)
  - History (`history.html`)
  - Client Portal Login (`login.html`)
- Make the layout responsive for desktop and mobile.
- Use a modern sans-serif font (you may import from Google Fonts).
- Use a simple color palette (e.g., dark blue / teal / gray with some accent color).
- Highlight the current page in the nav (e.g., bold or underline).

## Page-by-page content requirements

### 1. `index.html` (Home)

- Hero section with:
  - Company name: **Quantalyx Industries**
  - Tagline, for example: “Autonomous Intelligence for the Next-Generation Factory.”
- Short paragraphs explaining that Quantalyx builds:
  - Industrial IoT sensors
  - Edge AI devices
  - SCADA and OT/IT integrations
  - Cloud-based manufacturing analytics
  - Zero-trust security for factories
- Add CTA buttons/links:
  - “Meet the Team” → `team.html`
  - “Explore Our History” → `history.html`
  - “Access Client Portal” → `login.html`
- Include a small “At a Glance” section with 3–4 cards (e.g. “Global Footprint”, “AI-Driven Optimization”, “Secure OT/IT Convergence”).

### 2. `about.html` (About)

- Describe Quantalyx Industries as a global, mid-sized but rapidly scaling company.
- Include paragraphs mentioning:
  - Industrial IoT, predictive maintenance, digital twins
  - Cyber-physical security, SOC monitoring, SIEM, log analytics
  - Tech stack buzzwords: Kubernetes, containerized microservices, Linux, edge computing, ML pipelines, zero-trust networking.
- Mention that Quantalyx runs a “Secure Manufacturing Cloud” platform used by “Tier-1 automotive, aerospace, and energy clients”.

### 3. `team.html` (Team)

This page is very important for phishing & recon training.

- Create a **table or card grid** of at least **6 realistic fake employees** with:
  - Full name
  - Job title
  - Department
  - **Corporate email address** at `@quantalyx-industries.site`.
- Use patterns like:
  - `alex.rivera@quantalyx-industries.site`
  - `jamie.chen@quantalyx-industries.site`
  - `priya.patel@quantalyx-industries.site`
  - `miguel.santos@quantalyx-industries.site`
  - `sarah.williams@quantalyx-industries.site`
- Add internal-sounding job titles: “Director of OT Security”, “Principal Data Scientist, Predictive Maintenance”, “VP, Autonomous Systems”, etc.

4. history.html (History)
Create a timeline with multiple years (e.g., 2016, 2018, 2020, 2023, 2025).
