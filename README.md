# ci-cd-lab
Ultra-simple CI/CD demo: HTML + Azure Static Web Apps
# Ultra-Simple CI/CD Lab — Smart Campus Demo

## Objective
Demonstrate CI/CD by deploying a single `index.html` to **Azure Static Web Apps (SWA)** from a GitHub repository using GitHub Actions. Students will make a tiny change, push, and watch the live site update automatically.

---

## Files in this repo
- `index.html` — single-page app (Tailwind CDN).
- `.github/workflows/static-html-ci-cd.yml` — sample GitHub Actions workflow for Azure SWA.

---

## Quick start (student steps)

1. **Fork or clone** this repository to your GitHub account:
   ```bash
   git clone git@github.com:<your-username>/ci-cd-lab.git
   cd ci-cd-lab
