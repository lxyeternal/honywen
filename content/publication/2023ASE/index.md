---
title: "An Empirical Study of Malicious Code In PyPI Ecosystem"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zhengzi Xu
- Chengwei Liu
- Cheng Huang
- Yong Fang
- Yang Liu

# Author notes (optional)
author_notes:
- ""
- "corresponding"
- ""
- "corresponding"

date: "2023-07-18T00:00:00Z"
doi: '10.48550/arXiv.2309.11021'

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 38th IEEE/ACM International Conference on Automated Software Engineering*
publication_short: In *ASE 2023*

abstract: We conducted an empirical study to understand the characteristics and current state of the malicious code lifecycle in the PyPI ecosystem. We first built an automated data collection framework and collated a multi-source malicious code dataset containing 4,669 malicious package files. We preliminarily classified these malicious code into five categories based on malicious behaviour characteristics. Our research found that over 50% of malicious code exhibits multiple malicious behaviours, with information stealing and command execution being particularly prevalent. In addition, we observed several novel attack vectors and anti-detection techniques. Our analysis revealed that 74.81% of all malicious packages successfully entered end-user projects through source code installation, thereby increasing security risks. A real-world investigation showed that many reported malicious packages persist in PyPI mirror servers globally, with over 72% remaining for an extended period after being discovered. Finally, we sketched a portrait of the malicious code lifecycle in the PyPI ecosystem, effectively reflecting the characteristics of malicious code at different stages. We also present some suggested mitigations to improve the security of the Python open-source ecosystem.

# Summary. An optional shortened abstract.
summary: 

tags: [PyPI Ecosystem, Software Supply Chain Security]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0167404822002176'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 2023ASE
---

