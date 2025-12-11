---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: 'Destaques'
#subtitle: 'Destaques'

content:
  # Page type to display. E.g. project.
  page_type: project
  # Choose how many pages you would like to display (0 = all pages)
  count: 4
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: Todos
      tag: '*'
    - name: Eventos
      tag: eventos
    - name: Na mídia
      tag: mídia
    - name: Outros
      tag: outros

design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background:
#    image: noticias.png
#    image_darken: 
#    image_parallax: true
#    image_position: center
#    image_size: 
#    text_color_light: 
  spacing: {padding: [0, 0, 0, 0]}
---
