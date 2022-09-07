---
background-color: white
logo-left: https://raw.githubusercontent.com/multi-coop/vizboard-website-content/main/images/logo_GITRIBUTE.png
fixed-top: true

buttons-left-centered: true

buttons-left:

  - name: Datami 
    # icon: cog
    # link: /
    # hash: features
    # component: simpleLink
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Accueil
      en: Home
    submenu:
      - name: homepage
        link: /
        component: simpleLink
        label: 
          fr: Accueil
          en: Homepage
      - name: clients
        link: /
        scrollTo: landing-clients
        # hash: section-landing-clients
        component: simpleLink
        label: 
          fr: Ils soutiennent Datami
          en: They support Datami
      - name: discover
        link: /
        scrollTo: landing-demo-intro
        # hash: section-landing-demo-gitribute-cooptech
        component: simpleLink
        label: 
          fr: Découvrir Datami
          en: Discover Datami
      - name: simplify
        link: /
        scrollTo: landing-simplify
        # hash: section-landing-simplify
        component: simpleLink
        label: 
          fr: Simplifier la dataviz
          en: Simplify dataviz
      - name: features
        link: /
        scrollTo: landing-features
        # hash: section-landing-features
        component: simpleLink
        label: 
          fr: Fonctionnalités
          en: Features
      - name: CTA
        link: /
        scrollTo: landing-cta
        component: simpleLink
        label: 
          fr: Un projet ?
          en: A project ?

  - name: gallery
    disabled: false
    # icon: image
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Exemples
      en: Examples
    submenu:
      - name: demo-cooptech
        link: /demo-cooptech
        component: simpleLink
        label: 
          fr: Cooptech - annuaire
          en: Cooptech - organisations
      - name: sep
        separator: true
      - name: demo-odf-observatoire
        link: /demo-odf-observatoire
        component: simpleLink
        label: 
          fr: Open Data France - Données de l'Observatoire
          en: Open Data France - Observatory's datasets
      - name: demo-odf-ressources
        link: /demo-odf-ressources
        component: simpleLink
        label: 
          fr: Open Data France - Ressources
          en: Open Data France - Ressources
      - name: sep
        separator: true
      - name: demo-fabmob
        link: /demo-fabmob
        component: simpleLink
        label: 
          fr: Fabmob - Projets du wiki
          en: Fabmob - Projects from wikimedia
      - name: demo-aac
        link: /demo-aac
        component: simpleLink
        label: 
          fr: AAC - Projets du wiki
          en: AAC - Projects from wikimedia

  - name: docs 
    # icon: book-open-variant
    link: https://gitribute-docs.multi.coop
    component: dropdownLink
    # component: extLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Docs
      en: Docs
    # label_after_icon: true
    submenu:
      - name: features
        link: /main-features
        component: simpleLink
        label: 
          fr: Principales fonctionnalités
          en: Main features
      - name: software
        link: /software
        component: simpleLink
        label: 
          fr: Infos sur le logiciel
          en: Software infos
      - name: sep
        separator: true
      - name:
        link: https://gitribute-docs.multi.coop
        component: extLink
        # options: [ arrowless ]
        label:
          fr: Site officiel de documentation
          en: Official documentation website

  - name: contact 
    # icon: email
    link: /contact
    component: simpleLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Contactez-nous
      en: Contact us

buttons-right: 

  - name: multi
    link: https://multi.coop
    image: https://raw.githubusercontent.com/multi-coop/vizboard-website-content/main/images/logos/logo-multi-003.png
    icon: open-in-new
    component: extLink
    options: [ arrowless ]
    label: 
      fr: Un projet par la coopérative multi
      en: A project by the tech cooperative multi

  - name: blog 
    # icon: at
    link: /blog
    component: simpleLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Blog
      en: Blog

  - name: repo 
    link: https://gitlab.com/multi-coop/gitribute
    icon: gitlab
    component: extLink
    options: [ arrowless ]
    label: 
      fr: Code source de Datami
      en: Datami source code

  - name: switch-locale
    component: switchLocaleDropdown
    options: [ arrowless, uppercase, rounded, hoverable ]


--- 

# Navbar config file
