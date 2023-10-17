---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Research Fellow
          company: University of Oslo
          company_url: ''
          company_logo: uio-crest
          location: Oslo, NO
          date_start: '2021-04-01'
          date_end: ''
          description: |2- 
              * Conducting research in computational syntax and semantics.
              * Teaching a range of courses at both undergraduate and graduate levels.
        - title: Departmental Lecturer in Syntax
          company: University of Oxford
          company_url: ''
          company_logo: oxford-logo
          location: Oxford, UK
          date_start: '2019-10-01'
          date_end: '2021-03-31'
          description: Teaching and supervision of work in syntax and other topics to students of all levels.
        - title: Stipendiary Lecturer in Linguistics
          company: Jesus College, University of Oxford
          company_url: ''
          company_logo: jesus-crest
          location: Oxford, UK
          date_start: '2019-10-01'
          date_end: '2020-09-30'
          description: |2-
              * Coordinating teaching & providing academic and pastoral support for undergraduate linguistics students at Jesus College.
              * Teaching in general linguistics and grammatical analysis.
        - title: Stipendiary Lecturer in Linguistics
          company: St Hugh's College, University of Oxford
          company_url: ''
          company_logo: st-hughs-crest
          location: Oxford, UK
          date_start: '2018-10-01'
          date_end: '2019-09-30'
          description: |2-
              * Coordinating teaching & providing academic and pastoral support for undergraduate linguistics students at St Hugh's College.
              * Tutorial teaching for other colleges in general linguistics, grammatical analysis, psycholinguistics, and sociolinguistics.
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
