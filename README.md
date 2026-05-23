<div align="center">

```
// atharva.codes
```

<br/>

# ✦ Atharva Dwivedi — Portfolio Website ✦

*"Innovation happens where logic meets creativity."*

<br/>

![Status](https://img.shields.io/badge/status-live-00d4ff?style=for-the-badge&labelColor=0a0c10)
![Built With](https://img.shields.io/badge/built_with-HTML_CSS_JS-a259ff?style=for-the-badge&labelColor=0a0c10)
![License](https://img.shields.io/badge/license-personal-ff5c7a?style=for-the-badge&labelColor=0a0c10)

<br/>

---

</div>

<br/>

## ˚ ༘ ✶ About This Project

A **dark, minimal, interactive** personal portfolio built entirely in vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, just clean code.

Designed to showcase work as an **AI & ML Engineer**, innovator, and freelancer — with a focus on real projects, verified certifications, and a seamless client experience.

<br/>

---

<br/>

## ⊹ ˚. Features

```
  ✦  Custom animated cursor with hover effects
  ✦  Typing animation cycling through personal taglines
  ✦  Scroll-triggered reveal animations on every section
  ✦  Animated skill bars that fill on scroll
  ✦  Counter animations for stats in the hero
  ✦  Clickable project cards → open full PDF presentations
  ✦  Clickable certification cards → redirect to live credentials
  ✦  Live contact form powered by EmailJS → emails land in Gmail
  ✦  Grid background + radial glow aesthetic
  ✦  Fully responsive for mobile & desktop
```

<br/>

---

<br/>

## ⋆｡ °✈︎ Sections

| Section | What's Inside |
|---|---|
| **Hero** | Name, role, animated taglines, live stats |
| **About** | Bio, highlights, key achievements |
| **Skills** | Tech stack with animated proficiency bars |
| **Projects** | 3 real projects with PDF presentation links |
| **Certifications** | 8 certs, all linked to live credentials |
| **Awards** | 8 honours from IITs, Govt. of UP & more |
| **Services** | Freelance offerings with pricing |
| **Process** | 4-step client workflow |
| **Contact** | Live form → email delivered to Gmail |

<br/>

---

<br/>

## ✿ Projects Showcased

```
  01 ─ Tatini Pavitra Strotas
        MSME startup for sacred river restoration
        CM Yuva Innovation Challenge · IIT Kanpur
        [ Featured ]

  02 ─ Family Alert System (FAS)
        Behavioural road safety intervention
        Submitted to IIT Madras Ideathon

  03 ─ Ganga Saathi Circles
        Community waste segregation policy
        EUREKA – INNORAVE 2026
```

<br/>

---

<br/>

## ⌖ Tech Stack

```
  Language    →   HTML5 · CSS3 · Vanilla JavaScript
  Fonts       →   Syne (headings) · Space Mono (code/labels)
  Email       →   EmailJS (contact form → Gmail)
  Design      →   Custom CSS variables · no frameworks
  PDFs        →   Embedded & served locally
  Hosting     →   Netlify Drop (recommended)
```

<br/>

---

<br/>

## ˚₊ · ͟͟͞͞➳❥ Folder Structure

```
portfolio/
│
├── portfolio.html              ← main website file
├── Tatini-Pavitra-Strotas.pdf  ← project 01 presentation
├── Family-Alert-System-FAS.pdf ← project 02 presentation
├── Ganga-Saathi-Circles.pdf    ← project 03 presentation
└── README.md                   ← you are here ✦
```

> ⚠️ Keep all PDF files in the **same folder** as `portfolio.html`
> so the View Project buttons work correctly.

<br/>

---

<br/>

## ✦ Quick Customisation

Everything lives inside one `CONFIG` object in the `<script>` tag.
No digging through code — just edit and save.

```js
const CONFIG = {
  name:     "Atharva Dwivedi",
  email:    "astrickwriter@gmail.com",
  location: "Lucknow, Uttar Pradesh, India",

  skills:       [ /* add/remove skills here */ ],
  projects:     [ /* add pdfLink for each project */ ],
  certs:        [ /* add credentialLink for each cert */ ],
  awards:       [ /* add/remove awards here */ ],
  services:     [ /* update offerings & pricing */ ],
  typedLines:   [ /* cycling taglines in the hero */ ],
}
```

**To retheme colours** — edit the CSS variables at the very top:

```css
:root {
  --accent:   #00d4ff;   /* ← main highlight colour */
  --accent2:  #a259ff;   /* ← secondary colour */
  --accent3:  #ff5c7a;   /* ← tertiary / error colour */
  --bg:       #080c10;   /* ← page background */
}
```

<br/>

---

<br/>

## ⟡ Deployment Guide

**Netlify Drop** *(recommended — free, instant)*

```
  1. Go to  →  app.netlify.com/drop
  2. Drag the entire portfolio folder onto the page
  3. Get a live URL in under 60 seconds
  4. EmailJS contact form will work perfectly on live URL
```

**GitHub Pages**

```
  1. Create a new repo on github.com
  2. Upload all files (html + 3 pdfs)
  3. Settings → Pages → Deploy from main branch
  4. Your site is live at username.github.io/repo-name
```

> 💡 EmailJS does **not** work on `file://` (local). Always use a hosted URL.

<br/>

---

<br/>

## ✉ Contact Form Setup

Powered by **EmailJS** — emails go directly to `astrickwriter@gmail.com`
with subject line `Freelance Client`.

Keys already configured:
```
  Service ID   →  service_fwsxxj4
  Template ID  →  template_mfqzhs1
  Public Key   →  Hsj5GBv8tZgVEnOTT
```

Template variables used:
```
  {{from_name}}    {{from_email}}    {{service_type}}
  {{budget_range}} {{message}}       {{subject}}
```

<br/>

---

<br/>

<div align="center">

*Built with intention. Designed with clarity.*

```
// atharva.codes  ·  astrickwriter@gmail.com  ·  Lucknow, India
```

⭑ &nbsp; If this helped you, leave a ⭐ &nbsp; ⭑

</div>
