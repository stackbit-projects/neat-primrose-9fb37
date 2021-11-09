---
title: Home
layout: PageLayout
sections:
  - colors: colors-d
    backgroundWidth: full
    elementId: ''
    title: Some photos
    subtitle: Aren't they lovely photos?
    images:
      - url: images/hilary-ouse.jpg
        caption: Hilary Ouse
        altText: Photo of Hilary Ouse
      - url: /images/isabelle-parks.jpg
        altText: Photo of Isabelle Parks
        caption: Isabelle Parks
      - url: /images/desmond-eagle.jpg
        altText: Photo of Diamond Eagle
        caption: Diamond Eagle
      - url: /images/hugh-saturation.jpg
        altText: Photo of Flower Man
        caption: Flower Man
    spacing: 1
    columns: '4'
    imageSizePx: 267
    showCaption: false
    enableHover: true
    styles:
      self:
        width: full
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        height: auto
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
    type: MediaGallerySection
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-f
    backgroundWidth: full
    title: This Is A Big Hero Headline
    text: >-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: 'https://www.stackbit.com/'
        style: secondary
    feature:
      type: ImageBlock
      url: /images/hero.png
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 3
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-4
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
    backgroundWidth: full
    title: Some Fine Folks Who Work With Us
    subtitle: Join the team?
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-4
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      text:
        textAlign: center
    type: TextSection
  - type: MediaGallerySection
    showCaption: true
    spacing: 1
    imageSizePx: 150
    colors: colors-e
    backgroundWidth: full
    elementId: ''
    images:
      - url: images/hilary-ouse.jpg
        altText: Hilary Ouse
        caption: Hilary Caption
      - altText: lorem-ipsum
        caption: People at desk
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
        url: /images/about.jpg
      - altText: lorem-ipsum
        caption: Dude with flower
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
        url: /images/hugh-saturation.jpg
      - url: /images/dianne-ameter.jpg
        altText: Diane Ameter
        caption: Diane Caption
        elementId: ''
        type: ImageBlock
      - altText: Diamond Eagle
        caption: Diamond Eagle
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
        url: /images/desmond-eagle.jpg
      - altText: lorem-ipsum
        caption: lorem-ipsum
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
        url: /images/hugh-saturation.jpg
      - altText: lorem-ipsum
        caption: lorem-ipsum
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
        url: /images/isabelle-parks.jpg
      - altText: lorem-ipsum
        caption: lorem-ipsum
        elementId: ''
        styles:
          self:
            opacity: 100
        type: ImageBlock
        url: /images/hilary-ouse.jpg
    styles:
      self:
        height: screen
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-4
          - pb-4
        alignItems: flex-end
        justifyContent: center
        borderRadius: small
        borderColor: border-complementary
        borderStyle: solid
        borderWidth: 2
    enableHover: true
  - colors: colors-e
    backgroundWidth: full
    elementId: ''
    images:
      - url: images/hilary-ouse.jpg
        caption: Hilary Ouse
        altText: Photo of Hilary Ouse
      - url: /images/isabelle-parks.jpg
        altText: Photo of Isabelle Parks
        caption: Isabelle Parks
      - url: /images/desmond-eagle.jpg
        altText: Photo of Diamond Eagle
        caption: Diamond Eagle
      - url: /images/hugh-saturation.jpg
        altText: Photo of Flower Man
        caption: Flower Man
    spacing: 1
    imageSizePx: 150
    showCaption: false
    enableHover: true
    styles:
      self:
        width: full
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-0
          - pb-12
        height: auto
    type: MediaGallerySection
  - type: FeaturedPostsSection
    variant: variant-c
    colors: colors-c
    backgroundWidth: full
    title: Blog Posts
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
  - colors: colors-a
    backgroundWidth: full
    elementId: ''
    title: Some photos
    subtitle: Aren't they lovely photos?
    images:
      - url: images/hilary-ouse.jpg
        caption: Hilary Ouse
        altText: Photo of Hilary Ouse
      - url: /images/isabelle-parks.jpg
        altText: Photo of Isabelle Parks
        caption: Isabelle Parks
      - url: /images/desmond-eagle.jpg
        altText: Photo of Diamond Eagle
        caption: Diamond Eagle
      - url: /images/hugh-saturation.jpg
        altText: Photo of Flower Man
        caption: Flower Man
    spacing: 1
    columns: 4
    imageSizePx: 120
    showCaption: false
    enableHover: true
    styles:
      self:
        width: full
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        height: auto
        borderRadius: large
        borderColor: border-primary
        borderWidth: 4
        borderStyle: dashed
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
    type: MediaGallerySection
  - elementId: ''
    variant: variant-a
    colors: colors-a
    backgroundWidth: full
    title: About us
    subtitle: Meet the team
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - type: TestimonialsSection
    colors: colors-h
    backgroundWidth: full
    testimonials:
      - quote: >-
          “It’s great to see someone taking action while still maintaining a
          sustainable fish supply to home cooks.”
        name: Isabelle Parks
        title: Head chef at Parks
        image:
          type: ImageBlock
          url: /images/isabelle-parks.jpg
          altText: Isabelle Parks
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row
          quote:
            textAlign: left
          name:
            fontWeight: '700'
            fontStyle: normal
            textAlign: left
          title:
            fontWeight: '400'
            fontStyle: normal
            textAlign: left
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
  - type: CtaSection
    colors: colors-c
    backgroundWidth: full
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
    actionsPosition: right
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: TextSection
    colors: colors-f
    backgroundWidth: full
    title: The Section Title
    subtitle: The section subtitle
    text: >-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
      text:
        textAlign: center
  - type: ContactSection
    colors: colors-h
    backgroundWidth: full
    title: Join our club
    text: >-
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not.
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Fisherman holding lobster
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
---
