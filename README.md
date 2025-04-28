# Palmetto Pints Site

Automated craft beer tasting site for Palmetto Pints built with [Astro](https://astro.build), deployed on [Netlify](https://netlify.com), with [Plausible Analytics](https://plausible.io/) integration and content automation via GitHub.

## Features
- Modern, fast, SEO-friendly static site
- Home, Events, Blog, About, and Contact pages
- Blog and events managed as Markdown files (easy to automate)
- Plausible Analytics for privacy-friendly tracking
- Automated deployment via Netlify (CI/CD from GitHub)
- Ready for agent-driven content automation (push new posts/events via PR or direct commit)

## Quick Start

1. **Clone the repo:**
   ```bash
   git clone https://github.com/GlitchOverride/palmetto-pints-site.git
   cd palmetto-pints-site
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run locally:**
   ```bash
   npm run dev
   ```
4. **Deploy:**
   - Push to `master` branch; Netlify will auto-deploy.

## Automation
- New blog posts/events can be created by adding Markdown files to the `src/content/blog/` or `src/content/events/` directories.
- Your agent can automate this via GitHub MCP or direct file system edits.

## Plausible Analytics
- Add your Plausible domain in `src/layouts/BaseLayout.astro`.

## Stack
- Astro
- Netlify
- Plausible Analytics
- Markdown/MDX for content
- GitHub for versioning/automation

---

**Ready for full automation and future extensibility.**
