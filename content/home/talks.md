---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# Activate this widget? true/false
active: false


# This file represents a page section.
headless: False


# Order that this section appears on the page.
weight: 30

title: 'Recent Presentation'
subtitle: ''

content:
  # Page type to display. E.g. post, event, publication...
  page_type: event
  filter_default: 0
  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Green Finance
    tag: Deep Learning
  - name: Other
    tag: Demo

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3
  
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
