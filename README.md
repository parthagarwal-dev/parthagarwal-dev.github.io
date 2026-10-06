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
- The planned undergraduate thesis remains clearly labeled as planned. Its materials science application domain and advisor, Dr. Lu Lin, follow Parth’s October 6 update. Her linked homepage verifies her faculty affiliation; it is not evidence of this individual thesis arrangement.
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

Homepage anchors include `research`, `wang`, `ma`, `saha`, `security`, `publications`, `avt`, `honors`, `sure`, `experience`, `nittany-ai`, `thesis`, `teaching`, `service`, `interests`, `news`, and `contact`.

For a local preview, open `index.html` in a browser, or install the optional preview dependencies with `npm ci` and run `npm run dev`. Follow the local URL printed by Vite. Do not upload `node_modules`.


## October 6 academic portfolio update

- Teaching appears immediately after publications. Two current teaching assistant appointments are followed by three learning assistant roles, grading, and mathematics peer tutoring at the end. Each course has a concise subject overview, a separate account of Parth’s role, and an official course link. Course scope follows the Penn State catalogue; responsibilities and dates follow the supplied CV.
- Professional service has its own section and navigation link. The ICTAI 2026 committee page explicitly lists Parth Agarwal, Pennsylvania State University: https://ictai.computer.org/2026/program-committee-members/
- Engineering funding is highlighted as a $4,000 research award. Competitive selection and recognition of research potential follow the supplied CV; no acceptance rate, ranking, or specific donor name has been inferred. The general engineering research link provides institutional context, not an individual award announcement.
- SURE highlights selection for a funded, ten-week full-time research fellowship and links to the official program. The program website currently describes a later application cycle; the portfolio retains the supplied 2026 fellowship dates and does not infer a personal stipend amount from that page.
- Research interests connect scientific agents, multimodal clinical learning, and reliability/interpretability to the existing projects.
- The uploaded MMLS poster is included unchanged as `MMLS_Poster_Parth_Ag.pdf`, with a rendered preview at `assets/mmls-poster-2026.jpg`. The displayed title now follows the poster itself: “General-Purpose Agentic Framework for Biomedical Research.” MMLS 2026 was held June 24–25 at Purdue: https://midwest-ml.org/2026/
- Nittany AI Advance now includes the program link, project partner, technical responsibilities, and delivery details from the supplied CV. Its description does not claim a public project repository or measurable outcomes that were not supplied. Program: https://nittanyai.psu.edu/programs/advance

Upload the revised HTML files, `styles.css`, and the poster PDF to the repository root; upload the new poster preview inside `assets`. The complete ZIP also includes all earlier site assets. Keep the folder structure intact.

## Teaching and page organization refinement

- The introduction now includes current teaching responsibilities. The homepage order is introduction, research interests, research projects, publications, teaching, honors/funding, professional service, technical experience, updates, and contact.
- AVT and Nittany AI Advance now sit together under Technical experience, with direct subsection links. The existing `#avt` link still works.
- Website contact details use `pxa5191@psu.edu` and `https://www.linkedin.com/in/parth-agarwal-965416311/`, as supplied by Parth. The uploaded CV PDF remains unchanged.
- The homepage requests CSS version `20261006f` for the updated opening summary. The project pages retain their existing stylesheet URL; their layout is unchanged.
- Official course references: https://bulletins.psu.edu/university-course-descriptions/undergraduate/ds/ ; https://bulletins.psu.edu/university-course-descriptions/undergraduate/cmpsc/ ; https://bulletins.psu.edu/university-course-descriptions/undergraduate/ist/ ; https://bulletins.psu.edu/university-course-descriptions/undergraduate/math/ .

## Learning assistant, thesis, and engineering refinement

- Learning assistant appointments use the same bordered course cards as teaching assistant appointments, preserving course descriptions, contributions, dates, and links. Grading and mathematics tutoring remain after these groups.
- The planned thesis under Dr. Lu Lin concerns an agentic workflow for reliable adaptation under structured distribution shift, with materials science as the application setting. It has a prominent research panel and a research navigation link. No completed experiments, results, dataset, or publication is claimed. Advisor homepage: https://louise-lulin.github.io/ .
- Technical experience now presents AVT first, followed by Nittany AI Advance. Solutions Engineer is a full-size heading matching the other engineering entry, with the linked program name immediately below it.

## Research evidence and thesis placement

- Research order: Wang → Ma → Saha → SyNSec → planned Lu Lin thesis. The planned thesis remains visibly labeled and has no invented dataset, experimental results, or publication.
- Wang’s role is explicitly an extension of the pre-existing HEART framework, following Parth’s earlier correction. Design rationale explains input contracts, reusable capabilities, and independent verification without claiming sole invention of the framework.
- Agent results are transcribed from the supplied MMLS poster’s overall benchmark: proposed framework / Biomni / GENIE3 / GRNBoost2 / Pearson / PPCOR AUROC = 0.6723 / 0.5612 / 0.5995 / 0.5626 / 0.5333 / 0.5149; AUPRC = 0.1211 / 0.0656 / 0.0539 / 0.0510 / 0.0425 / 0.0378. These describe the June presentation, not current RECOMB results or a component ablation. The 15-dataset label belongs to a separate poster panel and is not applied to the overall benchmark.
- EHR findings come from Parth’s uploaded August 25, 2026 V1 training/evaluation log, `Pasted text(20260825-052247).txt`. This is a single-seed comparison (seed 20260825) on 65,017 test prediction events, using standard training versus 20% modality dropout. Full-input AUROC: 0.6607727778 / 0.6616028125; Brier: 0.2328482252 / 0.2034559219; labs-removed AUROC: 0.6226649433 / 0.6409601719. AUROC drops: 0.0381078345 / 0.0206426406. Public tables round to four decimals. These are preliminary V1 findings, not a final model comparison, significance claim, or clinical validation.
- The evaluated EHR snapshot used five sources and note metadata, not narrative clinical text. The source schematic and project description now reflect that distinction. Clinical NLP remains a broader research interest. Earlier prototype scores and later unmatched/model-version results were not mixed into this table.
- Raw research logs, patient-level data, internal paths, and internal repositories are not included in the website package. EHRSHOT links identify upstream resources, not Parth’s own public code.

## Thesis framing and final research order

- Following Parth’s October 6 clarification, the thesis sits at the end of Research, after SyNSec, and is mentioned briefly in the introduction after Wang, Ma, and Saha. Research navigation follows the same order.
- The primary focus is an agentic workflow for reliable model adaptation under structured distribution shift. Materials science is the application setting, not the primary thesis category. The workflow and reliability signals are described as planned; no implementation or result is claimed.

## Opening summary and academic highlights

- The introduction keeps Wang first, gives Ma a separate paragraph, and adds Hussain and the NSF Award 2215017 contributor recognition. Saha’s paper link and the planned Lu Lin thesis remain visible.
- Concise, linked highlights now cover both conference presentations, current TA and earlier LA appointments, grading and tutoring, the $4,000 Engineering research award and funded SURE fellowship, ICTAI service, AVT, and Nittany AI Advance.
- The two conference items are ICMLA 2025 and MMLS 2026, following Parth’s request to highlight both presentations. Their detailed entries retain the distinction between a conference paper and a poster; the summary does not identify an individual speaker for ICMLA.
- No specific Hussain paper has been identified in the supplied CV or prior research records, so the summary uses the documented NSF contributor recognition without claiming authorship of an unidentified paper.
- The existing Research order remains Wang → Ma → Saha → SyNSec → planned thesis.
- For this summary update, `index.html` and `styles.css` contain the visible changes; `README.md` documents them. The ZIP retains every existing research page, PDF, and image.

## Portrait, affiliations, and highlights update

- The opening explicitly locates the work with Dr. Suman Saha, Dr. Syed Rafiul Hussain, and the planned thesis with Dr. Lu Lin at Penn State. Wang remains linked to UIUC; Ma’s research is described in its Penn State setting.
- The supplied AutoDrive photograph is included as `assets/parth-agarwal.png`. The original image bytes are preserved; CSS frames it as a portrait without changing facial features or retouching the image.
- Academic highlights use a restrained three-column layout on wide screens, two columns on tablets, and one column on phones, with concise descriptions, stronger titles, and direct links to the full sections.
- Visible changes are in `index.html`, `styles.css`, and `assets/parth-agarwal.png`. Upload the files from the update ZIP at the repository root, keeping the image inside `assets`. Existing project pages and other assets are retained.
- Fresh local references were validated. The browser blocked local-file previews, so this revision has not had a rendered browser check.
