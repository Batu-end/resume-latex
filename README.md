# LaTeX Resume 📄

[![Compile LaTeX Resume](https://github.com/Batu-end/resume-latex/actions/workflows/compile.yml/badge.svg)](https://github.com/Batu-end/resume-latex/actions/workflows/compile.yml)

A LaTeX-based resume with an automated CI/CD pipeline. Every change made to the LaTeX source file is automatically compiled into a PDF and committed back to the repository.

## 🚀 Direct PDF Link

You can always find the latest compiled PDF here:
👉 **[Download resume.pdf](https://github.com/Batu-end/resume-latex/raw/main/resume.pdf)**

---

## 🛠️ How It Works

This repository uses **GitHub Actions** to compile the LaTeX resume on every push:
1. You make edits to [resume.tex](file:///Users/batu/Desktop/resume-latex/resume.tex).
2. You commit and push the changes to the `main` branch.
3. GitHub Actions triggers the [compile.yml](file:///Users/batu/Desktop/resume-latex/.github/workflows/compile.yml) workflow:
   - Sets up a LaTeX compilation environment.
   - Compiles `resume.tex` into `resume.pdf`.
   - Commits the updated `resume.pdf` back to the repository automatically.

This ensures you don't need to install or maintain heavy LaTeX distributions (like MacTeX) locally.

---

## ✍️ Updating Your Resume

1. Open [resume.tex](file:///Users/batu/Desktop/resume-latex/resume.tex) in your editor.
2. Update your education, experience, skills, or projects.
3. Commit and push the changes:
   ```bash
   git add resume.tex
   git commit -m "Update professional experience"
   git push origin main
   ```
4. Wait about 30–60 seconds for the GitHub Action to run, and your updated PDF will be live!
