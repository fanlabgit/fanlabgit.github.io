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
      title: The Fan Lab
      text:  University of Maryland School of Medicine  
      announcement:
        text: "We are hiring PhD students and Postdocs!"
        link:
          text: "To apply "
          url: "#contact"
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: fanlab-header-1m.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: research
    content:
      items:
        - statistic: "Biomarker Discovery"
          description: |
            Websites built  
            with Hugo Blox
          # Upload image to `assets/media/` and reference the filename here
          image: biomarker.jpg
        - statistic: "Drug Resistance"
          description: |
            GitHub stars  
            since 2016
          # Upload image to `assets/media/` and reference the filename here
          image: figure-screen3.jpg
        - statistic: "Population Genetics"
          description: |
            Discord community  
            for support
          # Upload image to `assets/media/` and reference the filename here
          image: figure-rna.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: team
    content:
      title: Team
      text: We are hiring!
      
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
  - block: contact
    id: contact
    content:
      items:
    - title: Contact us
          # The '|' symbol allows for multi-line text blocks
          text: |
            **Wenjun Fan, PhD** University of Maryland School of Medicine  
            108 N. Greene St., Baltimore MD 21201  
            ✉️ Email: Wenjun.Fan@som.umaryland.edu
          # Upload image to `assets/media/` and reference the filename here
          image: um-school-medicine-logo.svg
          image: UMB-Skyline-Rendering_MM.jpg


    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

---