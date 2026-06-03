---
title: ''
summary: 'Microsoft 365 administration, endpoint management and practical IT infrastructure projects by Chris Waiting.'
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
        prefix: "I work across"
        strings:
          - "Microsoft 365 administration"
          - "Intune and endpoint management"
          - "SharePoint and collaboration"
          - "modern workplace support"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View Projects
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
      subtitle: "Selected delivery work and hands-on learning across Microsoft 365 and IT infrastructure"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: Completed
          tag: Completed
        - name: Ongoing
          tag: Ongoing
        - name: Planned
          tag: Planned
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
      subtitle: "Tools and platforms I use across administration, support and project delivery"
      categories:
        - name: Microsoft 365
          items:
            - name: Microsoft 365 Administration
              icon: hero/cloud
              level: expert
            - name: SharePoint Online
              icon: hero/document-text
              level: advanced
            - name: Microsoft Teams & Teams Phone
              icon: hero/user-group
              level: advanced
            - name: Exchange Online
              icon: hero/envelope
              level: intermediate
        - name: Endpoint Management
          items:
            - name: Microsoft Intune
              icon: hero/device-phone-mobile
              level: expert
            - name: Windows 11 & Device Lifecycle
              icon: hero/computer-desktop
              level: advanced
            - name: Windows Autopilot
              icon: hero/rocket-launch
              level: expert
            - name: BitLocker & Windows LAPS
              icon: hero/shield-check
              level: advanced
        - name: Identity & Security
          items:
            - name: Entra ID
              icon: hero/key
              level: expert
            - name: MFA & Conditional Access
              icon: hero/lock-closed
              level: intermediate
            - name: Endpoint Security
              icon: hero/shield-check
              level: intermediate
            - name: SPF, DKIM & DMARC
              icon: hero/envelope
              level: intermediate
        - name: Infrastructure & Operations
          items:
            - name: Networking & Connectivity
              icon: hero/wifi
              level: advanced
            - name: DNS & Domains
              icon: hero/globe-alt
              level: intermediate
            - name: PowerShell
              icon: hero/command-line
              level: beginner
            - name: Documentation & User Support
              icon: hero/book-open
              level: advanced
    design:
      style: grid
      show_levels: true
      background:
        color:
          light: "#f1f5f9"
          dark: "#07111f"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: resume-experience
    id: experience
    content:
      username: me
      title: "Experience"
    design:
      background:
        color:
          light: "#ffffff"
          dark: "#0b1525"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: resume-awards
    id: certifications
    content:
      username: me
      title: "Certifications"
    design:
      background:
        color:
          light: "#f1f5f9"
          dark: "#07111f"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: collection
    id: blog
    content:
      title: "Technical Notes"
      subtitle: "Project reflections, lab work and practical troubleshooting notes"
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
          light: "#ffffff"
          dark: "#0b1525"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: contact-info
    id: contact
    content:
      title: "Get In Touch"
      subtitle: "Connect with me"
      text: |-
        I am based in Melbourne and enjoy connecting with people working across Microsoft 365, endpoint management and modern IT support.
      email: hello@chriswait.ing
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#f1f5f9"
          dark: "#07111f"
      spacing:
        padding: ["4rem", "0", "5rem", "0"]
---
