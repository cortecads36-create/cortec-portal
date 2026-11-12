# Cortec Middle East – Partner Portal (Clickable Prototype)

A static, front-end-only clickable prototype of the Cortec Middle East Partner Portal.
**All data is sample data. There is no backend, real authentication or database.**

## Features
- Login with MFA step and role preview (CSP Partner, CIA Member, Cortec Admin)
- Home dashboard: KPIs, recommendations, tasks, announcements
- Knowledge Hub with search and filters (role-based visibility)
- Partner Academy: courses, progress, certificates
- Opportunity Centre: register and track opportunities
- Technical Support: requests and timeline
- Marketing Centre, Community, Reports, My Organisation
- Admin Console: partner approvals, content governance, audit log

## Project structure
```
cortec-me-partner-portal/
├── index.html
├── assets/
│   ├── css/styles.css
│   └── js/app.js
└── README.md
```

## Run locally
Open `index.html` in Chrome, or run a local server:
```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Push to GitHub
```bash
cd cortec-me-partner-portal
git init
git add .
git commit -m "Initial commit: Cortec ME Partner Portal prototype"
git branch -M main
git remote add origin https://github.com/<your-username>/cortec-me-partner-portal.git
git push -u origin main
```

## Publish with GitHub Pages
Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
The site will be live at `https://<your-username>.github.io/cortec-me-partner-portal/`.

> Note: Keep the repository **private** if the prototype should stay internal.
> GitHub Pages on private repos requires a paid GitHub plan.
