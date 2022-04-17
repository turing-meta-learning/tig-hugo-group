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
  interval: 5000

# https://emojipedia.org/food-drink/

content:
  slides:
    - title: 👋 Green machine learning
      content: Reduce repetitions, reuse resources, and recycle models to build PyKale
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.5
        media: greenML.png
      link:
        icon: github
        icon_pack: fab
        text: Explore Now
        url: https://github.com/pykale/pykale
    - title: Accessible software 🗝️
      content: 'Make abundant machine learning software accessible for interdisciplinary research'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.4
        media: accessibleML.png
      link:
        icon: chalkboard
        icon_pack: fas
        text: Try Colab Tutorial
        url: https://colab.research.google.com/github/pykale/pykale/blob/main/examples/digits_dann_lightn/tutorial.ipynb
    - title: Pipeline-based API ⛓️
      content: 'Standardize all machine learning workflows into six steps'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.3
        media: pipelineAPI.png
      link:
        icon: book
        icon_pack: fas
        text: View API Docs
        url: https://pykale.readthedocs.io/en/latest/index.html
---
