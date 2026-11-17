# Manas College Google Review App

The direct Google review link supplied for Manas College is already configured:
https://g.page/r/Cbv2QStXe7pUEBM/review

## Features
- QR landing page with English/Hindi interface
- Keyword-based review draft generator and editable review text
- Star rating selector, copy button, and direct Google review link
- Admin panel, local usage counters, CSV export
- QR code generator for the hosted website URL
- Responsive design; works as a static GitHub Pages website

## Run locally
Extract the ZIP and open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and this README to the repository root.
3. Open repository Settings -> Pages.
4. Choose Deploy from a branch, select `main` and `/(root)`, then Save.
5. After deployment, open the public HTTPS website.
6. Click Admin access at the bottom, enter the deployed website URL under QR code, and generate/download the QR.
7. Print that QR and place it around the college.

## Important Google limitation
The app opens the supplied Google review page, but it cannot paste or publish a review automatically, bypass Google sign-in, or press Google's Post button. The visitor must review/edit the draft, paste it into Google if needed, and submit it themselves. Ask for honest feedback only; do not incentivize or filter reviews based on whether they are positive.

## Privacy / storage
No visitor name, phone number, email, or student details are collected. Admin counters and link settings use browser localStorage on that device only. Counts are not verified Google review totals and do not sync across devices.


## Review draft variation
The offline app now rotates between multiple Hindi/English review-writing patterns, uses the visitor's selected keywords and optional detail, and avoids repeating the immediately previous template. This is a local variation engine, not a live generative-AI API; no AI key or paid API is required. The visitor can edit every draft. The Google button opens the configured Google review page immediately (without waiting for clipboard copying). It also attempts to copy the current draft; the visitor still pastes/checks it and submits it themselves.
