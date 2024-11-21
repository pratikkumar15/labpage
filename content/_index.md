---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <p style="font-size: 1.45rem; font-weight: bold;"> Chemigenetic tools for biological labeling </p>
      image: 
        filename: 'welcome.jpg'
        alt_text: "NIR dye in a flask"
      text: |
        <br>
        We  build chemigenetic tools to image and manipulate biology by combining dye chemistry or click chemistry with genetic labeling strategies. We collaborate widely to generate tools for solving different biological problems.
        <p></p><p></p>We are currently hiring at all levels. Work in our lab integrates chemistry (organic synthesis, optical chemistry), spectroscopy, biomolecular labeling, and imaging. We put a strong emphasis on honing career-development skills.

  - block: collection
    content:
      title: Group News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      background:
    # Choose colors such as from https://html-color-codes.info
    #    gradient_start: '#A9D0F5'
    #    gradient_end: '#58ACFA'
    # The gradient angle from 0-360 degrees
    #    gradient_angle: 180
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    #    text_color_light: true
      view: citation
      columns: '1'
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: '*A <a href="https://asapbio.org/preprint-info/preprint-faq" target="_blank">preprint</a> is a scientific manuscript that is uploaded by the authors but has not yet been formally peer reviewed*<br><br>'
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the Team →" %}}
    design:
      columns: '1'
---
