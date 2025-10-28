# Personal Portfolio with CI/CD Deployment

This repository contains my personal portfolio website, built with HTML & CSS. It is automatically deployed to GitHub Pages using a CI/CD pipeline built with **GitHub Actions**.

## ✨ Live Website URL

**You can view the live portfolio here:**
**[https://KunalSingh005.github.io/gh-deployment-workflow/](https://KunalSingh005.github.io/gh-deployment-workflow/)**

---

## CI/CD Workflow

This project uses a GitHub Actions workflow defined in `.github/workflows/deploy.yml`.

* **Trigger:** The workflow is automatically triggered on every `push` to the `main` branch **if (and only if)** the `index.html` file is modified.
* **Action:** It builds the static site and deploys it to the `gh-pages` branch, making it live on GitHub Pages.

This project demonstrates a practical understanding of CI/CD principles for automated deployment.

## Tech Stack

* **Frontend:** HTML5, CSS3
* **DevOps:** GitHub Actions, CI/CD, YAML
* **Platform:** GitHub Pages
