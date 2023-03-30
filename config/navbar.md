---
background-color: white
# logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logo_GITRIBUTE.png
# logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-rect-colors-01.png
# logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-rect-colors-02.png
logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-rect-colors-03.png
# logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-square-colors-02.png
# logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-square-colors-03.png
# logo-left: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-square-colors-04.png

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
      # - name: video-presentation
      #   link: /
      #   scrollTo: landing-video-presentation
      #   component: simpleLink
      #   label: 
      #     fr: Vidéo de présentation
      #     en: Video
      - name: offer
        link: /
        scrollTo: landing-offer
        component: simpleLink
        label: 
          fr: Notre offre
          en: Our offer
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
      - name: tutorial
        link: /
        scrollTo: landing-tutorial
        component: simpleLink
        label: 
          fr: Tour d'horizon
          en: Quick tour
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
      - name: slides
        link: /
        scrollTo: landing-slides
        component: simpleLink
        label: 
          fr: Présentation 
          en: Slides
      - name: sponsors
        link: /
        scrollTo: landing-sponsors
        component: simpleLink
        label: 
          fr: Sponsors 
          en: Sponsors
  
  - name: examples 
    link: /examples
    component: simpleLink
    tag:
      type: success
      rounded: true
      label: 
        fr: new
        en: new
    options: [ arrowless, hoverable ]
    label: 
      fr: Exemples
      en: Examples
  
  # - name: gallery
  #   disabled: false
  #   # icon: image
  #   component: dropdownLink
  #   options: [ arrowless, hoverable ]
  #   label: 
  #     fr: Exemples
  #     en: Examples
  #   submenu:
  #     - name: odf-observatoire
  #       link: https://carto.observatoire-opendata.fr/
  #       component: extLink
  #       label:
  #         fr: Open Data France - observatoire
  #         en: Open Data France - observatory
  #       tag:
  #         type: light-info
  #         label: 
  #           fr: data
  #           en: data
  #     - name: sep
  #       separator: true
  #     - name: demo-rhinocc
  #       link: https://rhinocc-carto-preprod.netlify.app/
  #       component: extLink
  #       label:
  #         fr: Rhinocc - médiation numérique
  #         en: Rhinocc - digital mediation
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: demo-conumm
  #       link: https://www.carto.conumm.fr
  #       component: extLink
  #       label:
  #         fr: CONUMM - médiation numérique
  #         en: CONUMM - digital mediation
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: demo-ternum
  #       link: https://bfc-carto.netlify.app/
  #       component: extLink
  #       label:
  #         fr: BFC Ternum - médiation numérique
  #         en: BFC Ternum - digital mediation
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: demo-doubs
  #       link: https://inclusionnumerique.doubs.fr/
  #       component: extLink
  #       label:
  #         fr: Département du Doubs - médiation numérique
  #         en: Doubs - digital mediation
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: sep
  #       separator: true
  #     - name: demo-ping
  #       link: https://tierslieux.cartes.pingbase.net/
  #       component: extLink
  #       label:
  #         fr: Ping - tiers-lieux
  #         en: Ping - tiers-lieux
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: sep
  #       separator: true
  #     - name: demo-ifn
  #       link: https://etude-ifn-parentalite.netlify.app/
  #       component: extLink
  #       label:
  #         fr: La Trousse à projets - indice de fragilité numérique parentalité
  #         en: La Trousse à projets - parental digital fragility index
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: demo-mednum-fs
  #       link: https://mednum-france-services.netlify.app/?datami_tab=1&datami_view=map&datami_lon=2.539215&datami_lat=48.830374&datami_zoom=12&datami_detail_id=147
  #       component: extLink
  #       label:
  #         fr: France Services - données sur les lieux
  #         en: France Services - données sur les lieux
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     - name: sep
  #       separator: true
  #     - name: decider-ensemble
  #       link: https://decider-ensemble.netlify.app/
  #       component: extLink
  #       label:
  #         fr: Décider Ensemble - ressources
  #         en: Décider Ensemble - ressources
  #       tag:
  #         type: success
  #         label: 
  #           fr: new
  #           en: new
  #     # - name: sep
  #     #   separator: true
  #     # - name: demo-cooptech
  #     #   link: /demo-cooptech
  #     #   component: simpleLink
  #     #   label: 
  #     #     fr: Cooptech - annuaire
  #     #     en: Cooptech - organisations
  #     # - name: sep
  #     #   separator: true
  #     # - name: demo-odf-observatoire
  #     #   link: /demo-odf-observatoire
  #     #   component: simpleLink
  #     #   label: 
  #     #     fr: Open Data France - Données de l'Observatoire
  #     #     en: Open Data France - Observatory's datasets
  #     # - name: demo-odf-ressources
  #     #   link: /demo-odf-ressources
  #     #   component: simpleLink
  #     #   label: 
  #     #     fr: Open Data France - Ressources
  #     #     en: Open Data France - Ressources
  #     - name: sep
  #       separator: true
  #     - name: demo-fabmob
  #       link: /demo-fabmob
  #       component: simpleLink
  #       label: 
  #         fr: Fabmob - Projets du wiki
  #         en: Fabmob - Projects from wikimedia
  #       tag:
  #         type: light-warning
  #         label: 
  #           fr: wiki
  #           en: wiki
  #     - name: demo-aac
  #       link: /demo-aac
  #       component: simpleLink
  #       label: 
  #         fr: AAC - Projets du wiki
  #         en: AAC - Projects from wikimedia
  #       tag:
  #         type: light-warning
  #         label: 
  #           fr: wiki
  #           en: wiki
  #     - name: sep
  #       separator: true
  #     - name: katalog
  #       link: https://konsilion.fr/katalog/projets/home/
  #       component: extLink
  #       label:
  #         fr: Konsilion - Katalog
  #         en: Konsilion - Katalog
  #       tag:
  #         type: success
  #         label: 
  #           fr: libre
  #           en: libre

  - name: Infos
    link: https://www.youtube.com/watch?v=HLKrmth6qbA
    component: dropdownLink
    options: [ arrowless, hoverable ]
    label:
      fr: Infos
      en: Infos
    submenu:
      - name: live-sessions
        link: https://www.youtube.com/watch?v=HLKrmth6qbA
        component: extLink
        label:
          fr: Démo (replay)
          en: Live demo (replay)
      - name: presentation
        link: /presentation-slides
        component: simpleLink
        tag:
          type: warning
          rounded: true
          label: 
            fr: new
            en: new
        label:
          fr: Présentation
          en: Slides
      - name: roadmap
        link: /roadmap
        component: simpleLink
        tag:
          type: warning
          rounded: true
          label: 
            fr: new
            en: new
        label:
          fr: Feuille de route
          en: Roadmap
      - name: benchmark
        link: /benchmark
        component: simpleLink
        tag:
          type: warning
          rounded: true
          label: 
            fr: new
            en: new
        label:
          fr: Benchmark
          en: Benchmark

  - name: docs 
    # icon: book-open-variant
    link: https://datami-docs.multi.coop
    # component: dropdownLink
    component: extLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Documentation
      en: Documentation
    # label_after_icon: true
    # submenu:
    #   - name: features
    #     link: /main-features
    #     component: simpleLink
    #     label: 
    #       fr: Principales fonctionnalités
    #       en: Main features
    #   - name: software
    #     link: /software
    #     component: simpleLink
    #     label: 
    #       fr: Infos sur le logiciel
    #       en: Software infos
    #   - name: sep
    #     separator: true
    #   - name:
    #     link: https://datami-docs.multi.coop
    #     component: extLink
    #     # options: [ arrowless ]
    #     label:
    #       fr: Site officiel de documentation
    #       en: Official documentation website

  - name: contact 
    # icon: email
    link: /contact
    component: simpleLink
    options: [ arrowless, hoverable ]
    label: 
      fr: Contact
      en: Contact

buttons-right: 

  - name: multi
    link: https://multi.coop
    image: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-multi-003.png
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

  - name: repo Gitlab
    link: https://gitlab.com/multi-coop/datami-project/datami
    icon: gitlab
    component: extLink
    options: [ arrowless ]
    label: 
      fr: Code source de Datami
      en: Datami source code
  - name: repo Github
    link: https://github.com/multi-coop/datami
    icon: github
    component: extLink
    options: [ arrowless ]
    label: 
      fr: Code source de Datami (miroir)
      en: Datami source code (mirror)

  - name: switch-locale
    component: switchLocaleDropdown
    options: [ arrowless, uppercase, rounded, hoverable ]


--- 

# Navbar config file
