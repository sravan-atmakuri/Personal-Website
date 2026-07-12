# sravan-atmakuri.dev — Personal Portfolio & Resume

My personal resume website — a single-file, zero-dependency portfolio built with vanilla HTML, CSS, and JavaScript, auto-deployed to Netlify on every push.

**Live:** _add your Netlify URL here_

---

## What's On It

- **Profile** — 9+ years of Salesforce engineering, specializing in Life Sciences Cloud, Data Cloud, and Agentforce
- **Skill matrix** — primary, core, and supporting skill areas with proficiency overview
- **Experience timeline** — Megnity Technologies (Insulet), AT&T Entertainment Group, Access Technology Solutions
- **Certifications** — 7 Salesforce certifications, verifiable on [Trailblazer](https://www.salesforce.com/trailblazer/satakoplasravanatmakuri)
- **Projects** — [job-hunter](https://github.com/sravan-atmakuri/job-hunter) (AI application pipeline), [umf2026](https://github.com/sravan-atmakuri/umf2026) (festival set-times PWA), and a [live wedding RSVP site](https://sandmk.com/)

## Design & Build

- **Single `index.html`** — all markup, styles, and scripts in one file; no framework, no build step, no dependencies beyond Google Fonts
- **Design language** — warm off-white canvas, Salesforce-blue accent palette (`#0176D3` / `#032D60`), Space Grotesk + IBM Plex Mono typography
- **Animation** — scroll-triggered reveals via `IntersectionObserver`: spiral-in tiles, staggered fade-ups, animated stat counters, filling skill bars, and a scroll progress bar
- **Ambient background** — faint dot grid with a slow-drifting gradient mesh
- **Accessible by default** — respects `prefers-reduced-motion` (all animation disabled, content shown instantly), semantic landmarks, keyboard-friendly nav

## Performance Notes

No JavaScript frameworks, no bundler, no external JS. The only network requests beyond the page itself are two Google Font families. Everything else — including the animation system — is ~200 lines of vanilla JS.

## Deployment

Connected to Netlify via this GitHub repo:

1. Push a change to `index.html` on `main`
2. Netlify auto-deploys (no build command; publish directory is the repo root)

To run locally, just open `index.html` in a browser — or:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Structure

```
.
├── index.html   # The entire site
└── README.md
```

---

© Sravan Atmakuri · [LinkedIn](https://www.linkedin.com/in/sravanatmakuri) · [GitHub](https://github.com/sravan-atmakuri)
