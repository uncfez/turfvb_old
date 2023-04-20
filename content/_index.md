---
# Leave the homepage title empty to use the site title
title:
date: 
# Page type - we want a landing page (such as a homepage)
type: landing

sections:
  - block: hero 
    content: 
      title: Turf Västerbotten
      text: The **Turf Västerbotten** has been a center of excellence for Turfing research, teaching, and practice since its founding in 2017.
      image: 
        filename: welcome.jpg
 - block: collection
    id: post
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
---