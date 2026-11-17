# Homepage content and assets

Updated on November 18, 2026. All visible homepage copy is in English.

## Personal information

Education dates, the Qiyuan Laboratory experience, the contact email, research
interest, and honors were supplied by Ziyang Ding. The About Me text is an
editable academic biography based on those details. The supervisors, Zhen Zhao
(Shanghai AI Laboratory) and Yichao Yan (Shanghai Jiao Tong University), and the
Statistics bachelor's major were also supplied by Ziyang Ding. Supervisor names
link to their supplied homepages. The doctorate's 2031 completion date is marked
expected.

## Publications

The five entries and their order were checked against the
[Google Scholar profile sorted by date](https://scholar.google.com/citations?user=SuFIjWQAAAAJ&hl=en&sortby=pubdate&pagesize=100).
The title, year, author list, and equal-contribution notation follow the profile.
The list is split into Selected and Others. Selected follows the requested
newest-first order: CoLVR, Q-Flow (CIKM), then KARL, using `selected_order`.
Others sorts the `sort_date` fields descending: UniAfford, then Unbiased Top-k
Estimation. These fields are ordering keys; only the publication year is
displayed. KARL is listed as a 2026
preprint in the profile, although its original arXiv submission was in 2025.

| Work | Primary sources | Local thumbnail |
| --- | --- | --- |
| Q-Flow | [Official CIKM program](https://cikm2026.diag.uniroma1.it/cikm-program/CIKM2026_program.html), [ACM DOI](https://doi.org/10.1145/3799682.3841002) | `assets/img/publications/q-flow.png`: method framework uploaded by Ziyang Ding on November 18, 2026; white page margins trimmed. The paper link uses its verified DOI. |
| UniAfford | [arXiv](https://arxiv.org/abs/2609.37264), [project](https://4dvlab.github.io/UniAfford/) | `assets/img/publications/uniafford.png`: method framework, Figure 2, PDF page 5. |
| Unbiased Top-k Estimation | [arXiv](https://arxiv.org/abs/2609.34447) | `assets/img/publications/on-policy-distillation.png`: TT-OPD method framework, Figure 1, PDF page 1. |
| CoLVR | [arXiv](https://arxiv.org/abs/2605.08802), [author repository](https://github.com/Oscar-dzy/CoLVR) | `assets/img/publications/colvr.png`: method framework, Figure 2, PDF page 5. NeurIPS acceptance is confirmed in the arXiv comments. |
| KARL | [arXiv](https://arxiv.org/abs/2503.12797), [author repository](https://github.com/thunlp/KARL) | `assets/img/publications/karl.png`: Figure 1, PDF page 2, as requested, showing the knowledge-grounding gap and benchmark comparison. |

PDF thumbnails are rendered from the original PDFs, then cropped to the original
figures with page margins and captions removed. All five thumbnails are
1200 px wide and displayed at a shared responsive width with their natural
aspect ratios; there is no fixed-height white frame. They are not generated
illustrations. A first-party coauthor
[publication list](https://zhaozhen.me/publications/) additionally confirms the
Q-Flow oral presentation. Logos and paper illustrations belong to their
respective institutions and authors.

## Portrait and institution logos

- Portrait: [public Scholar profile photograph](https://scholar.googleusercontent.com/citations?view_op=view_photo&user=SuFIjWQAAAAJ&citpid=6).
- Shanghai Jiao Tong University: [official emblem SVG](https://www.sjtu.edu.cn/resource/assets/img/svg/Min-logo-pic.svg), rasterized to `assets/img/logos/sjtu.png`.
- Shandong University: [official logo SVG](https://www.sdu.edu.cn/images/logo.svg), cropped to its emblem and displayed in burgundy as `assets/img/logos/shandong-university.png`.
- Shanghai AI Laboratory: [official wordmark](https://www.shlab.org.cn/static/asset/2025/imgs/logo.webp), cropped to its symbol and displayed in blue as `assets/img/logos/shanghai-ai-lab.png`.
- Qiyuan Laboratory: [official recruitment site](https://qiyuanzp.zhiye.com/), whose configuration points to the [original logo](https://portal-oss.zhiye.com/607793/image/ddc3e99b-eb3c-4e38-8093-562956fd2394.png). Its symbol is cropped into `assets/img/logos/qiyuan-laboratory.png`.

## News and section order

The September 2026 NeurIPS acceptance and August 2026 CIKM acceptance were
supplied by Ziyang Ding. News remains above Publications; Education and
Internships & Collaborations follow Publications.

## Editing and building

- Identity and sidebar links: `_config.yml`.
- Biography and research interest: `index.md`.
- Structured entries: `_data/education.yml`, `_data/experience.yml`,
  `_data/publications.yml`, and `_data/honors.yml`.
- Content styles: `assets/css/profile.css`; the template's original Crimson Pro
  font and serif setting are retained.
- Build with `bundle install` followed by `bundle exec jekyll build`.
- `html_source_file/` contains a synchronized static export for preview or
  static-only hosting; its content and assets match the Jekyll build.
- The CV PDFs are unchanged. LinkedIn and X icons are commented out.
- Browser verification: the Jekyll build succeeds; the desktop (1280 px) and
  mobile (390 px) layouts show no horizontal overflow, all ten content images
  load, and the browser console reports no warnings or errors. Final captures
  are in `docs/screenshots/`.
