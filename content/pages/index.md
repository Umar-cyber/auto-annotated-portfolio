---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/Abeokuta_Forest_Nursery.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 59
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: DIRISU FAMILY DYNASTY
    subtitle: 'EDO STATE, NIGERIA'
    text: >+
      Edo State, located in the southern region of Nigeria, is one of the
      country's 36 states. Established on August 27, 1991, after being carved
      out from the former Bendel State, its capital city is Benin City, a
      historical and cultural hub renowned for its ancient artifacts and role in
      Nigerian history.

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
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
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
  - type: CtaSection
    title: FAMILY MEMBERS
    text: |+
      ######

      ###### Adeshola Dirisu

      ###### Imodu Dirisu

      ###### Abigail Dirisu

      ###### Bose Dirisu

      ###### Lucky Dirisu

      ###### Olu David Dirisu

      ###### Odio Peter Dirisu

      ###### Ogie David Dirisu

      ###### Friday Adebor Dirisu

      ###### Pst. Sunday Dirisu

      ###### Rukayya Peter Dirisu

      ###### Mariam Peter Dirisu

      ###### Francis Joseph Dirisu

      ###### Ayekpada Adebor Dirisu

      ###### Kafid A. DIRISU

      ###### Amid A. Dirisu

      ###### Sis. Josephine Samuel .D.

      ###### Benald Dirisu

      ###### Patience Dirisu

      ###### Paul Agustine Dirisu

      ###### Paul Samuel Dirisu

      ###### Mrs Josiah Dirisu

      ###### Aliyu Peter Dirisu

      ###### Yakubu Peter Dirisu (Don)

      ###### Philip Joseph

      ###### Mr josh link vec.Dirisu

      ###### Rashida Alex Dirisu

      ###### Yunusa .Dy. Cordinator

      ###### Dirisu Sunday

      ###### Ignatus Dirisu

      ###### Ogioshe Dirisu

      ###### Desmond Dolz dirisu

      ###### Kate Dirisu

      ###### Dada Dirisu 1,000 1,000

      ###### Jery.d. Jwoder nig ltd

      ###### Abdulmalik .d .sec

      ###### Famous Dirisu

      ###### Unice Dirisu

      ###### Sis Rose

      ###### Tunde Adebor Dirisu

      ###### Haruna Peter Dirisu

      ###### Philomina Salak Dirisu

      ###### Pst Abudu Emmanuel .D

      ###### Mummy Philo .D.(Minna)

      ###### Mummy Martins .D.okp

    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-1
          - pb-3
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedProjectsSection
    subtitle: 'Projects:'
    actions:
      - type: Link
        label: ''
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
    colors: colors-f
    variant: variant-b
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-0
          - pb-0
          - pl-2
          - pr-2
        justifyContent: center
        borderRadius: xx-small
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
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
          - pt-0
          - pb-0
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
    title: "CONTACT...\U0001F4AC"
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
          - pt-2
          - pb-4
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
