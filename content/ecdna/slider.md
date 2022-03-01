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
  - title: Common features of ecDNA-1
    content: '[Circular and double-stranded DNA out of chromosomes](https://pubmed.ncbi.nlm.nih.gov/31748743/)'
    align: center
    background:
      position: right
      color: '#666'
      brightness: 0.7
      media: slider1.png
  - title: Common features of ecDNA-2
    content: '[Does not contain a centromere or a telomere](https://pubmed.ncbi.nlm.nih.gov/30872802/)e'
    align: left
    background:
      position: center
      color: '#555'
      brightness: 0.7
      media: slider2.png
  - title: Common features of ecDNA-3
    content: '[Highly amplified in many cancers](https://pubmed.ncbi.nlm.nih.gov/32807987/)'
    align: right
    background:
      position: center
      color: '#333'
      brightness: 0.5
      media: slider3.png
    link:
      icon: graduation-cap
      icon_pack: fas
      text: Related research paper
      url:https://pubmed.ncbi.nlm.nih.gov/32807987/
---
