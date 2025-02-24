---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: iOS Software Engineer
    company: TikTok
    company_url: ''
    company_logo: tiktok
    location: San Jose, USA
    date_start: '2023-09-18'
    date_end: 'now'
    description: |2-
        Responsibilities include:
        
      * Working as Tech owner and developer on "Flip Story" feature, which allow user to capture 2 photos in creation. User can hold button in consumption side to flip and show B side photo. Mainly using OpenCombine(MVVM) to finish camera capture logic, edit animation and all consumption interaction logic. This project increased story publish rate +3%, story interactions+1.8%. 
      
      * Working on "Story Thought" feature, which allow user to express feeling in a light mode. Mainly responsible for inbox skylight and profile UI display, data synchronization and story thought player. This project increased story publish rate +13.5%, story DM rate +4.7%.

      * Mainly working on different types of interactive stickers for creation side and consumption side. Mainly using Swift & Objective - C. This project increased story publish rate +1.47%.

      * Working on "Add comment to story" feature which allow user to fast repost a comment to a story video. This project increased story publish rate +3.59%.

      * Working on "Story Album refactor" feature. Mainly using TTKC (internal package), basic album api and OpenCombine(MVVM) to build component based, reusable album.

  - title: Software Engineer Intern
    company: Amazon
    company_url: ''
    company_logo: amazon
    location: Sunnyvale, USA
    date_start: '2022-05-23'
    date_end: '2022-08-12'
    description: |2-
        Responsibilities include:
        
      * Complete the classification of copyrights, based on Naive Bayes Model. Accuracy is about 94%.
      
      * ntegrate the classification module into the Amazon License Compliance(ALC) website. Supports functions such as online model update, copyrights modification, and demonstration of machine learning credibility.

  - title: AI Programmer Intern
    company: ByteDance
    company_url: ''
    company_logo: bytedance
    location: Hangzhou, China
    date_start: '2021-04-01'
    date_end: '2021-06-25'
    description: |2-
        Responsibilities include:
        
      * Complete the virtual idol's lip animation. According to the phoneme input mapping to Blend Shape animation parameters, adjust the animation state machine. It offers about a 30% performance improvement over traditional bone animation and a 50% reduction in memory overhead.
      
      * Complete the virtual idol chatbot. It includes UI control logic script, network request module, client animation and other module coding. This tool can be used for offline animation testing of virtual idols.
        
  - title: Client Programmer Intern

    company: ByteDance
    company_logo: bytedance
    location: Hangzhou, China
    date_start: '2020-07-07'
    date_end: '2021-04-01'
    description: |2-
        Responsibilities include:

       * Programmed the combat parts of the game with C# and Lua, including scene loading, special effects, sound effects, logical calculation and other client-side methods; completed the transformation of the combat scene from 2D to 3D
  
       * Complete client work such as sound management, joystick mobile characters, game packaging, UI prefab construction and logic code writing

       * Participate in the development of DCC art tools and realize the automatic execution of some art works. For example, automatically generate Materials based on texture files, automatically generate .prefab files based on .fbx files, one-click preview of animation .fbx files, model replacement, and so on. This greatly improves the efficiency of art resource iteration

       * Developed a daily report robot that can automatically crawl the daily report content every day, aggregate it into a cloud document, and share it in a group chat @ those colleagues who have not completed the daily report

design:
  columns: '2'
---
