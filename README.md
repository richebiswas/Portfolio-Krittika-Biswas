# Krittika Biswas — Portfolio

Personal portfolio website. B.Tech CSE (AI) student, Techno India University.

**Live site:** [add your GitHub Pages URL here]

## Sections

- About
- Skills (Programming, Core CS, Frontend, Backend, Tools)
- Projects (Peenie, Glow Sales, Ultimate Space Invaders, IPL Analysis Dashboard, Escape The Labyrinth)
- Resume
- Experience (IBM SkillsBuild, Deloitte, Tata Forage)
- Hackathons (Smart India Hackathon, Smart Campus Hackathon)
- Certifications
- Contact (with a working contact form)

## Contact form

The contact form submits via [Formspree](https://formspree.io) using `fetch` (AJAX) — no page reload, and it shows a "Message sent" or error status inline.

- Form endpoint: `https://formspree.io/f/xzepkdon`
- To change where messages go, log into Formspree and update the destination email on that form — no code changes needed.
- To swap it for a different Formspree form, replace the `action` URL on the `<form id="contactForm">` element in `index.html`.

## Built with

- HTML / CSS / JavaScript
- [Three.js](https://threejs.org/) — animated 3D background
- [Font Awesome](https://fontawesome.com/) — icons
- Google Fonts — Playfair Display, Space Grotesk, JetBrains Mono

## Project structure

```
resume/
├── index.html
├── profile.jpg
├── Krittika_Biswas_CV.pdf
└── public/
    ├── certificates/
    │   ├── deloitte-analytics.png
    │   ├── freecodecamp-responsive.png
    │   ├── ibm-ml-python.png
    │   ├── sih-participation.png
    │   └── tata-forage-genai.png
    └── projects/
        ├── escape-labyrinth.png
        ├── glow-sales.png
        ├── ipl-dashboard.png
        ├── peenie.png
        └── space-invaders.png
```

## Running locally

Opening `index.html` directly (`file:///...`) breaks the resume download button — browsers block the `download` attribute on local files. Serve it instead:

```bash
python -m http.server
```

Then open `http://localhost:8000`.

## Contact

- Email: krittikabiswas1783@gmail.com
- GitHub: [github.com/richebiswas](https://github.com/richebiswas)
- LinkedIn: [krittika-biswas](https://www.linkedin.com/in/krittika-biswas-0a24a42b8/)
- LeetCode: [krittikabiswas1783](https://leetcode.com/u/krittikabiswas1783/)
