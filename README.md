# GitHub Pages Deployment Task

## Objective
Deploy a simple static HTML website using **GitHub Pages**.

---

## Steps Followed

1. **Created Project Files**
   - `index.html` (main webpage)
   - `style.css` (styling)

2. **Initialized Git Repository**
   ```bash
   git init
   git checkout -b main
   git add .
   git commit -m "Initial commit - simple GitHub Pages site"
   ```

3. **Pushed to GitHub**
   ```bash
   git remote add origin https://github.com/<username>/<repo-name>.git
   git push -u origin main
   ```

4. **Enabled GitHub Pages**
   - Go to **Repository → Settings → Pages**
   - Source: **Deploy from branch**
   - Branch: `main` and folder: `/root`
   - GitHub generated a live link.

---

## Deliverables

- **GitHub Repository:** [Repo Link](https://github.com/<username>/<repo-name>)
- **Live Website:** [Live Site](https://<username>.github.io/<repo-name>/)

---

## Screenshots (Optional)
_Add screenshots of your repo, settings, and live page here._

---

## Outcome
- Learned how to host static content for free using GitHub Pages.
- Created and styled a simple HTML website.
- Verified successful deployment through live link.
