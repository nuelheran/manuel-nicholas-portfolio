# Manuel Nicholas — Portfolio

A single-page personal portfolio for **Manuel Nicholas**, an Oracle APEX & Frontend Developer. It showcases selected enterprise projects, skills, certifications, and work experience through a dark, editorial-style design with an interactive Three.js background, a custom cursor, and smooth scroll animations.

**Live site:** deployed on Netlify with GitHub-connected auto-deployments.

## ✨ Highlights

- **Interactive 3D hero** — a Three.js (r128) canvas background rendered in real time.
- **Custom cursor & micro-interactions** — bespoke dot cursor, hover states, and scroll-triggered reveals.
- **Editorial dark theme** — Cabinet Grotesk / Fraunces / Fira Code type system with a blue accent palette and film-grain texture.
- **Fully responsive** — grid layouts collapse gracefully down to mobile.
- **Zero build step** — a single self-contained `index.html`; all CSS and JS are inline.

## 🧩 Sections

- **Hero** — intro and role.
- **About** — background, focus areas, and freelance work.
- **Skills & Technologies** — Oracle (APEX, DB, ORDS, EBS), frontend, Three.js, Machine Learning, and more.
- **Selected Projects** — Whistleblowing System, GL/EBS integration, risk heatmap, CV Generator, IT Asset Loan, KasFlow, and other enterprise and personal builds.
- **Experience** — roles at KCSI and PT Nojorono Tobacco International.
- **Licenses & Certifications** — including Oracle APEX Cloud Developer Certified Professional.
- **Contact** — email and social links.

## 🛠 Tech Stack

- **HTML / CSS / JavaScript** — hand-written, single-file, no framework.
- **[Three.js](https://threejs.org/) r128** — 3D background (loaded from CDN).
- **Google Fonts** — Cabinet Grotesk, Fraunces, Fira Code.
- **[Netlify](https://www.netlify.com/)** — hosting and continuous deployment.
- **[Netlify CLI](https://docs.netlify.com/cli/get-started/)** — local dev / deploy (only dev dependency).

## 📦 Project Structure

```
manuel-nicholas-portfolio/
├── index.html        # The entire site (inline CSS + JS)
├── favicon.png       # Site icon
├── package.json      # Dev dependency: netlify-cli
├── .gitignore
└── README.md
```

## 🚀 Getting Started

No build is required — the site is a single static file.

**Open directly:** open `index.html` in any browser.

**Or run a local server** (recommended, so fonts and CDN assets load cleanly):

```bash
# Python
python3 -m http.server 8000
# then visit http://localhost:8000
```

**Or with the Netlify CLI:**

```bash
npm install       # installs netlify-cli
npx netlify dev   # serves the site locally
```

## ☁️ Deployment

The site auto-deploys to Netlify on every push to the `main` branch. To deploy manually:

```bash
npx netlify deploy --prod
```

## 📬 Contact

- **Email:** manuelnicholasn@gmail.com
- **LinkedIn:** [manuelnicholas](https://linkedin.com/in/manuelnicholas/)
- **GitHub:** [nuelheran](https://github.com/nuelheran)
- **Instagram:** [nmanuelnicholas](https://instagram.com/nmanuelnicholas/)

## 📄 License

© Manuel Nicholas. All rights reserved. Provided for portfolio and reference purposes.
