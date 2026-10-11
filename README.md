# Benlu Wang — personal homepage

Live site: https://benluwang.github.io/

A static academic homepage inspired by the structure of https://aafrostnova.github.io/.
No package installation or build step is required.

## Edit and preview

- Edit biography, news, publications, education, and teaching in `index.html`.
- Edit the layout and colors in `style.css`.
- `script.js` highlights the current navigation section. All links work without JavaScript.
- Run `python3 -m http.server 8765 --bind 127.0.0.1` in this directory, then visit http://127.0.0.1:8765/.

GitHub Pages serves the root of the `main` branch. A `.nojekyll` file keeps it buildless.
Push changes to `main` to update the site.

## Private visitor analytics

Umami Cloud collects pageviews, traffic referrers, and approximate country/region/city.
Open https://cloud.umami.is/analytics/us/websites with the owner's account to view
the homepage's Overview and Realtime tabs. Keep Share URLs disabled and the website
in the personal workspace to keep the dashboard private. No public counter or
analytics credentials are included in the homepage; the public website ID only
identifies where the tracker sends visits.

The tracker runs only on `benluwang.github.io`, excludes section hashes from page
URLs, and respects browser Do Not Track. Local previews are not counted. Ad blockers
and browser privacy settings may prevent collection. Referrers may be unavailable,
and IP-derived locations are approximate; these metrics do not identify visitors
by name. Analytics begins when the script is deployed, and setup verification
visits are included in the first counts.

The Hobby plan is free for one website, with 100K events per month and six months
of data retention (see https://umami.is/pricing for current limits).

## Photo and publication figures

The profile photo is the supplied original, copied without rewriting or adding metadata.
CSS frames a 720×900 region at approximately x=480, y=698 from the 1280×2812 source.
The 4:5 head-and-shoulders composition places the eyes near 38% of the frame height,
with the face slightly right of center and autumn scenery on the left.
The same framing scales to desktop and mobile; the original face and expression are preserved.

Publication figures come from the corresponding public papers or author repositories:

- MedQA-MM: Figure 8, https://arxiv.org/html/2609.03261v2/images/MEDQA_MM.png
- MedThinkVQA: Figure 1, https://raw.githubusercontent.com/benluwang/MedThinkVQA/main/assets/figure1.png
- CPTCoder: Figure 1, page 2, https://aclanthology.org/2026.acl-demo.60.pdf
- From Scores to Steps: Figure 3, page 5, https://aclanthology.org/2025.emnlp-main.548.pdf

Paper figures retain the rights and licensing of their original publications.

## Content sources

- UMass BioNLP people: https://bio-nlp.github.io/pages/people.html
- ZJUI profile and Class of 2024: https://zjui.intl.zju.edu.cn/news/2664
- Yale graduate-study history: https://zonghai-yao.github.io/assets/pdf/Zonghai_Yao_CV.pdf
- MedQA-MM venue and authors: https://arxiv.org/abs/2609.03261
- ICLR proceedings: https://proceedings.iclr.cc/paper_files/paper/2026/hash/a7060588538c3ca1ef2fb071db9e5630-Abstract-Conference.html
- ICLR 2026 Poster presentation: https://iclr.cc/virtual/2026/poster/10008091
- CPTCoder: https://aclanthology.org/2026.acl-demo.60/
- From Scores to Steps: https://aclanthology.org/2025.emnlp-main.548/
- EMNLP 2025 Oral presentation: https://arxiv.org/abs/2509.16584

No advisor title, degree conferral date, CV download, or private project link is inferred.
