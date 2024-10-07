---
title: "Exploiting intermediate value leakage in dilithium: a template-based approach"
authors:
- Alexandre Berzati
- admin
- Maya Chartouny
- Steven Madec
- Damien Vergnaud
- David Vigilant
date: "2023-08-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Transactions on Cryptographic Hardware and Embedded Systems"
publication_short: "CHES 2023"

abstract: This paper presents a new profiling side-channel attack on CRYSTALSDilithium, the new NIST primary standard for quantum-safe digital signatures. An open source implementation of CRYSTALS-Dilithium is already available, with constant-time property as a consideration for side-channel resilience. However, this implementation does not protect against attacks that exploit intermediate data leakage. We show how to exploit a new leakage on a vector generated during the signing process, for which the costly protection by masking is still a matter of debate. With a corpus of 700 000 messages, we design a template attack that enables us to efficiently predict whether a given coefficient in one coordinate of this vector is zero or not. By gathering signatures and being able to make the correct predictions for each index, and then using linear algebra methods, this paper demonstrates that one can recover part of the secret key that is sufficient to produce universal forgeries. While our paper deeply discusses the theoretical attack path, it also demonstrates the validity of the assumption regarding the required leakage model from practical experiments with the reference implementation on an ARM Cortex-M4. We need approximately a day to collect enough representatives and one more day to perform the traces acquisition on our target.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Dilithium
- Digital signature
- Lattice-based Cryptography
- Post Quantum Cryptography
- Side Channel Attacks
- Template Attacks
- Learning with Errors
# featured: false

links:
- name: "ePrint"
  url: "https://eprint.iacr.org/2023/050"
url_pdf: https://tches.iacr.org/index.php/TCHES/article/view/11163/10602
url_code: 'https://artifacts.iacr.org/tches/2023/a22/'
url_slides: 'uploads/CHES_Andersson_CALLEVIERA.pdf'
url_video: 'https://youtu.be/V53gvqiM0mU?feature=shared&t=1350'

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