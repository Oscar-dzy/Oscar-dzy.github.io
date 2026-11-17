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

The Chinese name 丁子杨 was supplied by Ziyang Ding and appears beside the
English name in About Me. It uses a self-hosted three-character subset of
[Ma Shan Zheng](https://github.com/googlefonts/mashanzheng), a brush-calligraphy
font distributed through Google Fonts under the SIL Open Font License.
The license is included at `assets/fonts/OFL-MaShanZheng.txt`. The rest of the
page retains Crimson Pro.

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
| CoLVR | [arXiv](https://arxiv.org/abs/2605.08802), [author repository](https://github.com/Oscar-dzy/CoLVR), [project page](https://oscar-dzy.github.io/CoLVR-project-page/) | `assets/img/publications/colvr.png`: method framework, Figure 2, PDF page 5. NeurIPS acceptance is confirmed in the arXiv comments. The project link is a Project Page text button matching UniAfford, positioned after Code. |
| KARL | [arXiv](https://arxiv.org/abs/2503.12797), [author repository](https://github.com/thunlp/KARL) | `assets/img/publications/karl.png`: Figure 1, PDF page 2, as requested, showing the knowledge-grounding gap and benchmark comparison. |

PDF thumbnails are rendered from the original PDFs, then cropped to the original
figures with page margins and captions removed. All five thumbnails are
1200 px wide. The previews share a responsive 3:2 aspect ratio and use
`object-fit: cover`, with focal positions for Q-Flow, KARL, and TT-OPD.
This keeps preview sizes consistent without adding blank padding or stretching
the figures. Clicking a preview opens the unchanged full figure in a new tab;
paper titles and publication buttons retain their original destinations.
Selected and Others have pale-yellow heading bars. They are not generated
illustrations. The author name Zitang Gou in Unbiased Top-k Estimation was
corrected as supplied by Ziyang Ding. Corresponding authors are marked with
superscript daggers as supplied by Ziyang Ding: Zhen Zhao (CoLVR and Unbiased
Top-k Estimation), Lei Bai (Q-Flow), Chi Chen and Derek F. Wong (KARL), and
Yuexin Ma (UniAfford). Linjian Meng and Siyuan Gan share the equal-contribution
asterisk in Unbiased Top-k Estimation; KARL's existing equal-contribution
asterisks are retained. Both symbols are explained above the publication list.
A first-party coauthor
[publication list](https://zhaozhen.me/publications/) additionally confirms the
Q-Flow oral presentation. Logos and paper illustrations belong to their
respective institutions and authors.

## Portrait and institution logos

- Portrait: the replacement photograph supplied by Ziyang Ding on November 18, 2026, stored unchanged as `assets/img/ziyang-ding-portrait.jpg`.
- Shanghai Jiao Tong University: [official emblem SVG](https://www.sjtu.edu.cn/resource/assets/img/svg/Min-logo-pic.svg), rasterized to `assets/img/logos/sjtu.png`.
- Shandong University: [official logo SVG](https://www.sdu.edu.cn/images/logo.svg), cropped to its emblem and displayed in burgundy as `assets/img/logos/shandong-university.png`.
- Shanghai AI Laboratory: [official full stacked logo](https://www.shlab.org.cn/static/img/logo_2.5957e86a.webp), stored unchanged as `assets/img/logos/shanghai-ai-lab-complete.webp`. The full emblem, Chinese name, and English name are visible. This replaces the previous symbol-only crop.
- Qiyuan Laboratory: [official recruitment site](https://qiyuanzp.zhiye.com/), whose configuration points to the [original logo](https://portal-oss.zhiye.com/607793/image/ddc3e99b-eb3c-4e38-8093-562956fd2394.png). Its symbol is cropped into `assets/img/logos/qiyuan-laboratory.png`.

## Personal favicon

Ziyang Ding selected concept 01, **ZD Monogram**, on November 18, 2026.
The original vector artwork is `assets/img/zd-favicon.svg`: ivory ZD initials
on a midnight-blue rounded square, with transparent outer corners. It was
chosen from five favicon concepts prepared for the homepage.
Native SVG rasterization supplies the PNG assets. After a reported Safari
display issue, ordinary tab icons use explicit 16, 32, and 48 px PNG files
at the site root, plus a classic bitmap ICO containing 16, 32, 48, and
64 px frames. `favicon.ico` and `favicon-v2.ico` contain the same icon.
The root `apple-touch-icon.png` is an opaque 180 px PNG. A separate
`safari-pinned-tab.svg` supplies a black ZD silhouette on transparency with
a 16 × 16 viewBox, following Apple's
[pinned tab icon specification](https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/pinnedTabs/pinnedTabs.html).
The page uses root-relative, versioned icon URLs (`v=zd2`) so the new icon
resources can bypass previous cached URLs. SVG remains the vector master;
it is not offered as the ordinary tab favicon. Light and dark browser
themes share the selected design; the template favicon switcher is no
longer loaded. Native Safari display still requires checking in Safari;
HTTP and document checks alone do not establish that its UI refreshed.

## News and section order

The September 2026 NeurIPS acceptance and August 2026 CIKM acceptance were
supplied by Ziyang Ding. News remains above Publications; Education and
Internships & Collaborations follow Publications. Each acceptance news item
has exactly two decorative 🎉 icons immediately after the date and before
the acceptance sentence, hidden from assistive technology. The News heading
has no icons.

## Editing and building

- Identity and sidebar links: `_config.yml`.
- Biography and research interest: `index.md`.
- Structured entries: `_data/education.yml`, `_data/experience.yml`,
  `_data/publications.yml`, and `_data/honors.yml`.
- Content styles: `assets/css/profile.css`; the template's original Crimson Pro
  font and serif setting are retained.
- The profile stylesheet URL includes the Jekyll build timestamp so published
  font and layout changes refresh cached browser styles automatically.
- Build with `bundle install` followed by `bundle exec jekyll build`.
- `html_source_file/` contains a synchronized static export for preview or
  static-only hosting; its content and assets match the Jekyll build.
- The CV PDFs are unchanged. LinkedIn and X icons are commented out.
- Browser verification: the Jekyll build succeeds; the desktop (1280 px) and
  mobile (390 px) layouts show no horizontal overflow, all ten content images
  load, and the browser console reports no warnings or errors. Final captures
  are in `docs/screenshots/`.
