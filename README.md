# Parth Agarwal — Academic Website

Static academic portfolio for the existing GitHub Pages repository `parthagarwal-dev.github.io`.

## Update GitHub Pages

1. Extract `parth-academic-website.zip`.
2. Open your existing `parthagarwal-dev.github.io` repository on GitHub and choose **Add file → Upload files**.
3. Upload **all the extracted files and the entire `assets` folder** into the repository root. Do not upload the ZIP itself or place the website inside an extra enclosing folder.
4. Commit the changes. This update includes four new research pages and images, so replacing only `index.html` and `styles.css` is insufficient.
5. Wait for the repository's Pages deployment to finish in **Actions**, then reload your website. If an old version remains visible, hard-refresh the page.

Keep the existing GitHub Pages configuration. No production build or JavaScript runtime is required; Pages serves the HTML and CSS directly. The included CV is unchanged.

## Website files

- `index.html`: concise introduction; prominent Fall 2027 PhD availability; research summaries; publications and presentations; AVT; honors and funding; technical experience; teaching and service; updates and contact.
- `research-agents.html`: scientific-agent research with Dr. Haohan Wang, technical contributions, and RECOMB 2027 submission status.
- `research-ehr.html`: multimodal EHR research with Dr. Fenglong Ma and the SURE fellowship.
- `research-gait.html`: explainable gait research with Dr. Suman Saha, with the ICMLA 2025 paper link.
- `research-security.html`: SyNSec work with Dr. Syed Rafiul Hussain and NSF-supported research contribution.
- `styles.css`: shared responsive styles.
- `assets/`: AVT team photograph and three original explanatory SVG diagrams.
- `Parth_Agarwal_CV.pdf`: supplied CV, unchanged.
- `sitemap.xml`: all five public pages.
- `robots.txt`: indexing configuration.
- `package.json`, `package-lock.json`, and `vite.config.js`: optional local preview tooling, not required by GitHub Pages.

## Content and status notes

- Faculty appear in the requested order: Wang, Ma, then Saha. Their names link to official personal sites or faculty profiles. Hussain is linked in the security project.
- RECOMB 2027 is labeled **“Manuscript under submission”**, following the supplied status. It is not described as accepted or published. No unpublished manuscript title or public paper link has been invented. Update the status when it changes.
- The supplied CV dates the Ma research appointment September 2025–August 2026. These dates and past-tense wording are preserved. The SURE fellowship is identified separately as May–July 2026.
- The NSF item is **recognized research contributor to an NSF-supported project**, not a personal NSF grant or fellowship award. The recognition follows the supplied CV; the linked public records verify the award and project rather than an individual contributor roster.
- The gait paper title follows arXiv: **Explainable Gait Abnormality Detection Using Dual-Dataset CNN-LSTM Models**. https://arxiv.org/abs/2509.16472
- The diagrams explain research approaches. They are not experimental results, clinical outcome claims, or official conference figures. They can be opened at full size from the project pages.
- The planned adaptation thesis remains clearly labeled as a planned direction.
- Teaching, tutoring, grading, ICTAI service, Nittany AI Advance, SURE, College of Engineering funding, and AVT are retained.

## AVT image and results

The AVT section includes a 2024 team photograph and links to the team's website and Penn State's report, which names Parth Agarwal among the competition team members.

- Team: https://www.avt.psu.edu/
- Penn State report: https://news.engr.psu.edu/2024/avt-2024-autodrive-challenge-ii.aspx
- Image source: https://news.engr.psu.edu/assets/images/2024/avt-2024-autodrive-challenge-ii.jpg
- Photo credit: Penn State Advanced Vehicle Team, via Penn State Engineering. The photograph retains the original owner's rights.
- SAE results: https://www.autodrivechallenge.com/cdsweb/app/NewsItem.aspx?NewsItemID=553b141f-8523-47a6-88ed-416850410eab

The site includes the consistent results: **third overall** and **second in Intersection** for AutoDrive Challenge II Year 3 (2024). Construction placement is omitted pending clarification: the supplied CV says second, Penn State's report says third, and SAE's published podium lists other teams. Competition results are attributed to the team.

## NSF references

- Award 2215017: https://www.nsf.gov/awardsearch/showAward?AWD_ID=2215017
- Penn State project record: https://pure.psu.edu/en/projects/collaborative-research-cns-core-large-systems-and-verifiable-metr/
- Project: **Collaborative Research: CNS Core: Large: Systems and Verifiable Metrics for Sustainable Data Centers**.

## Editing and preview

Edit the relevant HTML page directly. Shared styling is in `styles.css`. Preserve the `assets` directory and relative file paths.

Homepage anchors include `research`, `wang`, `ma`, `saha`, `security`, `publications`, `avt`, `honors`, `sure`, `experience`, `teaching`, `news`, and `contact`.

For a local preview, open `index.html` in a browser, or install the optional preview dependencies with `npm ci` and run `npm run dev`. Follow the local URL printed by Vite. Do not upload `node_modules`.
