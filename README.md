# Muhammad Hassan — Personal Portfolio

> A clean, fast, fully responsive single-page portfolio showcasing projects, skills, and a working contact form — built with pure HTML, CSS, and JavaScript. No frameworks, no build step.

---

## 🔗 Live Site

**[hassancodebase.github.io](https://hassancodebase.github.io)**

---

## 📸 Preview

| Desktop | Mobile |
|--------|--------|
| Full-width hero with animated gradient blob | Hamburger nav with stacked layout |

---

## ✨ Features

- **Animated hero section** with gradient blob and scroll indicator
- **Skills grid** with animated progress bars triggered on scroll
- **Project gallery** with tags, GitHub links, and live demo links
- **Education timeline** with certifications panel
- **Working contact form** powered by EmailJS — no backend needed
- **Scroll-based reveal animations** on all sections
- **Responsive design** — tested across mobile, tablet, and desktop
- **Smooth scroll navigation** with active link tracking
- **Dark theme** with custom CSS variables for easy theming

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, Grid, Flexbox, keyframe animations) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Syne + Inter |
| Email | EmailJS (contact form, no backend) |
| Hosting | GitHub Pages |

> **No build tools, bundlers, or frameworks required.** Open `index.html` and it works.

---

## 📁 Project Structure

> Currently the site ships as a single `index.html` file.

---

## 🚀 Getting Started

### View Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/hassancodebase/hassancodebase.github.io.git
   cd hassancodebase.github.io
   ```

2. Open `index.html` in any browser — no server or install needed.

### Contact Form Setup (EmailJS)

The contact form uses [EmailJS](https://www.emailjs.com) to send emails without a backend. To configure it for your own account:

1. Create a free account at [emailjs.com](https://www.emailjs.com)
2. Create a **Service** (e.g. Gmail) and note the **Service ID**
3. Create an **Email Template** and note the **Template ID**
4. Copy your **Public Key** from the EmailJS dashboard
5. In `index.html`, update these three values:

   ```javascript
   emailjs.init("YOUR_PUBLIC_KEY");          // line ~387
   emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this)
   ```

---

**Theme colors (CSS variables):**

```css
:root {
  --clr-bg:       #0a0a0f;   /* page background */
  --clr-accent:   #00e5ff;   /* cyan highlight   */
  --clr-accent2:  #7c4dff;   /* purple highlight */
  --clr-text:     #e2e2ea;   /* body text        */
}
```

---

## 🌐 Deployment

### GitHub Pages (current)
Push to the `main` branch. GitHub Pages serves the site automatically from the repo root since the repo is named `hassancodebase.github.io`.

---

## 📬 Contact

**Muhammad Hassan**
- 📧 Email: [theawanite001@gmail.com](mailto:theawanite001@gmail.com)
- 🐙 GitHub: [github.com/hassancodebase](https://github.com/hassancodebase)

---

## 📄 License

This project is open for reference and inspiration. If you use this as a base for your own portfolio, a credit or a ⭐ on the repo is appreciated!

---

<p align="center">Built with ❤️ by Muhammad Hassan </p>
