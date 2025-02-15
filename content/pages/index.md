---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/KDE-Plasma-5.22-Wallpaper-Altai.webp
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'I make websites, desktop applications, and command-line programs'
    subtitle: >-
      Seasoned full-stack and application developer, specializing in .NET
      solutions and internal development tools. Experienced in creating and
      maintaining responsive and scalable applications whether they're internal
      company tools or client-facing products.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: LabelsSection
    title: My Specialties & Skillsets
    subtitle: ''
    items:
      - type: Label
        label: C#/.NET
        url: ''
      - type: Label
        label: Angular
        url: ''
      - type: Label
        label: React
        url: ''
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: Haskell
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: Git
        url: ''
      - type: Label
        label: Linux
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
---
