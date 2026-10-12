# Petals Community Empowerment Foundation

Static website for **petals.or.ke** — hosted on GitHub Pages.

## Live site

<https://petals.or.ke>

## About

Building Community Wellness Through a Holistic Approach.

**Objectives**

1. Establish sustainable water supply systems
2. Construct and rehabilitate sanitation facilities
3. Provide nutrition education
4. Enhance educational access and quality
5. Implement healthcare programs

**Core values:** Community, inclusivity, innovation, sustainability, integrity, conservation of environment, respect and impact.

## Structure

- `index.html` — single-page site (self-contained CSS + JS)
- `assets/logo.png` — foundation logo
- `CNAME` — apex domain record for GitHub Pages (`petals.or.ke`)

## DNS (GitHub Pages)

GitHub Pages serves a custom domain, but the DNS records live at the registrar/nameserver (host-ww.net).

- **Apex (`@` / `petals.or.ke`):** A records →
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- **`www`:** CNAME → `<username>.github.io`

## Development

```bash
python3 -m http.server 8090
# open http://127.0.0.1:8090/index.html
```
