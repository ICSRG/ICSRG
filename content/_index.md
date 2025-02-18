---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      # - title: 👋 Welcome to ICSRG
      #   content: Take a look at what we're working on...
      #   align: center
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.7
      #     position: right
      #     color: '#666'

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

      # - title: World-Class Biomedical AI Lab
      #   content: ''
      #   align: right
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Join Us
      #     url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4500
  
  
  
  - block: hero
    content:
      title: |
         Dr. Saadia Binte Alam 
      image:
        filename: icon.png
      text: |
        <br>
        <p>
        Dr. Saadia is an academician specializing in leading research in medical image and signal processing, AI-driven disease detection, video data analysis, and robotics, her work bridges medicine, computer science, and engineering to advance healthcare, security, and human-robot interaction.
    link:
      icon: circile-info
      icon_pack: fas
      text: Join Us
      url: ../contact/

  # - block: hero
  #   content:
  #     title: |
  #        Intelligent Computing and Systems Research Group (ICSRG) 
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       The Intelligent Computing and Systems Research Group (ICSRG) has been a center of excellence for Artificial Intelligence research, teaching, and practice.

  - block: people
    content:
      title: Research Areas
      user_groups:
          - Research Areas

      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: false
      show_social: false


  - block: hero
    content:
      title: |
         IUB BongoMarine 
      image:
        filename: bongomarine.jpg
      text: |
        <br>
        <p>
        IUB BongoMarine, a team of Computer Science and Engineering students from IUB currently works on developing and upgrading their innovative autonomous underwater vehicle with significant potential for industrial applications as they compete globally to make a impactful mark. 
        They have already earned recognition on the global stage, securing a spot at the prestigious Singapore Autonomous Underwater Vehicle Challenge (SAUVC) 2025. Previously the team was in Top 15 at SAUVC 24, participating as the only team from Bangladesh.

        Dr. Saadia is an integral part of the team contributing as one of the Supervisors.
    link:
      icon: circile-info
      icon_pack: fas
      text: Join Us
      url: ../contact/

  - block: slider
    content:
      slides:
      - title: 
        content: ''
        align: left
        background:
          image:
            filename: bongomarinehero.png
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: 
        content: ''
        align: left
        background:
          image:
            filename: submarine.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: 
        content: ''
        align: left
        background:
          image:
            filename: teambongo1.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'

      - title: 
        content: ''
        align: left
        background:
          image:
            filename: teambongo.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'


      - title: 
        content: ''
        align: left
        background:
          image:
            filename: bongonews.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'


  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'


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
      view: compact
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'


---
