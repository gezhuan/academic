---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: portfolio
  content:
    
    buttons:
    # - name: All
    #   tag: '*'
    - name: Research Statement
      tag: Research Statement
    # - name: Length-scale based Rheology
    #   tag: Length-scale based Rheology
    default_button_index: 0
    filters:
      folders:
      - project
    title: Research
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
# - block: portfolio
#   content:
#     buttons:
#     - name: All
#       tag: '*'
#     - name: Deep Learning
#       tag: Deep Learning
#     - name: Other
#       tag: Demo
#     default_button_index: 0
#     filters:
#       folders:
#       - project
#     title: Projects
#   design:
#     columns: "1"
#     flip_alt_rows: false
#     view: showcase
#   id: projects
# - block: features
#   content:
#     items:
#     - description: 90%
#       icon: r-project
#       icon_pack: fab
#       name: R
#     - description: 100%
#       icon: chart-line
#       icon_pack: fas
#       name: Statistics
#     - description: 10%
#       icon: camera-retro
#       icon_pack: fas
#       
#       name: Photography
#     title: Skills

# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: Hangzhou
      country: China
      postcode: "310030"
      street: No.600 Dunyu Road, Sandun Town
   

    email: gezhuan@westlake.edu.cn
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify

    phone: +86 15524005459
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
