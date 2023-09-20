---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
        # {{% callout note %}}
        # Quickly discover relevant content by [filtering publications](./publication/).
        # {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: wsh23@mails.tsinghua.edu.cn
      phone: (+86) 156 5258 7705
      address:
        street: Medical Science Building
        city: Tsinghua University
        region: Beijing 100084,
        postcode: China
        country: China
        country_code: US  
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
