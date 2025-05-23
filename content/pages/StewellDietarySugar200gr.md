---
type: PageLayout
title: StewellDietarySugar200gr
sections:
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Items on sale
      color: text-dark
      styles:
        self:
          textAlign: center
    items:
      - type: FeaturedItem
        title: Faux Fur Throw
        subtitle: $ 88 – $ 176
        text: >+
          Available in a range of colors and patterns, we make it easy to pick
          the perfect look for you.




          Our faux fur is incredibly soft, plush and oh-so inviting. It's like
          the real deal (but better)!



        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
              padding:
                - pt-0
                - pl-0
                - pb-0
                - pr-0
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pl-6
              - pb-6
              - pr-6
            textAlign: left
            borderColor: border-neutralAlt
            borderWidth: 2
            borderRadius: x-small
            flexDirection: row-reverse
            justifyContent: center
            borderStyle: dotted
      - type: FeaturedItem
        title: Cotton Knit Throws
        subtitle: $ 44.99 – $ 90
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            flexDirection: row
      - type: FeaturedItem
        title: Chunky Cotton Knit Throw
        subtitle: $117
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            flexDirection: row
    actions: []
    elementId: ''
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: CONTACT US FOR ORDERING
      color: text-dark
    subtitle: ''
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
slug: /StewellDietarySugar200gr
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---
