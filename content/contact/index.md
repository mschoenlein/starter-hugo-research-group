---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Connect with me
      text: |-
       Send me a message!
      email:  schoenlein@wisc.edu
     # phone: 
      address:
        street: 1202 W. Johnson St. 
        city: Madison
        region: WI
        postcode: '53711'
        country: United States
        country_code: US
     # coordinates:
      #  latitude: '37.4275'
     #   longitude: '-122.1697'
     # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 12:00'
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
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
          filename: paintBackground-03.png
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
