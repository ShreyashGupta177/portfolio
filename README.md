# Shreyash Gupta — Developer Portfolio

A sleek, responsive, modern dark-themed developer portfolio built with HTML5, CSS3, and modern vanilla JavaScript.

Live Site: Designed for hosting on [GitHub Pages](https://pages.github.com/).

---

## ✨ Features

- **Futuristic Dark Aesthetic**: Tailored color palette with dynamic glow, subtle particle canvas background, and smooth gradients.
- **Interactive Cursor Glow**: Subtle radial lighting tracking the mouse pointer.
- **Dynamic Typing Effect**: Cycles through key specialties (Full-Stack, AI/ML, Problem Solver, etc.).
- **Live Project Showcases**:
  - **HireMind AI**: SaaS job application with UI mockup, tech stack tags, and direct GitHub links.
  - **Emotion Recognition Detector**: Computer vision & deep learning live emotion detector showcase.
- **Interactive Terminal Card**: Real-time terminal styling displaying bio and focus areas.
- **Skills Matrix**: Categorized tags across Frontend, Backend, AI/ML, and Tools.
- **Responsive Navigation**: Glassmorphic sticky header with mobile menu and smooth scrolling.
- **Zero Heavy Dependencies**: Pure HTML5, CSS3, and modern ES6+ JavaScript for blazing fast load times (100/100 Lighthouse performance).

---

## 🚀 Quick Start / Local Preview

You can open `index.html` directly in your browser or serve it with Python:

```bash
# In the project directory
python3 -m http.server 3000
```
Then visit `http://localhost:3000`.

---

## 🌐 Deploying to GitHub Pages

1. Initialize a git repository (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio release"
   ```
2. Push to your GitHub repository:
   ```bash
   git remote add origin https://github.com/ShreyashGupta177/portfolio.git
   git branch -M main
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** > **Pages**
   - Under **Build and deployment**, set source to **Deploy from a branch** (`main` / root)
   - Click **Save** — your site will be live at `https://shreyashgupta177.github.io/portfolio`!

---

## 🛠️ Customization

- **Contact Links**: Update email and LinkedIn profile URLs in the `#contact` section of `index.html`.
- **Projects**: Easily add new project cards in the `.projects-grid` section.
- **Colors**: Customize the CSS variables at the top of `style.css` (`--accent`, `--gradient`, `--bg`, etc.).
