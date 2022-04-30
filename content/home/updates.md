---
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

# ... Put Your Section Options Here (title etc.) ...
title: Latest Updates
subtitle: <a href="/post">CaRAML Blog <i class="fas fa-angle-right"></i></a>

content:
  # Filter content to display
  filters:
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
  count: 3
  # Choose how many pages you would like to offset by
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false

design:
  # Choose a listing view
  view: compact
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
---
