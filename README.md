# Saqlain Shah — Portfolio

Live site: https://saqlainshahx01.github.io/portfolio

This repository holds a static HTML/CSS/JS portfolio for Saqlain Shah.

Quick links
- Home: `index2.html`
- Resume viewer: `resume.html` (embeds `resume.pdf`)

Run locally
1. From the project root:
```bash
python3 -m http.server 8000
# open http://localhost:8000/index2.html
```

How to update the resume
1. Replace `resume.pdf` in the project root with your updated PDF.
2. Commit and push:
```bash
git add resume.pdf
git commit -m "Update resume"
git push
```

Edit the prefilled email message
- Open `index2.html` and find the `handleEmailClick` function.
- Update the `body` text to change the default message and placeholders.

Deploy notes
- The site uses GitHub Pages (branch `main`, root). After pushing changes it may take ~1–2 minutes to update.
- Enable "Enforce HTTPS" in the Pages settings if not already enabled.

Contact
- Email: shahsaqlain622@gmail.com

---
Generated and added to the repo by a local tooling assistant.
