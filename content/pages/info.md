---
type: PageLayout
title: About Me
colors: colors-c
backgroundImage:
  type: BackgroundImage
  url: /images/GradientSLheader for substack.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-c
    backgroundSize: inset
    text: >+
      <div style="text-align: left">I feel a palpable need to bring confounding
      scientific discoveries under all available light, to people who see them
      as arcane. I do not know when exactly this started but I recall reading
      Stephen Jay Gould's 'The Mismeasure of Man' back in 9th grade, a clarion
      call experience, and there was this show called "Human Universe" by Brian
      Cox which I used to watch every day as a kid, also going to a covert
      dome-telescope on top of a mountain for the first time with my brother's
      space research license and spotting my first neutron star - these are all
      core memories that could offer a clue. To an extent, I have been able to
      emulate this passion into things that have a tangible impact on the world
      ; because I feel an innate responsibility to future generations of
      thinkers and creators. My unrelenting sense of purpose is better elicited
      in my inclination for "Cathedral Thinking". I think in a burning world
      which surveys a very ambiguous future of either transcendence or
      destruction - the importance of science coverage is only going to increase
      by many orders of magnitude. *I intend on being at the very helm of it*. I
      love Bjork's music, Andrei Tarkovsky's Solaris is my favourite film, I
      like debates and not playing chess by the books.</div>

    media:
      type: ImageBlock
      url: /images/WhatsApp Image 2025-01-16 at 2.23.24 PM.jpeg
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
    title: Sulagna Chatterjee
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
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Professional Experience:'
        text: |+
          **2022 - Present**

          *   Full-Time Digital Marketing Executive at Meril Life Sciences

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |+
          **2019-2022**

          *   Media Student at Uni of Mumbai

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Sulagna's LinkedIn
            altText: ''
            url: 'https://www.linkedin.com/in/sulagna-chatterjee-8b3862205/'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
        styles:
          self:
            textAlign: left
        title: ''
      - type: FeaturedItem
        actions:
          - type: Link
            label: Sulagna's Instagram
            url: 'https://www.instagram.com/kynozomi/'
        styles:
          self:
            textAlign: left
        title: ''
    columns: 3
    spacingX: 120
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
  - type: LabelsSection
    colors: colors-f
    subtitle: I can operate on all of these platforms
    items:
      - type: Label
        label: Adobe Design Suite
      - type: Label
        label: TouchDesigner
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Adobe Substance 3D
      - type: Label
        label: Netlify
      - type: Label
        label: Garage Band
      - type: Label
        label: C++
      - type: Label
        label: Figma
    title: Tech Skills
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
      [Sulagnachatterjee52018@gmail.com](mailto:thisismyemail.@myemail.me)
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
  - type: ContactSection
    backgroundSize: full
    title: Reach out to me
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
