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
  - title: Common characters of ecDNA
    content: 
    1) Circular and double-stranded DNAs presented outside chromosomes
    2) Mostly 1-3 Mb in size
    3) Often contains major oncogenes and regulatory elements
    4) No centromeres and no telomeres 
    align: left
    background:
      position: right
      color: '#666'
      brightness: 0.7
      media: ectag.png
  - title: Lunch & Learn ☕️
    content: 'Share your knowledge with the group and explore exciting new topics together!'
    align: left
    background:
      position: center
      color: '#555'
      brightness: 0.7
      media: contact.jpg
  - title: World-Class Semiconductor Lab
    content: 'Just opened last month!'
    align: right
    background:
      position: center
      color: '#333'
      brightness: 0.5
      media: welcome.jpg
    link:
      icon: graduation-cap
      icon_pack: fas
      text: Join Us
      url: ../contact/
---
