---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: MADLAB Documentation
      text: Tools for researchers in the Human-AI Teaming/Collaboration space 🤖
      primary_action:
        text: MADLAB Website
        url: "https://steyvers.socsci.uci.edu/madlab/"
        icon: rocket-launch
      secondary_action:
        text: Dr. Mark Steyvers (MADLAB P.I.)
        url: https://steyvers.socsci.uci.edu/
        # text: Read the docs
        # url: /docs/
      announcement:
        text: "Announcing the release of MPLib.js (a multiplayer gaming library for researchers)."
        link:
          text: "Read more"
          url: "/mplibjs/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "240+"
          description: |
            Publications
        - statistic: "1M+"
          description: |
            in Research Grants
        - statistic: "50+"
          description: |
            Collaborations
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  #- block: markdown
  #  content:
  #    #title: 'Test'
  #    #subtitle: 'Testing'
  #    text: <img src="https://faculty.sites.uci.edu/steyvers/files/2019/07/logo5.png" />
  #    #text: **Testing** # ![image](https://faculty.sites.uci.edu/steyvers/files/2019/07/logo5.png) # Add any **markdown** formatted #content here - text, images, videos, galleries - and even HTML code!
  #  design:
  #    # See Page Builder docs for all section customization options.
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    css_class: "bg-gray-100 dark:bg-gray-800"
  #- block: features
  #  id: features
  #  content:
  #    title: Features
  #    text: Collaborate, publish, and maintain technical knowledge with an all-in-one documentation site. Used by 100,000+ startups, #enterprises, and researchers.
  #    items:
  #      - name: Optimized SEO
  #        icon: magnifying-glass
  #        description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #      - name: Fast
  #        icon: bolt
  #        description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #      - name: Easy
  #        icon: sparkles
  #        description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #      - name: No-Code
  #        icon: code-bracket
  #        description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #      - name: Highly Rated
  #        icon: star
  #        description: Rated 5-stars by the community.
  #      - name: Swappable Blocks
  #        icon: rectangle-group
  #        description: Build your pages with blocks - no coding required!
  #- block: cta-card
  #  content:
  #    title: "Start Writing with the #1 Effortless Documentation Platform"
  #    text: Hugo Blox Docs Theme brings all your technical knowledge together in a single, centralized knowledge base. Easily search and #edit it with the tools you use every day!
  #    button:
  #      text: Get Started
  #      url: https://hugoblox.com/templates/details/docs/
  #  design:
  #    card:
  #      # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #      css_style: ""
---