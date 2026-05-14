[README.md](https://github.com/user-attachments/files/27771644/README.md)
# christianwood.dev · Portfolio Website

Personal portfolio site for **Christian Wood** — cybersecurity professional, CompTIA Security+ certified, B.S. Cybersecurity @ Purdue University (May 2026).

Built as a single-file static site, deployable instantly via GitHub Pages.

---

## Live Site

🔗 [cyberspango.github.io/Website](https://cyberspango.github.io/Website)

---

## About

This site serves as my professional portfolio for cybersecurity job applications. It covers my experience, technical skills, projects, and contact information in a clean, dark-themed single-page layout.

**Sections:**
- **Hero** — availability status, title, quick summary
- **About** — background, goals, certification
- **Skills** — SIEM, EDR, IAM, compliance, networking, scripting
- **Experience** — Bell Techlogix & Information Service Agency internships (Summer 2025)
- **Projects** — Azure Sentinel SIEM lab, LAN config lab, Active Directory lab
- **Contact** — email, phone, LinkedIn, GitHub + contact form

---

## Tech Stack

| Layer | Choice |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Scripting | Vanilla JavaScript |
| Fonts | JetBrains Mono + Syne (Google Fonts) |
| Hosting | GitHub Pages |

No frameworks. No dependencies. No build step — just `index.html`.

---

## Deployment

### GitHub Pages (recommended)

1. Clone or fork this repo
2. Ensure `index.html` is in the root directory
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Save — your site will be live at `https://<username>.github.io/<repo>`

### Local Preview

```bash
git clone https://github.com/CyberSpango/Website.git
cd Website
open index.html
```

Or serve it locally:

```bash
npx serve .
# or
python3 -m http.server 8000
```

---

## Customization

All content lives in `index.html`. Key areas to update:

| What | Where in the file |
|---|---|
| Name, tagline, availability | `<!-- HERO -->` section |
| About text & stats | `<!-- ABOUT -->` section |
| Skills & tags | `<!-- SKILLS -->` section |
| Work experience | `<!-- EXPERIENCE -->` section |
| Projects | `<!-- PROJECTS -->` section |
| Contact links | `<!-- CONTACT -->` section |
| Colors & fonts | `:root` CSS variables at the top of `<style>` |

---

## Contact Form

The form is currently client-side only (shows a confirmation UI on submit). To enable real email delivery, replace the `<form>` tag with a [Formspree](https://formspree.io) endpoint:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
```

Sign up free at formspree.io — no backend required.

---

## License

This project is open for personal use and adaptation. If you use it as a base for your own portfolio, a credit or star is appreciated but not required.

---

*Christian Wood · [cd.wood@outlook.com](mailto:cd.wood@outlook.com) · [LinkedIn](https://www.linkedin.com/in/christian-wood-a7233724b/) · [GitHub @CyberSpango](https://github.com/CyberSpango)*
