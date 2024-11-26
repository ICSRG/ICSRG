---
title: Research

type: landing

sections:
  - block: people
    content:
      title: Research Areas
      user_groups:
          - Research Areas

      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: false


  - block: collection
    content:
      title: Research Projects
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: card
      columns: '1'

---