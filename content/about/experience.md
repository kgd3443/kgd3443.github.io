---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Unity Game Prototype Developer
    company: Personal Project
    company_url: ''
    company_logo: unity
    location: Korea
    date_start: '2025-01-01'
    date_end: ''
    description: |2-
        Highlights:
        
        * Built a 2D prototype (Vampire Survivors–style)
        * Implemented object pooling, camera dynamics, and spawn timing
        * Wrote dev logs & retrospectives; iterated on gameplay feel


  - title: Todo List Web App (Assignment)
    company: University Jeonbuk
    company_url: ''
    company_logo: project
    location: Korea
    date_start: '2025-09-01'
    date_end: '2025-09-30'
    description:  |2-
        Features:
        
        * Add/delete items and toggle completion (strikethrough)
        * Simple state + render() loop with clean DOM updates
        * Documented requirements, screenshots, and usage in README

design:
  columns: '1'
---
