# AI Contract Hub: Review Studio

Complete source of the current bilingual UI/UX prototype. HTML, CSS and JavaScript are contained in `index.html`. No package installation or build step is required.

## Run locally

Open `index.html` in a modern browser. For a local web server, run `python3 -m http.server 8000` in this folder, then visit http://localhost:8000. Clipboard access may require HTTPS or localhost.

## Publish with GitHub Pages

1. Extract this ZIP.
2. Upload `index.html` to the root of your GitHub repository. Upload the file, not the ZIP.
3. Open Settings > Pages.
4. Choose Deploy from a branch, then main and /(root).
5. Save and wait for deployment. Open the URL shown in Pages.

If your repository already has a README, merge this documentation rather than overwriting the existing README.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## What is included

- Responsive overview, new review and sample review library screens.
- Arabic and English interface with RTL support.
- PDF/DOCX file selection and text input.
- Simulated processing, sample findings and risk filters.
- Original quotations with Arabic translations in Arabic mode.
- Suggested wording and sample text report download.

## Current functionality boundary

This is an interactive frontend prototype. It does not extract uploaded contracts, run an AI model, or send files to n8n. Results are predefined examples. It has no backend, authentication or persistent review history. Browser file selection is local. No API key is required.

To enable real review, replace the processing simulation in `start()` with a request to a secured backend/n8n integration and replace the static findings with the returned review. Keep model API keys on the server. An n8n workflow export is not part of this package.

## تعديل التصميم

كل الكود داخل index.html. التنسيق موجود داخل style، والمنطق والتفاعلات داخل script. ارفع index.html نفسه إلى GitHub وليس ملف ZIP. النموذج لا يحتاج تسجيل دخول إلى ChatGPT عند تشغيله محليًا أو استضافته على GitHub Pages.

## Team

CAI5_IND6_G1, Group (2)

- Eman Mohamed Mahmoud Khodry
- Ahmed Abdullah Ali Elbana
- Ahmed Saied Ali Elmezayen
- Mazen Moustafa Elsayed Mohammed
- Mohamed Alm ElDin Ahmed Ammar
- Fady Medhat Beshay Ebrahim
