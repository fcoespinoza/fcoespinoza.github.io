---
# Leave the homepage title empty to use the site title
title: "Francisco Espinoza"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography (optional)
      button:
        text: Download CV
        url: uploads/Francisco_Espinoza_CV.pdf
    # Uncomment if you want custom background
    # design:
    #   css_class: dark
    #   background:
    #     color: grey
    #     image:
    #       filename: stacked-peaks.svg
    #       filters:
    #         brightness: 1.0
    #       size: cover
    #       position: center
    #       parallax: false

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a UK-based Social Sciences researcher with experience in academia and government.  
        I specialise in Comparative Politics and Latin America, with broader expertise in post-transition regions and UK politics.  
        My work bridges research and teaching, with a focus on inclusive, student-centred learning.  
        I value collaboration, public engagement, and contribute to dynamic academic networks and environments.  
        I am open to collaboration.
    design:
      columns: '1'

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

  # Uncomment this section to show featured publications
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

  # Uncomment this section to show talks
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

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: post
      count: 5
