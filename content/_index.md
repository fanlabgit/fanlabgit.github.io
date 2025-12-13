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
        The Fan Laboratory investigates the molecular mechanisms governing cancer progression and  uncover fundamental survival pathways in cancer. We employ an integrative strategy combining 
        functional genomics, bioinformatics, multi-omics, and chemical biology to dissect how cancer 
        cells adapt to targeted therapies and develop new therapeutic strategies.  

        Our work focuses on three distinct but interconnected areas of translational biology:
        
        - The Interface of rRNA Synthesis and Splicing  
        - Ribosomal Heterogeneity  
        - Translational Fitness and Resistance  
                
      
    design:
      columns: "1"
      background:
        color: "white"

  - block: markdown
    id: publications
    content:
      title: Publications
      subtitle: ""
      text: |
        1. **Fan W**, Liu H, Stachelek GC, Begum A, Davis CE, Dorado TE, Ernst G, Reinhold WC, Ozbek B, Zheng Q, De Marzo AM, Rajeshkumar NV, Barrow JC, Laiho M#. Ribosomal RNA transcription regulates splicing through ribosomal protein RPL22. *Cell Chemical Biology*. 2025-06. PMID: 40553690 (Cover article, independent preview by Dr. Omar Abdel-Wahab - PMID: 40680725)
        
        2. **Fan W**, Eklund E, Sherman RM, Liu H, Pitts S, Ford B, Rajeshkumar NV, Laiho M#. Widespread genetic heterogeneity of human ribosomal RNA genes. *RNA*. 2022 Apr;28(4):478–492. PMCID: PMC8925967 (Article)
        
        3. Xie J\*, Wang Z\*, **Fan W\***, Liu Y, Liu F, Wan X, Liu M, Wang X, Zeng D, Wang Y, He B, Yan M, Zhang Z, Zhang M, Hou Z, Wang C, Kang Z, Fang W, Zhang L, W.-F. Lam E, Guo X, Yan J, Zeng Y, Chen M, Liu Q#. Targeting cancer cell plasticity by HDAC inhibition to reverse EBV-induced dedifferentiation in nasopharyngeal carcinoma. *Signal Transduct Target Ther*. 2021 Sep 4;6(1):333. PMID: 34482361 (Article)
        
        4. Pitts S, Liu H, Ibrahim A, Garg A, Felgueira CM, Begum A, **Fan W**, Teh S, Low JY, Ford B, Schneider DA, Hay R, Laiho M#. Identification of an E3 ligase that targets the catalytic subunit of RNA Polymerase I upon transcription stress. *J Biol Chem*. 2022 Dec;298(12):102690. PMCID: PMC9727647 (Article)

        5. Peng F\*, Wang JH\*, **Fan WJ\***, Meng YT, Li MM, Li TT, Cui B, Wang HF, Zhao Y, An F, Guo T, Liu XF, Zhang L, Lv L, Lv DK, Xu LZ, Xie JJ, Lin WX, Lam EWF, Xu J, Liu Q#. Glycolysis gatekeeper PDK1 reprograms breast cancer stem cells under hypoxia. *Oncogene*. 2018 Feb 22;37(8):1119. PMCID: PMC5851083 (Article)
        
        6. Xia JL\*, **Fan WJ\***, Zheng FM, Zhang WW, Xie JJ, Yang MY, Kamran M, Wang P, Teng HM, Wang CL, Liu Q#. Inhibition of AURKA kinase activity suppresses collective invasion in a microfluidic cell culture platform. *Sci Rep*. 2017 Jun 7;7(1):2973. PMCID: PMC5462816 (Article)

        7. **Fan W**, Xie J, Xia J, Zhang Y, Yang M, Wang H, Pan Y, Zhang M, Han B, Wu B, Hou Z, Liang D, Wang C, Xu J, Song L, Liu Q#. RUVBL1-ITFG1 interaction is required for collective invasion in breast cancer. *Biochim Biophys Acta Gen Subj*. 2017 Jul;1861(7):1788–1800. PMID: 28341484 (Article)

        \* Co-first authors, # corresponding authors

        [Full list in Google Scholar](https://scholar.google.com/citations?user=GuJ4ltoAAAAJ&hl=en)
    design:
      css_class: "bg-white dark:bg-gray-800"

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
          text: "We are hiring PhD students and postdocs!" 
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
                  
            Department website: https://www.medschool.umaryland.edu/biochemistry/  
            ![UMB Logo](um-school-medicine-logo.svg)
          # Upload image to `assets/media/` and reference the filename here
          # image: um-school-medicine-logo.svg
          image: umb-skyline-rendering-mm.jpg

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

---