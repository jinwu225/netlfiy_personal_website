---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Put Your Section Options Here (title, background, etc.) ...
# Order that this section appears on the page.
title: Experience
subtitle:
weight: 40

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
# Use the same format as date_format listed in the config/_default/params.yaml
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#   To add an company logo, use company_logo: my-logo, where my my-logo 
#   references an SVG image in assets/media/icons/brands/ folder.
experience:
  - title: CEO
    company: GenCoin
    company_url: ''
    company_logo: org-gc
    location: California
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Analysing
        * Modelling
        * Deploying

  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
