---
title: ''
date: 2022-10-24
type: landing

# View.
view: citation

# # Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''

design:
  spacing: "6rem"
# design:
  # Default section spacing
  # spacing: '6rem'


sections:
  # - block: hero
  #   content:
  #     title: Build Your Landing Pages with Hugo Blox
  #     text: 🧱 EASY. FREE (OPEN SOURCE). NO-CODE  🧱
  #     primary_action:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #       icon: rocket-launch
  #     secondary_action:
  #       text: Read the docs
  #       url: https://docs.hugoblox.com
  #     announcement:
  #       text: "Announcing the release of version 1."
  #       link:
  #         text: "Read more"
  #         url: "/blog/"
  #   design:
  #   #   spacing:
  #   #     padding: [0, 0, 0, 0]
  #   #     margin: [0, 0, 0, 0]
  #     # For full-screen, add `min-h-screen` below
  #     css_class: "dark"
  #     background:
  #       color: "navy"
  #       image:
  #         # Add your image background to `assets/media/`.
  #         filename: bg-triangles.svg
  #         filters:
  #           brightness: 0.5
  #         size: cover
  #         position: center
  #         parallax: false
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  # - block: features
  #   id: features
  #   content:
  #     title: Features
  #     text: Build your site with blocks 🧱
  #     items:
  #       - name: Optimized SEO
  #         icon: /images/b.webp
  #         description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #       - name: Fast
  #         icon: bolt
  #         description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #       - name: Easy
  #         icon: sparkles
  #         description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #       - name: No-Code
  #         icon: code-bracket
  #         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #       - name: Highly Rated
  #         icon: star
  #         description: Rated 5-stars by the community.
  #       - name: Swappable Blocks
  #         icon: rectangle-group
  #         description: Build your pages with blocks - no coding required!


  - block: collection
    id: 2026 
    content:
      count: 0 
      title: 2026 Papers
      pagination: false
      text: ''
      filters:
        folders:
          - publications
        tags:
          - 2026
        # exclude_featured: true
    
    design:
      view: article-grid
      columns: 3
      css_class: "hbx-bg-gradient"

  - block: collection
    id: 2025 
    content:
      count: 0 
      title: 2025 Papers
      pagination: false
      text: ''
      filters:
        folders:
          - publications
        tags:
          - 2025
        # exclude_featured: true
    
    design:
      view: article-grid
      columns: 3
      css_class: "hbx-bg-gradient"
  - block: collection
    id: 2024 
    content:
      count: 0 
      title: 2024 Papers
      text: ''
      filters:
        folders:
          - publications
        tags:
          - 2024
        # exclude_featured: true
    design:
      view: article-grid
      columns: 3
      css_class: "hbx-bg-gradient"
      # css_class: "bg-gray-100 dark:bg-gray-900"
      # spacing:
      #   padding: ["1rem", 0, "1rem", 0]
  - block: collection
    id: preprints
    content:
      count: 0 
      title: Preprints
      pagination: false
      text: ''
      filters:
        folders:
          - publications
        tags:
          - preprints
    
    design:
      view: article-grid
      columns: 3
      css_class: "hbx-bg-gradient"
---