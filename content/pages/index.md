---
type: PageLayout
title: Home
colors: colors-c
backgroundImage:
  type: BackgroundImage
  url: /images/featured-Image4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      Warning: May cause extreme brand envy. We create ridiculously effective
      digital marketing and design solutions.
    subtitle: >-
      We blend creativity and strategy to develop digital solutions that are as
      unique as your brand, helping you connect with your audience, achieve your
      goals, and leave a lasting impression.
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
        textAlign: center
      subtitle:
        textAlign: center
        fontStyle: italic
        textDecoration: underline
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: MediaGallerySection
    title: BRANDS
    subtitle: Our partners
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: logo one
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo2.svg
        altText: logo two
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo3.svg
        altText: logo three
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo4.svg
        altText: logo four
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo5.svg
        altText: logo five
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo1.svg
        altText: altText of the image
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo2.svg
        altText: altText of the image
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo3.svg
        altText: altText of the image
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo4.svg
        altText: altText of the image
        caption: ''
        elementId: ''
      - type: ImageBlock
        url: /images/logo5.svg
        altText: altText of the image
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
    variant: variant-a
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
      - content/pages/projects/project-four.md
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
  - type: TestimonialsSection
    testimonials:
      - type: Testimonial
        quote: >
          "Our website is the core of our sales strategy. Doris helped us
          establish an easy-to-maintain Stackbit site with outstanding visuals!"
        name: John Doe
        title: CEO at Parks
        image:
          type: ImageBlock
          url: /images/bg3.jpg
          altText: John Doe
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
      - type: Testimonial
        quote: >
          “Anytime I have a question, I know I can get in touch with Doris. She
          always helps me adjust my site to look as perfect as I’d hoped.”
        name: Johnna Doe
        title: Product Marketing Manager at Acme
        image:
          type: ImageBlock
          url: /images/bg.jpg
          altText: Johnna Doe
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
    colors: colors-d
    variant: variant-c
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
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
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
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
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
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
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
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
