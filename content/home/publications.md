---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# Activate this widget? true/false
# 2021-12-25: I set this widget to false. I set it to false instead of deleting in case I need the code for reference later.
# I don't plan on putting all of my publications on my website. Instead, I will link to LinkedIn and my CV. But, myabe I'll change my mind at some point.
active: false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

title: Recent Publications
subtitle: ''

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how much pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  # Filter on criteria
  filters:
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: true
design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 4
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}
