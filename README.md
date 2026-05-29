# Kevin Muriuki Karimi — Portfolio Website

A personal portfolio website built as a single, self-contained HTML file. No frameworks, no build tools, no dependencies to install — just open in a browser or deploy to any static host.

***

## Live Site

[your-domain.com](https://your-domain.com)

***

## About This Project

This portfolio presents my professional background in technical support, software development, consultative sales, and project management. It is designed to help recruiters and hiring managers quickly understand my capabilities across:

- IT Support / Technical Support
- Solutions Engineering / Sales Engineering
- Junior Front-End / Full-Stack Development
- Technical Project Coordination
- Customer-facing roles in SaaS / cloud / enterprise tech

***

## Tech Stack

| Layer | Implementation |
|---|---|
| Structure | Plain HTML5 |
| Styling | CSS (custom design system, light/dark mode) |
| Interactivity | Vanilla JavaScript |
| Icons | [Lucide](https://lucide.dev) via CDN |
| Fonts | [Cabinet Grotesk + Satoshi](https://fontshare.com) via Fontshare CDN |

No npm. No build step. No framework. One file.

***

## Sections

- **Hero** — Headline, positioning statement, key stats
- **About** — Career story and core strengths
- **Skills** — Technical support, development, sales, and operations
- **Experience** — Career timeline from 2014 to present
- **Projects** — Featured work and planned builds
- **Why Kevin** — Differentiator and value proposition
- **Testimonials** — Endorsements
- **Contact** — Links and message form

***

## Getting Started

### View locally

1. Clone or download this repo
2. Open `index.html` in any browser
3. No installation required

### Edit

Open `index.html` in any text editor (VS Code recommended). Sections are clearly labelled with comments:

```
/* HERO */
/* ABOUT */
/* SKILLS */
/* EXPERIENCE */
/* PROJECTS */
```

Find the section you want, make your changes, save.

***

## Deployment

This site is hosted on **GitHub Pages**.

### To deploy your own fork:

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to **`main` branch, `/ (root)` folder**
4. Your site will be live at `https://yourusername.github.io/`

### Custom domain:

1. Go to **Settings → Pages → Custom domain**, enter your domain
2. Add these DNS records at your registrar:

| Type | Host | Value |
|---|---|---|
| `A` | `@` | `185.199.108.153` |
| `A` | `@` | `185.199.109.153` |
| `A` | `@` | `185.199.110.153` |
| `A` | `@` | `185.199.111.153` |
| `CNAME` | `www` | `yourusername.github.io` |

3. Enable **Enforce HTTPS** in Pages settings once DNS propagates

***

## Updating the Site

**Option 1 — Edit on GitHub (no software needed):**
Click `index.html` in the repo → pencil icon → edit → commit. Live in ~30 seconds.

**Option 2 — Edit locally:**
```bash
git clone https://github.com/yourusername/yourusername.github.io
# edit index.html
git add index.html
git commit -m "Update projects section"
git push
```

GitHub Pages redeploys automatically on every push. No build minutes, no limits.

***

## Roadmap

Projects currently listed as "Planned" or "In Progress":

- [ ] Helpdesk Ticket Dashboard (React)
- [ ] Customer Discovery CRM (React + API)
- [ ] IT Troubleshooting Knowledge Base
- [ ] SaaS Landing Page Showcase

***

## License

This project is for personal portfolio use. Feel free to fork the structure and adapt it for your own portfolio
