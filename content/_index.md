---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-12-16
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "Hello! I am an active university student with a passion for education, technology, and environmental sustainability. I believe in the power of collaboration to create meaningful and impactful change."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Maulany Citra Pandini's CV.pdf
      button:
        text: Portfolio
        url: uploads/Maulany Citra Pandini's CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Work and Contributions'
      subtitle: ''
      text: |-
        I am actively involved in various activities focusing on education, plastic waste management, and technology development. Here are some of my key focuses:
        
        - Teaching elementary school students in subjects like IPAS, Mathematics, and Javanese Language.
        - Participating in the "Plastic-Free Generation" Project to raise environmental awareness.
        - Developing a Python learning module registered under copyright protection (HaKI).
        
        I am also working on creating inspiring social media content related to education and the laundry business I manage. Feel free to reach out for collaboration!😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Mapres Talks at PKKMB X MASTA ITESA 2024
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: "🌟 Looking to Collaborate?"
      text: |-
        If you're interested in topics such as education, plastic waste management, or technology development, don't hesitate to reach out. Together, we can make a bigger impact!
      button:
        text: Contact Me
        url: mailto:maulanycitra26@gmail.com
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
