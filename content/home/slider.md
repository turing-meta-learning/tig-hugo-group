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
  loop: true  # false
  # Duration of transition between slides (in ms)
  interval: 9000

# https://emojipedia.org/food-drink/

content:
  slides:
    - title: 👋 Turing IG on Meta Learning
      content: Turing interest group on meta-learning for multimodal data
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.5
        media: pykale_logo.jpg
      link:
        icon: github
        icon_pack: fab
        text: Explore Now
        url: https://github.com/pykale/pykale
    - title: Under Construction 🚧
      content: 'This website is under construction. Please check back later.'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.4
        media: accessible_ml.jpg
      link:
        icon: chalkboard
        icon_pack: fas
        text: Try Colab Tutorial
        url: https://colab.research.google.com/github/pykale/pykale/blob/main/examples/digits_dann_lightn/tutorial.ipynb
---
