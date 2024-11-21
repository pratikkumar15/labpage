---
title: Contact
date: 2024-11-03

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |
        **You can use this page to email us or inquire about the open positions**
      email: name[@]ncbs.res.in
      phone: 91
      address:
        street: National Centre for Biological Sciences
        city: Bengaluru
        region: Karnataka
        postcode: '560065'
        country: India
        country_code: IN
      coordinates:
        latitude: '13.071406531558969'
        longitude: '77.58027996863052'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
#      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
