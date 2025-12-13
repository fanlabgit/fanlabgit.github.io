---
title: 'Home'
date: 2025-12-12
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
  - block: markdown
    id: research
    content:
      title: "The Fan Laboratory"
      text: |              
        The Fan Laboratory investigates the molecular mechanisms governing cancer progression and 
        uncover fundamental survival pathways in cancer. We employ an integrative strategy combining 
        functional genomics, bioinformatics, multi-omics, and chemical biology to dissect how cancer 
        cells adapt to targeted therapies and develop new therapeutic strategies.

        Our work focuses on three distinct but interconnected areas of translational biology:
        
        - The Interface of rRNA Synthesis and Splicing
        - Ribosomal Heterogeneity
        - Translational Fitness and Resistance
                
        [Google scholar](https://scholar.google.com/citations?user=GuJ4ltoAAAAJ&hl=en)
    design:
      columns: "1"
      background:
        color: "white"

  - block: testimonials
    id: team
    content:
      title: "Team"
      text: ""
      items:
        - name: "Wenjun Fan"
          role: "Principal Investigator"
          # Upload image to `assets/media/` and reference the filename here
          image: "pi.jpg"
          text: "We are hiring!" 
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
  - block: cta-image-paragraph
    id: contact
    content:
      items:
        - title: Contact us
          # The '|' symbol allows for multi-line text blocks
          text: |
            **Wenjun Fan, PhD**
            Department of Biochemistry and Molecular Biology
            University of Maryland School of Medicine
            108 N. Greene St., Baltimore MD 21201  
            ✉️ Email: Wenjun.Fan@som.umaryland.edu
            [Department of Biochemistry](https://www.medschool.umaryland.edu/biochemistry/)
            ![UMB Logo](um-school-medicine-logo.svg)
          # Upload image to `assets/media/` and reference the filename here
          # image: um-school-medicine-logo.svg
          image: umb-skyline-rendering-mm.jpg

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

---