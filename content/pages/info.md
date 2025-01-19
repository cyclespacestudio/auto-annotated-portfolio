---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      ##### At Cyclespace Studio, we're more than just a design agency – we're
      your strategic partners in growth. We believe that great design is the
      engine that drives business forward. We work collaboratively with our
      clients, taking the time to understand their goals, challenges, and target
      audience. We then apply our expertise in branding, digital design, and
      marketing to create solutions that not only look great but also deliver
      measurable results. We're committed to helping our clients thrive in
      today's competitive market.

    media:
      type: ImageBlock
      url: /images/LEONE ROSE SHOT.png
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    title: About Us
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    title: SOFTWARE
    subtitle: We are Experts in These Tools
    images:
      - type: ImageBlock
        url: /images/BLENDER.png
        altText: logo one
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/UNREAL.png
        altText: logo two
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/Midjourney.png
        altText: logo three
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/AFTER EFFECTS 1.png
        altText: logo four
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/RUNWAY.png
        altText: logo five
        caption: ''
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 5
    aspectRatio: '16:9'
    showCaption: true
    enableHover: false
    elementId: Brands
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    title: Services
    subtitle: Your Digital Partner for Success
    items:
      - type: Label
        label: Motion Graphics & Animation
        url: ''
      - type: Label
        label: Design Consulting
        url: ''
      - type: Label
        label: Graphic Design
        url: ''
      - type: Label
        label: Logo Design & Branding
        url: ''
      - type: Label
        label: Web Design (UI/UX)
        url: ''
      - type: Label
        label: Illustration
        url: ''
      - type: Label
        label: UI/UX Design for Apps
        url: ''
      - type: Label
        label: Art Direction
        url: ''
      - type: Label
        label: Packaging Design
        url: ''
      - type: Label
        label: Interactive Design
        url: ''
      - type: Label
        label: Print Design & Pre-Press
        url: ''
      - type: Label
        label: Information Design
        url: ''
      - type: Label
        label: User Research & Testing
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
        textAlign: center
      subtitle:
        textAlign: center
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Tiktok
            url: >-
              https://www.tiktok.com/@cyclespace.studio?is_from_webapp=1&sender_device=pc
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Twitter
            url: 'https://x.com/cyclespacemedia'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/cyclespace-studio'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/cyclespace_studio/'
        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 51
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [info@cyclespacestudio.com](info@cyclespacestudio.com)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
