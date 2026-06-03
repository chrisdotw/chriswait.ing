---
title: ''
summary: 'Microsoft 365, endpoint management and practical IT projects by Chris Waiting.'
date: 2026-06-03
type: landing

sections:
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I work with"
        strings:
          - "Microsoft 365"
          - "Intune and endpoint management"
          - "SharePoint and collaboration"
          - "practical IT solutions"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View My Projects
          url: "#projects"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#f8fafc"
          dark: "#07111f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  - block: portfolio
    id: projects
    content:
      title: "Projects & Labs"
      subtitle: "Practical Microsoft 365, endpoint management and infrastructure work"
      count: 0
      filters:
        folders:
          - projects
        buttons:
          - name: All
            tag: '*'
          - name: Microsoft 365
            tag: Microsoft 365
          - name: Intune
            tag: Intune
          - name: SharePoint
            tag: SharePoint
          - name: Collaboration
            tag: Collaboration
          - name: Lab
            tag: Lab
        default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0b1525"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: tech-stack
    id: skills
    content:
      title: "Skills & Technologies"
      subtitle: "Tools I use across support, administration and endpoint management"
      categories:
        - name: Microsoft Cloud
          items:
            - name: Microsoft 365
              icon: hero/cloud
            - name: Entra ID
              icon: hero/key
            - name: Exchange Online
              icon: hero/envelope
            - name: SharePoint Online
              icon: hero/document-text
        - name: Endpoint Management
          items:
            - name: Microsoft Intune
              icon: hero/device-phone-mobile
            - name: Windows 11
              icon: hero/computer-desktop
            - name: Windows Autopilot
              icon: hero/rocket-launch
            - name: Endpoint Security
              icon: hero/shield-check
        - name: Collaboration & Support
          items:
            - name: Microsoft Teams
              icon: hero/user-group
            - name: Teams Rooms
              icon: hero/video-camera
            - name: DNS & Domains
              icon: hero/globe-alt
            - name: Networking
              icon: hero/wifi
        - name: Tools & Learning
          items:
            - name: PowerShell
              icon: hero/command-line
            - name: GitHub
              icon: brands/github
            - name: Microsoft Learn
              icon: hero/academic-cap
            - name: Documentation
              icon: hero/book-open
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f1f5f9"
          dark: "#07111f"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: resume-experience
    id: experience
    content:
      title: "Experience"
      date_format: Jan 2006
      items:
        - title: Onsite IT Support Technician
          company: Managed Service Provider
          company_url: ''
          company_logo: ''
          location: Melbourne, Australia
          date_start: '2022-10-01'
          date_end: ''
          description: |2-
            * Deliver onsite and remote IT support for a nonprofit client environment.
            * Administer Microsoft 365 services including SharePoint, Exchange, Teams and endpoint management.
            * Support users with varied technical confidence, from day-to-day troubleshooting through to device rollout and service coordination.
            * Contribute to practical IT improvements involving Intune, collaboration tools, hardware and connectivity.
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0b1525"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: collection
    id: blog
    content:
      title: "Technical Notes"
      subtitle: "Labs, project reflections and troubleshooting lessons"
      text: ''
      filters:
        folders:
          - blog
        exclude_featured: false
      count: 3
      order: desc
    design:
      view: card
      columns: 3
      background:
        color:
          light: "#f1f5f9"
          dark: "#07111f"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: contact-info
    id: contact
    content:
      title: "Get In Touch"
      subtitle: "IT support, Microsoft 365 and endpoint management"
      text: |-
        I am based in Melbourne and interested in connecting with people working across Microsoft 365, endpoint management and modern IT support.
      email: hello@chriswait.ing
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0b1525"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: cta-card
    content:
      title: "Projects built from practical IT experience"
      text: |-
        This site documents solutions, labs and lessons learned across **Microsoft 365**, **Intune**, **SharePoint**, endpoint management and user support.
      button:
        text: 'Browse Projects'
        url: '/projects/'
        new_tab: false
    design:
      card:
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#f1f5f9"
          dark: "#07111f"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
