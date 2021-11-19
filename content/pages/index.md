---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-i
    title: 'Love where you work, because work loves you'
    text: >
      One platform, one community, getting to the bottom line of everything
      employment.  Figure out your benefits, practice for interviews, get
      mentored, help peers, get helped in return.
    actions:
      - type: Button
        label: Sign Up
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
    feature:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-11
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-8
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-e
    title: Where did everyone go?
    text: >
      Learn how top tech companies have learned working remote using our
      product.
    actions:
      - type: Button
        label: Sign Up
        url: /
        style: secondary
      - type: Button
        label: Watch Video
        url: /
        style: link
        showIcon: true
        icon: arrowRight
    feature:
      type: ImageBlock
      url: /images/hero-3.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-20
          - ml-20
          - mr-20
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mb-6
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    title: 'A great feature, we’re proud of'
    text: >
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    feature:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-6
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-primary
        borderWidth: 5
        borderStyle: solid
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mb-6
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    title: And a strong value proposition
    text: >
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    feature:
      type: ImageBlock
      url: /images/hero-2.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-6
          - pb-36
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mb-6
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - colors: colors-a
    elementId: ''
    title: Featured items section
    subtitle: Featured items section example subtitle
    items:
      - type: ItemBlock
        title: 'The quick, brown fox jumps over a lazy dog'
        subtitle: Section subtitle
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
    columns: 3
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-4
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-f
    text: >+
      ## “We sometimes write things. You should read it, it might shed some
      light on why we’re doing what we’re doing”

      [See all posts](/blog)

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
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-0
    type: TextSection
  - elementId: ''
    variant: variant-b
    colors: colors-f
    actions:
      - type: Button
        label: View all
        url: /
        style: primary
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
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
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
      actions:
        justifyContent: center
    type: FeaturedPostsSection
  - colors: colors-a
    elementId: ''
    title: Gallery
    subtitle: Gallery subtitle
    images:
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-1.jpeg'
        altText: image alt text
        caption: image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-2.jpeg'
        altText: image alt text
        caption: image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-3.jpeg'
        altText: image alt text
        caption: image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-4.jpeg'
        altText: image alt text
        caption: image caption
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
      - url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
    spacing: 3
    columns: '7'
    aspectRatio: '1:1'
    imageSizePx: 300
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
    type: MediaGallerySection
  - type: ContactSection
    colors: colors-e
    title: Get early access
    text: >
      Sign up your team today to be the first to try out our new product to
      increae your team’s productivity
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: lorem-ipsum
          label: Email
          placeholder: Your email
          isRequired: false
          width: full
          type: EmailFormControl
      submitLabel: Sign Up
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
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-8
---
