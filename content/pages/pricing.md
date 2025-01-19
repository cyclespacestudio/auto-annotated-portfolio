---
type: PageLayout
title: Pricing
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: This in an empty page
    subtitle: The section subtitle
    text: >-
      Start adding sections by clicking the + button on the page or through the
      sidebar.
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: RecentPostsSection
    subtitle: Posts
    actions:
      - type: Link
        label: See all posts
        altText: See all posts
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    colors: colors-f
    variant: variant-b
    elementId: ''
    recentCount: 3
    showDate: true
    showAuthor: false
    showExcerpt: true
    showFeaturedImage: false
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
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
        justifyContent: center
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
