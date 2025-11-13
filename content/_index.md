---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My core research focuses on the spatiotemporal variations of **tropospheric ozone**. Through quantitative analysis, I investigate long-term trends and interannual variability across continental and regional scales, which is critical for understanding ozone’s impact on **air quality and climate change**.
        I specialize in applying advanced quantitative methods and remote sensing techniques to generate high-quality atmospheric pollution datasets, including ozone, PM2.5, and fine/coarse mode Aerosol Optical Depth (fAOD/cAOD).
    
        Please reach out to collaborate 😃
    design:
      columns: 1
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
    
    columns: 2
  - block: collection
    id: talks
    content:
      title: Recent Presentations
      text: ''
      filters:
        folders:
          - conference-paper
        exclude_featured: false
    design:
      view: citation
  
---
