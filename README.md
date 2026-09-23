# Sergey Orlov — portfolio

[orlovtsu.github.io](https://orlovtsu.github.io/) · [LinkedIn](https://www.linkedin.com/in/orlovtsu/)

A static portfolio focused on production machine learning, credit decisioning, data engineering, applied AI, and technical ownership.

## Pages

- `index.html`: positioning, selected production work, four public reference labs, background, and contact.
- `work.html`: professional case studies in decisioning, document intelligence, analytics platforms, and entity resolution, with technical ownership, modeling, decisioning, production, lifecycle responsibilities, and links to independent demonstrations.
- `archive.html`: one selected collaborative geospatial project, clearly marked as earlier team research.
- `downloads/`: public résumé and a conceptual credit decisioning architecture overview.
- `assets/portfolio/`: current design, social preview, and synthetic report images from the public labs.

The site uses plain HTML and CSS with self-hosted Manrope and DM Sans fonts (OFL licenses in `assets/portfolio/fonts/`). It has no build step, client-side app framework, analytics, or contact-form backend. Serve locally with `python -m http.server 8000`. GitHub Pages serves the repository root. `.nojekyll` makes static-file publishing explicit.

## Content maintenance

Cashco experience describes technical ownership, general engineering methods, and broad tooling. Public pages and downloadable documents omit internal employer metrics, comparative model results, business volumes, vendor economics, and nonpublic deployment configurations. The architecture PDF is a conceptual explanation of responsibilities, not an employer deployment blueprint. Public examples must remain distinct from employer implementations. Any future addition of employer-specific facts requires checking the applicable publication permissions first.

Public project descriptions were checked against repository source and documentation on September 22, 2026. Cashflow Intelligence Lab is described as a compact prototype; its README mentions reports not present in the inspected tree, so its website links to source and tests. Document AI cloud adapters are optional boundaries, not live providers in the default benchmark.

The public selection focuses on current engineering work and one earlier collaborative geospatial project. Retired tutorial prototypes, exploratory studies, old write-ups, and their standalone charts are removed from the site. Their separate source repositories are unchanged. The old `/portfolio/` entry point redirects to the main portfolio. Historical template license files are retained for attribution.

All four current public labs use synthetic data. The separate analytics-platform-portfolio repository contains generic examples and design discussions informed by professional experience. It does not describe an employer’s current deployment or provide a complete runnable platform.
