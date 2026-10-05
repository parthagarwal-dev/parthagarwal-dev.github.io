# Parth Agarwal — Academic Website

Static academic website for the existing GitHub Pages repository `parthagarwal-dev.github.io`.

## Update the existing site

1. Open the existing repository on GitHub.
2. Choose **Add file → Upload files**.
3. Upload the files inside this folder to the repository root. Upload the files themselves, not the ZIP or an enclosing folder.
4. Replace `index.html`, `styles.css`, and `README.md` with the revised versions and commit the changes.
5. Keep `Parth_Agarwal_CV.pdf`, `robots.txt`, and `sitemap.xml` at the root. Copies are included for a complete package.

The existing GitHub Pages configuration can continue to serve the repository. After deployment completes, reload the website. If old styles remain cached, use a hard refresh.

## Files

- `index.html` — all page content; starts with Dr. Haohan Wang, then Dr. Fenglong Ma, then Dr. Suman Saha and the paper link.
- `styles.css` — responsive typography and layout; no JavaScript, external fonts, or build step required.
- `Parth_Agarwal_CV.pdf` — supplied CV, unchanged. Linked at the repository root.
- `robots.txt` and `sitemap.xml` — existing indexing files, unchanged.

## Content notes

- The supplied CV dates the Fenglong Ma research appointment September 2025–August 2026. This version preserves those dates and uses past tense. Update the date and wording together if the appointment is ongoing.
- The site uses “Dr.” throughout its prose. The original PDF is unchanged.
- The gait paper title follows arXiv: **Explainable Gait Abnormality Detection Using Dual-Dataset CNN-LSTM Models** (plural “Models”). Source: https://arxiv.org/abs/2509.16472.
- Ongoing scientific-agent work and the planned adaptation thesis are labeled by status. The in-preparation manuscript is described within the research entry rather than listed as a published paper.
- EHR research descriptions do not claim numerical improvements, completed clinical deployment, or patient outcomes.
- AutoDrive placements are attributed to the team. No competition year is inferred from the conflicting “Year 3 / June 2024” wording in the CV.
- SURE appears briefly with the associated research and is described separately under Honors & Research Funding.
- Teaching, tutoring, grading, professional service, Nittany AI Advance, and AutoDrive are included.
- No headshot, unpublished poster, or private repository link has been invented.

## Editing

Edit the corresponding semantic section in `index.html`. Anchor IDs are stable: `research`, `wang`, `ma`, `saha`, `publications`, `honors`, `sure`, `experience`, `teaching`, `news`, and `contact`.

Open `index.html` directly to preview locally, or run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.
