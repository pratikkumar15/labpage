---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:
#  - block: hero
#    content:
#      title:
#      text: <br><br><br><br><br>
#    design:
#       background:
#          video: 
#            filename: beaker.mp4
#            object-fit: none
          
  - block: hero
    content:
      title: |
        <p style="font-size: 2.0rem; font-weight: bold;"> Molecular tools for biology </p>
      image: 
        filename: 'welcome.jpg'
        alt_text: "NIR dye in a flask"
      text: |
        <p></p><p></p>
        We integrate dye chemistry, click chemistry, and biomolecular labeling strategies to build modern tools for imaging and manipulating biology.
        <p></p><p></p> Work in our lab encompasses organic chemistry, photochemistry, spectroscopy, enzymatic and chemical labeling, and imaging. We collaborate with a range of biologists to generate novel technologies for probing complex biological questions. 
        <p></p><p></p><b><i>We are currently seeking candidates at all levels to join our team.</i></b>
#    design:
#        background:
#          video: 
#            filename: beaker.mp4
#            filters:
#              brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: false
  
  

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
      text_color_light:
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
      title: Latest Publications
#      text: '*A <a href="https://asapbio.org/preprint-info/preprint-faq" target="_blank">preprint</a> is a scientific manuscript that has not yet been formally peer reviewed*<br><br>'
      count: 3
      filters:
        folders:
          - publication
        publication_type: ''
    design:
      view: citation
      columns: '1'

#  - block: collection
#    content:
#      title: Latest Peer-Reviewed Publications
#      text: ''
#      count: 2
#      filters:
#        folders:
#          - publication
#        publication_type: 'article-journal'
#    design:
#      view: citation
#      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the Team →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      filters:
        folders:
          - blank
    design:
      background:
        image: 
          filename: NCBS.png
          size: auto
          filters:
            brightness: 1
          parallax: false
          position: center
---