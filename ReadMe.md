<div align="center">

<br/>

```
███████╗██████╗  █████╗ ███╗   ██╗ ██████╗██╗███████╗
██╔════╝██╔══██╗██╔══██╗████╗  ██║██╔════╝██║██╔════╝
█████╗  ██████╔╝███████║██╔██╗ ██║██║     ██║███████╗
██╔══╝  ██╔══██╗██╔══██║██║╚██╗██║██║     ██║╚════██║
██║     ██║  ██║██║  ██║██║ ╚████║╚██████╗██║███████║
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝╚═╝╚══════╝
```

# Francis Garry Nillama — CV · 2026

### AI Engineer · LLM Systems & Agentic Workflows

<br/>

[![Live CV](https://img.shields.io/badge/🌐_Live_CV-cv--nillama--2026.vercel.app-1fc8a4?style=for-the-badge&logoColor=white)](https://cv-nillama-2026.vercel.app)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![GitHub](https://img.shields.io/badge/GitHub-FrancisGarryNillama-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/FrancisGarryNillama)
[![HTML5](https://img.shields.io/badge/Built_with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/FrancisGarryNillama/CV_Nillama_2026/blob/main/CV_NIllama_2026.html)

<br/>

> *A production-grade, typographically refined CV built as a single-file HTML document — dark editorial aesthetic, Google Fonts, and print-to-PDF ready. No frameworks, no build steps, no dependencies.*

<br/>

---

</div>

<br/>

## ✦ Preview

<div align="center">

| Section | Description |
|---|---|
| **Header** | Name in Cormorant Garamond serif · Live contact links · Role title |
| **Summary** | Italicized editorial-style professional profile |
| **Skills** | Six-card responsive grid — Languages, Frontend, Backend, AI/Data, DBs, DevOps |
| **Experience** | Lifewood internship + BPO history with quantified outcomes |
| **Projects** | 11 projects — type-badged, stack-labeled, metric-highlighted |
| **Education** | CIT-U BSIT 2026 |

</div>

<br/>

---

## ✦ Tech Stack & Design Choices

<div align="center">

| Layer | Choice | Rationale |
|---|---|---|
| **Markup** | HTML5 (single file) | Zero dependencies — deploy anywhere, open in any browser |
| **Typography** | Cormorant Garamond + Jost (Google Fonts) | Editorial luxury meets clean technical legibility |
| **Styling** | Vanilla CSS · CSS Custom Properties | Full control, no framework overhead, easy theming |
| **Color System** | Navy `#0b1121` · Teal `#1fc8a4` · Gold `#c8a85a` | Professional + distinctive — avoids generic purple/white AI aesthetics |
| **Layout** | CSS Grid · Flexbox | Responsive two-column project grid, adaptive skill cards |
| **Print** | `@media print` + `-webkit-print-color-adjust` | Export to PDF directly from browser with dark theme preserved |
| **Hosting** | Vercel (static) | Instant global CDN, zero config, auto-deploy on push |

</div>

<br/>

---

## ✦ Features

- 🎨 **Dark editorial design** — navy/teal/gold palette with Cormorant Garamond display typography
- 📄 **Single-file architecture** — the entire CV is one `.html` file — no build pipeline, no npm
- 🖨️ **Print-to-PDF ready** — open in Chrome → Print → Save as PDF. Dark theme is preserved via `print-color-adjust: exact`
- 📱 **Responsive layout** — CSS Grid adapts cleanly from desktop to tablet
- ⚡ **Near-instant load** — only external dependency is Google Fonts (2 families)
- 🔖 **ATS-safe content** — all text is semantic HTML, fully selectable and indexable
- 🌐 **Vercel auto-deploy** — every push to `main` triggers a new production deployment

<br/>

---

## ✦ Project Structure

```
CV_Nillama_2026/
│
├── CV_NIllama_2026.html     ← The entire CV (single file)
├── README.md                ← You are here
└── .vercelignore            ← (optional) exclude files from Vercel deployment
```

<br/>

---

## ✦ Deploying to Vercel — Step-by-Step

> **Already live?** Your CV is deployed at [`cv-nillama-2026.vercel.app`](https://cv-nillama-2026.vercel.app).  
> Every push to `main` will automatically re-deploy. Steps below are for reference and re-connection.

<br/>

### Method 1 — Vercel Dashboard (Recommended for first-time setup)

**Step 1 — Create a Vercel account**
```
→ Go to https://vercel.com
→ Click "Sign Up" → choose "Continue with GitHub"
→ Authorize Vercel to access your GitHub account
```

**Step 2 — Import your repository**
```
→ From the Vercel Dashboard, click "Add New..." → "Project"
→ Search for: CV_Nillama_2026
→ Click "Import" next to the repo
```

**Step 3 — Configure the project**
```
Framework Preset   →  Other  (it's a static HTML file, not a framework)
Root Directory     →  ./     (leave as default)
Build Command      →  (leave empty — no build needed)
Output Directory   →  ./     (leave as default)
```

**Step 4 — Deploy**
```
→ Click "Deploy"
→ Vercel will detect the HTML file and deploy in ~15 seconds
→ You'll receive a live URL: https://cv-nillama-2026.vercel.app
```

**Step 5 — (Optional) Add a custom domain**
```
→ Go to Project Settings → Domains
→ Add your custom domain (e.g., francisgarry.dev)
→ Update your DNS records as instructed by Vercel
```

<br/>

### Method 2 — Vercel CLI (Power users)

```bash
# Install Vercel CLI globally
npm install -g vercel

# Log in (opens browser for GitHub OAuth)
vercel login

# From inside your cloned repo directory
cd CV_Nillama_2026

# Deploy to production
vercel --prod

# Follow the prompts:
#   Set up and deploy? → Y
#   Which scope? → your username
#   Link to existing project? → Y (if already exists) / N (first time)
#   Project name? → cv-nillama-2026
#   In which directory? → ./
#   Override settings? → N
```

<br/>

### Keeping Your CV Up to Date

Once connected, deployment is fully automatic. Your workflow is:

```bash
# 1. Edit CV_NIllama_2026.html locally

# 2. Stage your changes
git add CV_NIllama_2026.html

# 3. Commit with a descriptive message
git commit -m "cv: update projects section with new internship outcomes"

# 4. Push to main — Vercel auto-deploys in ~15 seconds
git push origin main
```

> Vercel listens to your `main` branch. Every push = a new production deployment. You can monitor live builds at [vercel.com/dashboard](https://vercel.com/dashboard).

<br/>

---

## ✦ Exporting to PDF

**Chrome (Recommended)**
```
1. Open https://cv-nillama-2026.vercel.app in Chrome
2. Press Ctrl+P (Windows) or Cmd+P (Mac)
3. Set Destination → "Save as PDF"
4. Set Paper size → A4
5. Set Margins → None
6. ✅ Enable "Background graphics" checkbox
7. Click Save
```

**Tip:** The dark navy background is preserved via CSS `print-color-adjust: exact`. No color loss on export.

<br/>

---

## ✦ Local Development

No build tools required. Just open the file:

```bash
# Clone the repo
git clone https://github.com/FrancisGarryNillama/CV_Nillama_2026.git
cd CV_Nillama_2026

# Option A — open directly in browser
open CV_NIllama_2026.html          # macOS
start CV_NIllama_2026.html         # Windows
xdg-open CV_NIllama_2026.html      # Linux

# Option B — serve locally with Python (recommended, avoids CORS on fonts)
python -m http.server 8000
# → Open http://localhost:8000/CV_NIllama_2026.html
```

<br/>

---

## ✦ Customization Guide

All design tokens are CSS custom properties at the top of the `<style>` block:

```css
:root {
  --navy: #0b1121;       /* Page background */
  --teal: #1fc8a4;       /* Primary accent — links, badges, highlights */
  --gold: #c8a85a;       /* Secondary accent — section labels, ruling lines */
  --white: #f7f4ef;      /* Primary text */
  --muted: #8a95a8;      /* Secondary / descriptive text */
}
```

To change the color scheme, update these six variables — everything else inherits from them.

<br/>

---

## ✦ Skills Snapshot

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)

</div>

<br/>

---

## ✦ Connect

<div align="center">

| Channel | Link |
|---|---|
| 🌐 **Live CV** | [cv-nillama-2026.vercel.app](https://cv-nillama-2026.vercel.app) |
| 💻 **GitHub** | [github.com/FrancisGarryNillama](https://github.com/FrancisGarryNillama) |
| ✉️ **Email** | [paenggwapokaayo123@gmail.com](mailto:paenggwapokaayo123@gmail.com) |
| 📍 **Location** | Cebu City, Philippines |

</div>

<br/>

---

<div align="center">

```
Built with intention · Deployed with purpose · Maintained with pride
```

*© 2026 Francis Garry Nillama · AI Engineer · LLM Systems & Agentic Workflows*

</div>