---
type: PageLayout
title: Home
colors: colors-c
backgroundImage:
  type: BackgroundImage
  url: /images/bg.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
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
        width: narrow
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
        flexDirection: col-reverse
        borderRadius: none
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Button
        label: Book A Call
        altText: ''
        url: '/https://cal.com/cyclespace-studio'
        showIcon: true
        icon: arrowUpRight
        iconPosition: left
        style: secondary
        elementId: ''
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
    subtitle: The Future is Digital.
    title: Projects
  - type: LabelsSection
    title: Services
    subtitle: Your Digital Partner for Success
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
        url: ''
      - type: Label
        label: React
        url: ''
      - type: Label
        label: Microsoft Office
        url: ''
      - type: Label
        label: Next.js
        url: ''
      - type: Label
        label: Netlify
        url: ''
      - type: Label
        label: Pancakes
        url: ''
      - type: Label
        label: C++
        url: ''
      - type: Label
        label: Swift
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
  - type: TestimonialsSection
    testimonials:
      - type: Testimonial
        quote: >+
          ### **Unleash the Power of AI:**


          ##### Leverage the speed and efficiency of AI to streamline the entire
          video production process, from concept to completion.


          ### **3D Animation That Wows:**


          ##### Captivate your audience with breathtaking 3D animations that
          bring your brand to life. We craft immersive worlds and engaging
          characters that leave a lasting impression.


          ### **Hollywood-Level Creativity:**


          ##### Achieve the visual impact of high-budget Hollywood productions
          with our expert 3D animation techniques and innovative storytelling.

        name: Zwivhuya Mbulaheni
        title: CEO at Cyclespace Studio
        image:
          type: ImageBlock
          url: /images/about.jpg
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
        quote: >+
          ### **Dramatically Reduced Costs:**


          ##### AI technology significantly lowers production expenses, making
          world-class video advertising accessible to businesses of all sizes.




          ### **Data-Driven Success:**


          ##### Track key performance indicators (KPIs) to measure the
          effectiveness of your campaigns and optimize for maximum return on
          investment (ROI).




          ### **Your Vision, Reimagined:**


          ##### Share your ideas with us, and our team will bring them to life
          with a unique blend of AI-powered creativity and stunning 3D
          animation.



        name: Zwivhuya Mbulaheni
        title: Founder at Cyclespace studio
        image:
          type: ImageBlock
          url: /images/about.jpg
          altText: Johnna Doe
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
    colors: colors-f
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
    title: Hollywood-Quality Ads. AI-Powered Prices
    subtitle: >-
      Experience the future of advertising. We seamlessly blend cutting-edge AI
      with stunning 3D animation to deliver captivating video campaigns that
      drive results.
  - type: CtaSection
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        label: Learn more
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-b
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
    title: "Got an interesting project? Tell us more...\U0001F4AC"
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
