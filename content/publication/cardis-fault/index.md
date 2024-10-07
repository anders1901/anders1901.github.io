---
title: "Fault Attacks Sensitivity of Public Parameters in the Dilithium Verification"
authors:
- admin
- Alexandre Berzati
- Karine Heydemann
date: "2024-02-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Smart Card Research and Advanced Applications"
publication_short: "CARDIS 2023"

abstract: This paper presents a comprehensive analysis of the verification algorithm of the CRYSTALS-Dilithium, focusing on a C reference implementation. Limited research has been conducted on its susceptibility to fault attacks, despite its critical role in ensuring the scheme’s security. To fill this gap, we investigate three distinct fault models - randomizing faults, zeroizing faults, and skipping faults - to identify vulnerabilities within the verification process. Based on our analysis, we propose a methodology for forging CRYSTALS-Dilithium signatures without knowledge of the secret key. Instead, we leverage specific types of faults during the verification phase and some properties about public parameters to make these signatures accepted. Additionally, we compared different attack scenarios after identifying sensitive operations within the verification algorithm. The most effective requires potentially fewer fault injections than targeting the verification check itself. Finally, we introduce a set of countermeasures designed to thwart all the identified scenarios rendering the verification algorithm intrinsically resistant to the presented attacks.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Dilithium
- Digital signature
- Fault Attacks
- Side Channel Attacks
- Post Quantum Cryptography
- Lattice-based Cryptography
# featured: false

links:
- name: "ePrint"
  url: "https://eprint.iacr.org/2023/1796"
url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-54409-5_4
url_code: ''
url_slides: 'uploads/CARDIS_Andersson_CALLEVIERA.pdf'
url_video: 'https://youtu.be/WtQMezUVl1U?feature=shared&t=7525'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

profiles: []

profile: false

reading_time: false
---