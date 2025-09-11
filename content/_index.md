---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: ""
        content: ""
        align: center
        background:
          image:
            filename: banner.jpg
            filters:
              brightness: 0.8
          position: right
          color: ""
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: 300px
      is_fullscreen: false 
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
    
  - block: hero
    content:
      title: About us
      image:
        filename: lab-logo.png
      text: | 
        <br>
        
        The Approximate Inference lab is a research group in the [Aalto University Department of Computer Science](https://www.aalto.fi/en/department-of-computer-science). Our work centers on developing robust and sample efficient methods for [simulation-based inference](https://simulation-based-inference.org/). Check [this page](blog/robust-and-efficient-sbi) to know more about our research.
  
  - block: people
    id: people
    content:
      title: People
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigator
        - Postdoctoral Researchers
        - PhD Students
        - Visiting Researchers
        - Alumni
      sort_by: Params.first_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  

  - block: collection
    id: publication
    content:
      title: Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: community/news
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      address:
        street: Konemiehentie 2
        city: Espoo
        region: 
        postcode: "02150"
        country: Finland
        country_code: FI
      directions: 
      office_hours:
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '60.18706512222067'
        longitude: '24.82131872457146'  
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'


  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: 
  #   design:
  #     columns: '1'
---
