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
              level: 90
            - name: SharePoint Online
              icon: hero/document-text
              level: 85
            - name: Microsoft Teams & Teams Phone
              icon: hero/user-group
              level: 85
            - name: Exchange Online
              icon: hero/envelope
              level: 75
        - name: Endpoint Management
          items:
            - name: Microsoft Intune
              icon: hero/device-phone-mobile
              level: 85
            - name: Windows 11 & Device Lifecycle
              icon: hero/computer-desktop
              level: 90
            - name: Windows Autopilot
              icon: hero/rocket-launch
              level: 70
            - name: BitLocker & Windows LAPS
              icon: hero/shield-check
              level: 75
        - name: Identity & Security
          items:
            - name: Entra ID
              icon: hero/key
              level: 80
            - name: MFA & Conditional Access
              icon: hero/lock-closed
              level: 75
            - name: Endpoint Security
              icon: hero/shield-check
              level: 75
            - name: SPF, DKIM & DMARC
              icon: hero/envelope
              level: 70
        - name: Infrastructure & Operations
          items:
            - name: Networking & Connectivity
              icon: hero/wifi
              level: 75
            - name: DNS & Domains
              icon: hero/globe-alt
              level: 75
            - name: PowerShell
              icon: hero/command-line
              level: 60
            - name: Documentation & User Support
              icon: hero/book-open
              level: 90
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
      title: "Experience"
      date_format: Jan 2006
      items:
        - title: IT Support Engineer / Microsoft 365 Administrator
          company: Managed Services Environment
          company_url: ''
          company_logo: ''
          location: Melbourne, Australia
          date_start: '2022-10-01'
          date_end: ''
          description: |2-
            * Primary onsite IT resource supporting a distributed nonprofit user environment across day-to-day support, administration and technology projects.
            * Administer Microsoft 365 services including Exchange Online, SharePoint Online, Teams, Teams Phone, Intune and Entra ID.
            * Support a hybrid environment spanning cloud services, endpoints, onsite infrastructure and network connectivity.
            * Contribute to endpoint management initiatives including Intune deployment, compliance policies, BitLocker, Windows LAPS and device lifecycle management.
            * Support meeting room technology, resource accounts, call queues and auto attendants.
            * Coordinate with vendors and remote technical teams, produce documentation and provide practical guidance to end users.
        - title: Desktop Support Analyst
          company: Enterprise Support Environment
          company_url: ''
          company_logo: ''
          location: Melbourne, Australia
          date_start: '2022-05-01'
          date_end: '2022-10-01'
          description: |2-
            * Provided Level 1 and Level 2 desktop support within a large enterprise environment.
            * Supported Windows endpoints and Microsoft applications using endpoint management and incident management tools.
        - title: Operations and IT Support
          company: Logistics Environment
          company_url: ''
          company_logo: ''
          location: Melbourne, Australia
          date_start: '2015-01-01'
          date_end: '2021-09-01'
          description: |2-
            * Combined operational responsibilities with practical technology support in a busy logistics setting.
        - title: Field Network Technician
          company: Telecommunications Environment
          company_url: ''
          company_logo: ''
          location: Melbourne, Australia
          date_start: '2014-01-01'
          date_end: '2015-01-01'
          description: |2-
            * Worked with field network services and customer connectivity in a telecommunications environment.
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
          light: "#f1f5f9"
          dark: "#07111f"
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
          light: "#ffffff"
          dark: "#0b1525"
      spacing:
        padding: ["4rem", "0", "5rem", "0"]
---
