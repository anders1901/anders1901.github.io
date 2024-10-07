---
title: "Uncompressing Dilithium's public key"
authors:
- Paco Azevedo Oliveira
- admin
- Benoît Cogliati
- Louis Goubin
date: "2024-09-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The Dilithium signature scheme – recently standardized by NIST under the name ML-DSA – owes part of its success to a specific mechanism that allows an optimizaion of its public key size. Namely, among the data of the MLWE instance (**A**,**t**), which is at the heart of the construction of Dilithium, the least significant part of **t** -- denoted by  **t**<sub>0</sub> -- is not included in the public key. The verification algorithm had been adapted accordingly, so that it should not require the knowledge of  **t**<sub>0</sub>. However, since it is still required to compute valid signatures, it has been made part of the secret key. The knowledge of  **t**<sub>0</sub> has no impact on the black-box cryptographic security of Dilithium, as can be seen in the security proof. Nevertheless, it does allow the construction of much more efficient side-channel attacks. Whether it is possible to recover  **t**<sub>0</sub> thus appears to be a sensitive question. In this work, we show that each Dilithium signature leaks information on  **t**<sub>0</sub>, then we construct an attack that retrieves it from Dilithium signatures. Experimentally, depending on the Dilithium security level, between 200 000 and 500 000 signatures are sufficient to recover  **t**<sub>0</sub> on a desktop computer.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Dilithium
- Public Key
- Partial Key Recovery


links:
- name: ePrint
  url: https://eprint.iacr.org/2024/1373
url_pdf: https://eprint.iacr.org/2024/1373.pdf
url_code: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ''
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

reading_time: false
---