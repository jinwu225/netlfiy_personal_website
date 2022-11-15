---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: collection

# This file represents a page section.
headless: true

# Put Your Section Options Here (title, background, etc.) ...
# Order that this section appears on the page.
title: Recent Posts
subtitle:
weight: 60

content:
  # Filter content to display based on criteria
  filters:
    # The folders to display content
    folders:
      - post
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  # Useful if you wish to show the first item in the Featured widget
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

  # See All link appears when you have more content than specified count number 
  archive:
    # Show/hide the ;ink
    enable: true  
    text: See all blog posts
    link: post/

design:
  # Choose a view for the listings:
  view: compact
  columns: '2'
---

Check out my recent blog posts below!