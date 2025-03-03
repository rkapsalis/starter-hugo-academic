---
widget: slider
weight: 1 
active: true
headless: true
title: My page

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '440px'
  # Make the slides full screen within the browser window?
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Hello! I'm Romanos.
      content: I am an AI Engineer.
      align: left
      background:
        position: center
          # Specify an image from `assets/media/`
          # or delete the image section to remove it
        media: IMG_20240722_135438.jpg
        filters:
          brightness: 0.7
        color: '#666'
      link:
        icon: file
        icon_pack: fas
        text: Resume
        url: https://rkapsalis.github.io/resume/
    - title: Projects
      content: 'Explore my portfolio showcasing AI projects and inovative solutions I have developed.'
      align: left
      background:
       
          # Specify an image from `assets/media/`
          # or delete the image section to remove it
        media: IMG_20240226_181511.jpg
        filters:
          brightness: 0.7
        position: center
        color: '#555'
      link:
        icon: code
        icon_pack: fas
        text: Portfolio
        url: https://github.com/rkapsalis 
    # - title: World-Class Semiconductor Lab
    #   content: 'Just opened last month!'
    #   align: right
    #   background:
    #     image:
    #       # Specify an image from `assets/media/`
    #       # or delete the image section to remove it
    #       filename: /headers/IMG_20240226_181511.jpg
    #       filters:
    #         brightness: 0.5
    #     position: center
    #     color: '#333'
    #   link:
    #     icon: graduation-cap
    #     icon_pack: fas
    #     text: Join Us
    #     url: ../contact/

---
