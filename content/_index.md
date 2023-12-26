---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
       Research Lab
    #  image:
    #    filename: welcome.jpg
      text: |
        <br>
        The VisionX Lab (Vision and eXtended) Lab is affiliated with Wuhan University. Our research spans three key areas:
        1.	Vision Perception: Our research encompasses various computer vision fields, including object detection, image parsing, and human activity recognition, and other fundamental aspects of computer vision.
        2.	Vision-Language Integration: We are dedicated to facilitating seamless collaboration between vision and language, enhancing communication and reasoning across these modalities.
        3.	Generative Models: We aim to generate high-fidelity images, text, and other forms of content, fostering new possibilities in AI-driven content generation.
        Looking for highly-motivated Postdoc/Ph.D. students for 2023! Feel free to drop me an email with your CV. [招生信息] 

  
  - block: collection
    content:
      title: Publications
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
      page_type: publication
    design:
      view: citation
      columns: '1'
    
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
    #  - title: Lunch & Learn ☕️
    #    content: 'Share your knowledge with the group and explore exciting new topics together!'
    #    align: left
    #   background:
    #      image:
    #        filename: contact.jpg
    #        filters:
    #          brightness: 0.7
    #      position: center
    #      color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
    
  - block: collection
    content:
      title: Latest News
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
      view: card
      columns: '1'
---
