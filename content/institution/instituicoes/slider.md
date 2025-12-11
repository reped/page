---
widget: slider
weight: 1
active: true
headless: true

design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: flat_brazil.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Instituição 1 ☕️ 
        content: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Massa tincidunt dui ut ornare lectus sit amet est. Ultrices sagittis orci a scelerisque purus semper eget duis at.'
        align: left
        background:
          image:
            filename: ind_embraer.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Instituição 2
        content: 'Nisi quis eleifend quam adipiscing vitae proin sagittis nisl. Commodo nulla facilisi nullam vehicula ipsum a arcu. Ultrices tincidunt arcu non sodales neque sodales ut etiam sit. Donec pretium vulputate sapien nec. '
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: 
          icon_pack: fas
          text: Início
          url: /#portfolio/
           
---
