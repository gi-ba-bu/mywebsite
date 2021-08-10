---
# An instance of the Tag Cloud widget.
# Docs: https://wowchemy.com/docs/page-builder/
widget: tag_cloud

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 120

title: " Topics"
subtitle: in my posts and projects.

content:
# Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy: tags
  # Choose how many tags you would like to display (0 = all tags)
  count: 20
design:
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min: 1
  font_size_max: 1
  spacing:
# Customize the section spacing. Order is top, right, bottom, left.
    padding: ["0px", "40px", "20px", "40px"]
    
advanced:
  css_style: 'text-align: left;'
---
