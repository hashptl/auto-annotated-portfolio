---
type: PageLayout
title: Home
colors: colors-c
backgroundImage:
  type: BackgroundImage
  url: /images/1 Homepage skl.gif
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      Hello! I am Sulagna. an alias coined by one of my professors -"Skai" is
      what all my friends call me. 
    subtitle: ''
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
        borderColor: border-complementary
      title:
        textAlign: center
        fontWeight: 400
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >+
      <div style="text-align: center">##### I am an interdisciplinary writer
      \[focusing mostly on science journalism], multimedia designer and digital
      content specialist. I have studied media communications and philosophy of
      science & tech. Currently working as a digital content executive for a
      global MedTech company where I translate complex scientific literature
      into accessible narratives, I am also studying policymaking. I am most
      interested in finding ways to enable "rhizomatic" thinking through
      materials such as interactive softwares, films, digital artefacts and
      literary pieces. Additionally, I am deeply invested in understanding the
      impact of technological progress, and planetary-scale data on human
      civilization through a strategic and cathedral-thinking approach. Also
      skilled in fashion technology, critique and building compelling brand
      languages - I intend on pulling strands from these disparate domains of
      learning and build something unique for posterity.</div>

  - type: TextSection
    colors: colors-a
    variant: variant-b
    title: In this portfolio
    subtitle: you will find
    text: >
      My writing samples, a few designs, prototypes, my final year college
      project from 2022, a section about me, an unusual amount of truisms and
      occasionally a few things that have inspired me.
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
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
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
      - content/pages/projects/essay_4.md
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
    subtitle: ESSAYS ;
    title: Words Permeate Us All
  - type: CtaSection
    title: FINAL- YEAR PROJECT
    text: >+
      Stainslaw Lem, the revered polish science fiction author wrote Summa
      Technologiae in 1964. The manuscript has tremendous foresight given that
      most of the things prognosticated in the essays have become real objects
      and phenomena in the current era. Does fiction precede reality? does
      science manifest in what starts out as impossible? Futurismo explores the
      human ingenuity behind creating the technologies of hereafter. There is an
      ongoing belief that nothing is impossible when viewed from the colossal
      time-scale of the universe itself. We may not have the computation
      infrastructure needed to solve the most complex mathematical paradoxes
      deemed "un-solvable" right now\.. but there is no saying we can't do it
      when we have evolved into the technological singularity. Conceived in 2021
      and carrying stories ranging from the book that led to the invention of
      the first pacemaker, interviews from visionaries like Cho Gi Seok
      (Photographer), Robbie Barat (Bioinformatics researcher and artist at
      Stanford) and Yoon Ahn (Metaverse' first fashion designer and founder of
      "AMBUSH) Futurismo was made in praise of prescience.

    actions:
      - type: Button
        label: Take me to Futurismo
        altText: ''
        url: >-
          https://drive.google.com/file/d/19gdvkICb9mKTgcyl7W-sretn6G0HgIHJ/view?usp=sharing
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-c
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
        flexDirection: col
      title:
        textAlign: center
      text:
        textAlign: center
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
