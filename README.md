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

- **GitHub Repository:** [Repo Link](https://github.com/deep0304/elevate-task6)
- **Live Website:** [Live Site](https://deep0304.github.io/elevate-task6/)

---

## Screenshots 

<img width="797" height="621" alt="image" src="https://github.com/user-attachments/assets/2f66ba67-bd73-4f85-abcb-d2f703c999e6" />


---

## Outcome
- Learned how to host static content for free using GitHub Pages.
- Created and styled a simple HTML website.
- Verified successful deployment through live link.
