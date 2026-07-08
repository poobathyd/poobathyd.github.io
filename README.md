# poobathyd.github.io

Personal portfolio site for Poobathy D, PhD — live at **https://poobathyd.github.io**

## How to publish (one-time setup)

1. Sign in to GitHub and create a new **public** repository named exactly: `poobathyd.github.io`
2. Upload all files in this folder to the repository (drag-and-drop on github.com works, or use git):

   ```bash
   cd poobathyd.github.io
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/poobathyd/poobathyd.github.io.git
   git push -u origin main
   ```

3. Wait 1–2 minutes. Your site is live at https://poobathyd.github.io

No build step needed — it's plain HTML/CSS/JS, served directly by GitHub Pages.

## Structure

| File | Page |
|------|------|
| `index.html` | Home / About |
| `experience.html` | Professional & research experience |
| `education.html` | Degrees, achievements, certifications |
| `projects.html` | Projects, patents, publications |
| `skills.html` | Technical skills |
| `contact.html` | Contact details |
| `style.css` | Shared styles |
| `assets/profile.png` | Profile photo |

## Updating content

Edit the HTML files directly (each section is a `card` block), commit, and push — changes go live automatically.

<!-- rebuild trigger -->
