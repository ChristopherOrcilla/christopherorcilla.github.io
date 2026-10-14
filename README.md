# Christopher Orcilla — recruiter portfolio

A mobile-friendly static website designed for GitHub Pages. Built with HTML, CSS, and a small amount of vanilla JavaScript. No paid hosting, npm, frameworks, build commands, or API keys required.

## Publish in 8 steps (no terminal required)

1. Sign into `https://github.com/ChristopherOrcilla`.
2. Go to `https://github.com/new` and create a **public** repository named exactly `christopherorcilla.github.io` (all lowercase). Add a README if you want.
3. Download `christopherorcilla-portfolio.zip` from ChatGPT and **extract** it on your computer. Do **not** upload the ZIP itself.
4. Open the extracted `christopherorcilla-portfolio` folder and **select all files and folders inside it**. These include `index.html`, `resume.html`, `404.html`, `assets`, and `projects`.
5. In your new GitHub repo click **Add file → Upload files**. Drag and drop everything selected in step 4 into the upload area. GitHub should show files including `index.html` at the repository root, and `assets/style.css` / `projects/operations-dashboard.html` in their folders. Do not nest the whole `christopherorcilla-portfolio` folder in the repo.
6. Click **Commit changes** and commit to the `main` branch.
7. Open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, then choose `main` and `/(root)`; click **Save**.
8. Visit `https://christopherorcilla.github.io`. If it isn't ready immediately, open the repository's **Actions** tab to check the deployment workflow. The Settings → Pages screen also shows the website link after publication.

GitHub Pages official guide: https://docs.github.com/en/pages/quickstart

## Files

```text
index.html                           # main landing page
resume.html                          # professional overview; print/save as PDF
404.html                             # friendly broken-link page
assets/style.css                     # all responsive styles
assets/site.js                       # mobile navigation and project filters
assets/favicon.svg                   # logo icon
assets/social-preview.png            # share preview image
projects/operations-dashboard.html   # Tableau operations analytics case study
projects/excel-data-cleaning.html    # cleaning + validation case study
projects/automated-reporting.html    # Python + Excel workflow case study
projects/attrition-intelligence.html # academic capstone case study
robots.txt, sitemap.xml, .nojekyll   # static website configuration
```

## Before sharing with recruiters

- Review the résumé overview in `resume.html`, especially job-title wording and education details; replace it or link your own current PDF résumé if preferred.
- Add an email address if you want direct email contact; currently LinkedIn and GitHub are working contact paths.
- The two *real* public repository URLs are already in the website: `ExcelDataCleaning` and `OperationsPerformanceDashboardAnalytics`.
- The automation and capstone pages are explicitly described as case studies; no fictional live product, clients, or performance gains are claimed.
- The charts shown as project preview illustrations are **conceptual**, not screenshots. Replace the illustrations with your own dashboard/Excel screenshots when you have approved images to share.
- The operations Tableau project uses **fictional** sample data; the site explicitly says so.
- Never upload proprietary lab data, HR records, personal emails, tokens, or client information to a public repository.

## How to preview it locally

Double-click `index.html` on your computer. All website files are local and have relative links. You can also run `python -m http.server 8000` in the extracted website folder and visit `http://localhost:8000`.

## Updating after launch

To update any page, go to that file in GitHub, click the pencil icon, edit, and **Commit changes**. GitHub Pages republishes changes from `main` automatically. Alternatively upload replacements using **Add file → Upload files**.

To swap in your real PDF résumé:
1. Upload your PDF into the `assets` folder (for example `assets/Christopher_Orcilla_Resume.pdf`).
2. Change the résumé buttons in `index.html` and header links on each page from `resume.html` to `assets/Christopher_Orcilla_Resume.pdf`. Links inside `projects/` should use `../assets/Christopher_Orcilla_Resume.pdf`.

## Current site links

- LinkedIn: https://www.linkedin.com/in/christopher-orcilla-datascience
- GitHub: https://github.com/ChristopherOrcilla
- Public Tableau / Excel projects: actual GitHub repo links, not placeholders

## No-cost details

GitHub Pages works for **public** repositories on GitHub Free. The live site itself is publicly reachable, so only publish files you want recruiters and the public to see.
