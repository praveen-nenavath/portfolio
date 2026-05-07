# Nenavath Praveen — Personal Portfolio

A responsive, dark-themed developer portfolio built with pure HTML, CSS and JavaScript. No frameworks, no build tools, no dependencies.

---

## Project Structure

```
portfolio/
│
├── portfolio.html       # Main portfolio file (single-file app)
└── README.md            # Project documentation
```

---

## Features

- Single-file architecture — everything in one `portfolio.html`, zero external dependencies
- Dark editorial design with green accent color `#7fff6e`
- Noise texture and animated blob effects via pure CSS
- Scroll-reveal animations using IntersectionObserver API
- Sticky glassmorphism navbar with active section highlighting
- Fully responsive across mobile, tablet, and desktop
- Google Fonts — Syne (display), DM Mono (body), Instrument Serif (italic)

---

## Sections

```
01 — Hero          Name, title, CTA buttons, quick-stats card
02 — Experience    BlueStock SDE internship details
03 — Projects      AgriTech, Banjara Shaadi, Online Voting System
04 — Skills        Languages, Frameworks, Databases, Tools, Soft Skills
05 — Achievements  DSA milestones, CGPA, internship, certifications
06 — Contact       Email, phone, GitHub, LinkedIn
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

### 2. Open in browser

```bash
# macOS
open portfolio.html

# Windows
start portfolio.html

# Linux
xdg-open portfolio.html
```

Or simply drag and drop `portfolio.html` into any browser window.

### 3. Serve locally (optional)

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

Then open `http://localhost:8000` in your browser.

---

## Customization

### Update personal info

```html
<!-- Hero name -->
<h1 class="hero-name">Nenavath<br><span>Praveen</span></h1>

<!-- Email -->
<a href="mailto:praveennenavath052@gmail.com">

<!-- Phone -->
<a href="tel:+919618963009">
```

### Update social links

```html
<!-- GitHub -->
<a href="https://github.com/YOUR_USERNAME">

<!-- LinkedIn -->
<a href="https://linkedin.com/in/YOUR_PROFILE">
```

### Update project links

```html
<!-- AgriTech -->
<a class="project-card" href="https://your-agritech-url.com">

<!-- Banjara Shaadi -->
<a class="project-card" href="https://banjarashaadi.com">
```

### Change accent color

```css
:root {
  --accent: #7fff6e;   /* change this to any color you like */
}
```

---

## Deployment

### GitHub Pages

```
1. Push the repo to GitHub
2. Go to Settings → Pages
3. Set source to main branch, / (root)
4. Live at: https://your-username.github.io/portfolio
```

### Netlify

```
1. Go to netlify.com
2. Drag and drop portfolio.html into the deploy zone
3. Done — live URL is generated instantly
```

### Vercel

```bash
npx vercel --prod
```

---

## Tech Stack

```
HTML5          Structure and semantic markup
CSS3           Styling, animations, responsive layout
JavaScript     Scroll-reveal, active nav highlighting (Vanilla JS)
Google Fonts   Syne · DM Mono · Instrument Serif
```

---

## Responsive Breakpoints

```css
/* Desktop */   min-width: 900px
/* Tablet  */   max-width: 900px
/* Mobile  */   max-width: 600px
```

---

## License

This project is open source and available under the MIT License.

---

## Author

```
Name     : Nenavath Praveen
Email    : praveennenavath052@gmail.com
Phone    : +91-9618963009
College  : RGUKT Basar — B.Tech CSE (2022–2026)
GitHub   : github.com/your-username
LinkedIn : linkedin.com/in/your-profile
```
