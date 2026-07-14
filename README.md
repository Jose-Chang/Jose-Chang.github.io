# Jose Ramon Chang Irias, Ph.D. — Personal Website

This repository hosts my personal GitHub Pages website, built as a modern, responsive
one-page portfolio based on my resume/CV.

🔗 **Live site:** https://jose-chang.github.io

## Sections

- **Hero** — Introduction, role, and quick links (contact, resume, socials)
- **About** — Personal profile summary
- **Experience** — Professional timeline (Promise Technology, NCKU, Altum Lab, CAISR, Darmiyan)
- **Education** — Ph.D., M.Sc., and B.Sc. details
- **Publications** — Journal articles, conference talks, and workshops
- **Skills & Volunteering** — Technical skills, software, leadership, and volunteer work
- **Honors, Languages & Certifications** — Scholarships, awards, and language proficiencies
- **Contact** — Email, phone, and professional links (LinkedIn, Google Scholar, Nordlinglab)

## Tech Stack

- Plain HTML5, CSS3 (custom properties, responsive grid/flexbox, animations)
- Vanilla JavaScript (no frameworks) — scroll progress bar, dark/light theme toggle,
  mobile navigation, scroll-triggered reveal animations, active nav highlighting
- [Font Awesome](https://fontawesome.com/) icons
- Google Fonts: Merriweather (headings) & Inter (body)

## Local Development

Simply open `index.html` in your browser, or serve the folder with any static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customization

- Add your resume PDF to `assets/Jose_Chang_Resume.pdf` so the "Resume" button works.
- Update social links (LinkedIn, Google Scholar, Nordlinglab profile) in `index.html`.
- Colors and theme can be adjusted via CSS variables at the top of `style.css`.

## Deployment

This site is deployed automatically via **GitHub Pages** from the `main` branch.
Any push to `main` will update the live site.
