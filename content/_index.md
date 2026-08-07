---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About me
        education: Education
        interests: Research Interests
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      spacing:
        padding: ["0px", "0", "0px", "0"]
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: markdown
    content:
      title: '📚 Research Overview'
      subtitle: ''
      text: |-
        My research focuses on developing **flexible, stretchable, and wearable electronic systems** enabled by advanced micro- and nanofabrication technologies. The objective is to bridge semiconductor manufacturing with emerging applications in wearable healthcare, energy harvesting, and intelligent electronic systems.

        My primary research areas include:

        - **Flexible and Stretchable Electronics:** Development of mechanically compliant electronic architectures using serpentine, origami, and kirigami-inspired designs to improve reliability under bending and stretching.

        - **Thermoelectric Energy Harvesting:** Design and fabrication of flexible thermoelectric generators for self-powered wearable sensing systems and low-power IoT applications.

        - **Micro- and Nanofabrication:** CMOS-compatible fabrication processes, MEMS technologies, thin-film devices, flexible hybrid electronics, and advanced semiconductor manufacturing.

        - **AI for Electronic Design:** Artificial intelligence and optimization algorithms for PCB autorouting, electronic design automation, and intelligent circuit design.

        I welcome collaborations with researchers, industry partners, and students interested in flexible electronics, wearable sensing, semiconductor manufacturing, and intelligent electronic systems.
    design:
      columns: '2'
  
  - block: collection
    id: papers
    content:
      title: Featured Publications
      text: Representative publications spanning flexible electronics, wearable sensing, thermoelectric energy harvesting, and advanced semiconductor manufacturing.
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
 
---
