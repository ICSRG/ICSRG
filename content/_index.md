---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to ICSRG
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Kidney Tumor Diagnosis
        content: ''
        align: left
        background:
          image:
            filename: kts.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: Lung Disease Detection from Chest X-ray (CXR)
        content: ''
        align: left
        background:
          image:
            filename: cxr.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: Autonomous Quadruped Robot
        content: ''
        align: left
        background:
          image:
            filename: robodog.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: Diabetic Foot Ulcer Diagnosis
        content: ''
        align: left
        background:
          image:
            filename: diabetic.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: Automated Violence Detection and Classification
        content: ''
        align: left
        background:
          image:
            filename: violence.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: World-Class Biomedical AI Lab
        content: ''
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 1000


  - block: hero
    content:
      title: |
         Intelligent Computing and Systems Research Group (ICSRG) 
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The Intelligent Computing and Systems Research Group (ICSRG) has been a center of excellence for Artificial Intelligence research, teaching, and practice.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
