---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        # filename: cv/anuoluwatuyi.pdf
        url: cv/anuoluwatuyi.pdf
    design:
      css_class: dark
      background:
        color: dark
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
      title: 'Current Research 🔬'
      subtitle: ''
      text: |-
        My research focuses on __automating the classification of parcel descriptions in Nigerian Pidgin into their HS Codes__. This project aims to improve the accuracy of categorizing parcels from the Nigerian market, through addressing the unique linguistic challenges of Nigerian Pidgin.

        I am also deeply passionate about advancing research on underrepresented languages, particularly Nigerian Pidgin. I explore advanced machine learning techniques to enhance the processing and understanding of these languages, contributing to their preservation and better integration into modern technology.

        I am always eager to collaborate on projects related to machine learning, natural language processing, and supporting underrepresented languages. Please feel free to reach out for discussions or potential partnerships!
    design:
      view: article-grid
      columns: '1'
      style: 'padding: 20px;'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: projects
  #   content:
  #     title: Featured Projects
  #     filters:
  #       folders:
  #         - project
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 3
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 3
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
