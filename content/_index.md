---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # text: |-
      text: 
        # I am a PhD student at Sorbonne University and Thales DIS.  
        # My research interests mainly involve Lattice-Based Crytographic Algorithms, specially:
        # - finding new Side Channel Attacks and Fault Attacks 
        # - optimizing implementations
        # - verifying efficient countermeasures
        "I am a PhD student at Sorbonne University and Thales DIS.  
        My research interests involve Lattice-Based Cryptography. Specially finding new Side Channel/Fault Attacks, optimizing implementations, and verifying efficient countermeasures."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CVEN_Andersson_CALLEVIERA.pdf
    design:
      # css_class: "dark"
      css_class: "bg-gray-100 dark:bg-gray-800"
      background:
        color: transparent
        image:
          # Add your image background to `assets/media/`.
          filename: layered-waves2.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       I am a PdD student in the ALMASTY team of Lip6 in Sorbonne University and at Thales DIS Meyreuil.

  #       My research focuses on Lattice-Based Crytographic Algorithms (Dilithium and Kyber), specially in :
  #       - finding new Side Channel Attacks and Fault Attacks 
  #       - optimized implementations
  #       - eficient coountermeasures
  #     columns: '1'
  #     padding: ['1px', '0', '1px', '0']
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
