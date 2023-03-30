---
routes: 

  # LANDING
  - name: home
    url: /
    options:
      # hero: true
      # summary: true
      # contrib: true
      name:
        fr: Accueil
        en: Homepage
      description:
        fr: Page d'accueil
        en: Homepage
      keywords:
        fr: [ accueil, landing ]
        en: [ homepage, landing ]
    sections:
      - name: landing
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          # custom-class: my-6
          name:
            fr: Introduction
            en: Introduction
        files:
          fr: ./texts/fr/landing/landing.md
          en: ./texts/en/landing/landing.md
      # - name: landing-video-presentation
      #   component: TextComponent
      #   options:
      #     columns-size: full
      #     custom-class: mt-0 pt-0
      #     name:
      #       fr: Vidéo
      #       en: Video
      #   files:
      #     fr: ./texts/fr/landing/landing-video-presentation.md
      #     en: ./texts/fr/landing/landing-video-presentation.md
      - name: landing-offer
        component: TextComponent
        options:
          columns-size: full
          custom-class: mt-0 pt-6
          name:
            fr: Notre offre
            en: Our offer
        files:
          fr: ./texts/fr/landing/landing-offer.md
          en: ./texts/en/landing/landing-offer.md
      - name: landing-clients
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-6 py-6 mx-4
          name:
            fr: Ils soutiennent Datami
            en: They support Datami
        files:
          fr: ./texts/fr/landing/landing-clients.md
          en: ./texts/en/landing/landing-clients.md
      - name: landing-demo-intro
        component: TextComponent
        options:
          columns-size: full
          custom-class: mt-6 pt-6 mb-0 pb-0 is-hidden-mobile
          name:
            fr: Exemple d'intégration d'un vizboard
            en: An example of a vizboard
        files:
          fr: ./texts/fr/landing/landing-demo-intro.md
          en: ./texts/en/landing/landing-demo-intro.md
      - name: demo-datami-odf-observatoire
        component: HtmlComponent
        options:
          columns-size: three-quarters
          custom-class: mb-6 pb-6 is-hidden-mobile
          name:
            fr: Découvrir
            en: Discover
        files:
          fr: ./texts/gallery/demo-odf-observatoire.html
          en: ./texts/gallery/demo-odf-observatoire.html
      - name: landing-simplify
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          custom-class: mt-6 pt-6
          name:
            fr: Simplifier vos dataviz
            en: Simplify your dataviz
        files:
          fr: ./texts/fr/landing/landing-before-after.md
          en: ./texts/en/landing/landing-before-after.md
      - name: landing-tutorial
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          custom-class: mt-6 pt-6
          name:
            fr: Tutoriel
            en: Tutorial
        files:
          fr: ./texts/fr/landing/landing-video-tutorial.md
          en: ./texts/en/landing/landing-video-tutorial.md
      - name: btn-to-contact
        component: ButtonsComponent
        options:
          columns-size: three-quarters
          custom-class: mt-0 mb-6 pt-4 mx-6
          buttons-size: one-third
          buttons:
            - link: "mailto:contact@multi.coop"
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Contactez-nous
                en: Contact us
      - name: landing-features
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          custom-class: mt-6 pt-6 mx-6
          name:
            fr: Fonctionnalités
            en: Features
        files:
          fr: ./texts/fr/landing/landing-features.md
          en: ./texts/en/landing/landing-features.md
      - name: landing-tool
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          custom-class: my-6 pb-6
          name:
            fr: Un outil multi-fonctions
            en: A multi-features tool
        files:
          fr: ./texts/fr/landing/landing-tool.md
          en: ./texts/en/landing/landing-tool.md
      - name: landing-ideal
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          custom-class: my-6 pb-6 mx-6
          name:
            fr: Idéal pour...
            en: Ideal tool for...
        files:
          fr: ./texts/fr/landing/landing-ideal.md
          en: ./texts/en/landing/landing-ideal.md
      - name: landing-cta
        component: TextComponent
        options:
          columns-size: full
          # hero: true
          custom-class: mt-6 pt-6
          name:
            fr: Un projet ?
            en: A project ?
        files:
          fr: ./texts/fr/landing/landing-cta.md
          en: ./texts/en/landing/landing-cta.md
      - name: btn-to-contact
        component: ButtonsComponent
        options:
          columns-size: three-quarters
          custom-class: my-6 mx-6
          buttons-size: one-third
          buttons:
            - link: "mailto:contact@multi.coop"
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Contactez-nous
                en: Contact us
      - name: landing-slides-title
        component: TextComponent
        options:
          columns-size: full
          custom-class: py-6 mt-6 mx-2
          name:
            fr: Slides title
            en: Slides title
        files:
          fr: ./texts/fr/landing/landing-slides-title.md
          en: ./texts/en/landing/landing-slides-title.md
      - name: landing-slides
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-6 py-6 mt-6 mx-2
          name:
            fr: Slides
            en: Slides
        files:
          fr: ./texts/fr/landing/landing-slides.md
          en: ./texts/en/landing/landing-slides.md
      - name: landing-sponsors
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-6 py-6 mt-6 mx-2
          name:
            fr: Développé avec le soutien de
            en: Developped with the support of
        files:
          fr: ./texts/fr/landing/landing-sponsors.md
          en: ./texts/en/landing/landing-sponsors.md
  
  - name: Presentation
    url: /presentation-slides
    options:
      name:
        fr: Présentation
        en: Presentation
      description:
        fr: Présentation
        en: Presentation
      keywords:
        fr: [ slides ]
        en: [ slides ]
    sections:
      - name: landing-slides
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-0 py-0
          name:
            fr: Slides
            en: Slides
        files:
          fr: ./texts/fr/landing/landing-slides.md
          en: ./texts/en/landing/landing-slides.md

  - name: Roadmap
    url: /roadmap
    options:
      name:
        fr: Roadmap
        en: Roadmap
      description:
        fr: Roadmap
        en: Roadmap
      keywords:
        fr: [ slides ]
        en: [ slides ]
    sections:
      - name: roadmap-head
        component: TextComponent
        options:
          columns-size: half
          custom-class: mt-6 mb-0 py-0
          name:
            fr: Roadmap head
            en: Roadmap head
        files:
          fr: ./texts/roadmap/fr/roadmap-head.md
          en: ./texts/roadmap/en/roadmap-head.md
      - name: roadmap-tech
        component: TextComponent
        options:
          columns-size: full
          custom-class: mb-0 py-0
          name:
            fr: Roadmap tech
            en: Roadmap tech
        files:
          fr: ./texts/roadmap/roadmap-tech.md
          en: ./texts/roadmap/roadmap-tech.md
      # - name: roadmap-bizdev
      #   component: TextComponent
      #   options:
      #     columns-size: full
      #     custom-class: my-0 py-0
      #     name:
      #       fr: Roadmap bizdev
      #       en: Roadmap bizdev
      #   files:
      #     fr: ./texts/roadmap/roadmap-bizdev.md
      #     en: ./texts/roadmap/roadmap-bizdev.md
      - name: roadmap-legend
        component: TextComponent
        options:
          columns-size: half
          custom-class: my-0 py-0
          name:
            fr: Roadmap legend
            en: Roadmap legend
        files:
          fr: ./texts/roadmap/fr/roadmap-legend.md
          en: ./texts/roadmap/en/roadmap-legend.md

  - name: Benchmark
    url: /benchmark
    options:
      name:
        fr: Benchmark
        en: Benchmark
      description:
        fr: Benchmark
        en: Benchmark
      keywords:
        fr: [ benchmark ]
        en: [ benchmark ]
    sections:
      - name: benchmark-head
        component: TextComponent
        options:
          columns-size: half
          custom-class: mb-0 py-0
          name:
            fr: Benchmark head
            en: Benchmark head
        files:
          fr: ./texts/benchmark/fr/benchmark-head.md
          en: ./texts/benchmark/en/benchmark-head.md
      - name: benchmark-features
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-0 py-0
          name:
            fr: Benchmark features
            en: Benchmark features
        files:
          fr: ./texts/benchmark/benchmark-features.md
          en: ./texts/benchmark/benchmark-features.md
      - name: benchmark-legend
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-0 py-0
          name:
            fr: Benchmark legend
            en: Benchmark legend
        files:
          fr: ./texts/benchmark/fr/benchmark-legend.md
          en: ./texts/benchmark/en/benchmark-legend.md
      - name: benchmark-dataviz
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-0 py-0
          name:
            fr: Benchmark dataviz
            en: Benchmark dataviz
        files:
          fr: ./texts/benchmark/benchmark-dataviz.md
          en: ./texts/benchmark/benchmark-dataviz.md
      - name: benchmark-edition
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-0 py-0
          name:
            fr: Benchmark edition
            en: Benchmark edition
        files:
          fr: ./texts/benchmark/benchmark-edition.md
          en: ./texts/benchmark/benchmark-edition.md

  - name: Examples 
    url: /examples
    options:
      name:
        fr: Exemples
        en: Examples
      description:
        fr: Exemples
        en: Examples of Datami implementation
      keywords:
        fr: [ examples ]
        en: [ examples ]
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
        files:
          fr: ./texts/examples/fr/examples-head.md
          en: ./texts/examples/en/examples-head.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/examples/fr/examples-data.md
          en: ./texts/examples/en/examples-data.md

  # STANDARD ROUTES
  - name: Contact
    url: /contact
    options:
      hero: true
      name:
        fr: Contactez-nous
        en: Contact us
      description:
        fr: Contactez-nous pour plus d'infos
        en: Contact us for more infos
      keywords:
        fr: [ contact, mail ]
        en: [ contact, mail ]
    sections: 
      - name: Contact
        component: TextComponent
        options:
          columns-size: three-quarters
          # custom-class: mt-6
          # columns-divider: h1
        files:
          fr: ./texts/fr/contact/contact-head.md
          en: ./texts/en/contact/contact-head.md
  - name: legal
    url: /legal
    options:
      name:
        fr: Mentions légales
        en: Legal
      description:
        fr: Mentions légales
        en: Legal mentions
      keywords:
        fr: [ contact, légal ]
        en: [ contact, legal ]
    sections: 
      # - name: data
      #   component: TextDataComponent
      #   files:
      #     fr: ./texts/fr/contact/legal-data.md
      - name: legal-text
        component: TextComponent
        files:
          fr: ./texts/fr/contact/legal-mentions.md
          en: ./texts/en/contact/legal-mentions.md
      - name: Contact
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          buttons:
            - link: /contact
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Nous contacter
                en: Contact us

  # GALLERY - HTML
  # - name: demo-cooptech
  #   url: /demo-cooptech
  #   options:
  #     contrib: true
  #     name:
  #       fr: Démo Cooptech
  #       en: Demo Cooptech
  #     description:
  #       fr: Démonstrateur avec les données de Cooptech
  #       en: Demonstrator with Cooptech dataset
  #     keywords:
  #       fr: [ démo, cooptech ]
  #       en: [ demo, cooptech ]
  #   sections:
  #     - name: demo-datami-cooptech
  #       component: HtmlComponent
  #       options:
  #         columns-size: three-quarters
  #       files:
  #         fr: ./texts/gallery/demo-cooptech.html
  #         en: ./texts/gallery/demo-cooptech.html
  #     - name: Contact
  #       component: ButtonsComponent
  #       options:
  #         columns-size: two-thirds
  #         buttons-size: half
  #         custom-class: mt-6
  #         buttons:
  #           - link: /contact
  #             # icon-left: email
  #             rounded: false
  #             size: is-large
  #             style: "box-shadow: -5px 5px 5px #D7D7D7;"
  #             label: 
  #               fr: Nous contacter
  #               en: Contact us
  # - name: demo-odf-observatoire
  #   url: /demo-odf-observatoire
  #   options:
  #     contrib: true
  #     name:
  #       fr: Démo Open Data France | Observatoire
  #       en: Demo Open Data France | Observatory
  #     description:
  #       fr: Démonstrateur avec les données de l'Observatoire d'Open Data France
  #       en: Demonstrator with Open Data France Observatory dataset
  #     keywords:
  #       fr: [ démo, ODF ]
  #       en: [ demo, ODF ]
  #   sections:
  #     - name: demo-datami-odf-observatoire
  #       component: HtmlComponent
  #       options:
  #         columns-size: three-quarters
  #       files:
  #         fr: ./texts/gallery/demo-odf-observatoire.html
  #         en: ./texts/gallery/demo-odf-observatoire.html
  #     - name: Contact
  #       component: ButtonsComponent
  #       options:
  #         columns-size: two-thirds
  #         buttons-size: half
  #         custom-class: mt-6
  #         buttons:
  #           - link: /contact
  #             # icon-left: email
  #             rounded: false
  #             size: is-large
  #             style: "box-shadow: -5px 5px 5px #D7D7D7;"
  #             label: 
  #               fr: Nous contacter
  #               en: Contact us
  # - name: demo-odf-ressources
  #   url: /demo-odf-ressources
  #   options:
  #     contrib: true
  #     name:
  #       fr: Démo Open Data France | Ressources
  #       en: Demo Open Data France | Ressources
  #     description:
  #       fr: Démonstrateur avec les données des Ressources d'Open Data France
  #       en: Demonstrator with Open Data France Ressources dataset
  #     keywords:
  #       fr: [ démo, ODF ]
  #       en: [ demo, ODF ]
  #   sections:
  #     - name: demo-datami-odf-ressources
  #       component: HtmlComponent
  #       options:
  #         columns-size: three-quarters
  #       files:
  #         fr: ./texts/gallery/demo-odf-ressources.html
  #         en: ./texts/gallery/demo-odf-ressources.html
  #     - name: Contact
  #       component: ButtonsComponent
  #       options:
  #         columns-size: two-thirds
  #         buttons-size: half
  #         custom-class: mt-6
  #         buttons:
  #           - link: /contact
  #             # icon-left: email
  #             rounded: false
  #             size: is-large
  #             style: "box-shadow: -5px 5px 5px #D7D7D7;"
  #             label: 
  #               fr: Nous contacter
  #               en: Contact us
  - name: demo-fabmob
    url: /demo-fabmob
    options:
      contrib: true
      name:
        fr: Démo Fabmob
        en: Demo Fabmob
      description:
        fr: Démonstrateur avec les données wiki de la Fabrique des mobilités
        en: Demonstrator with Fabmob wiki dataset
      keywords:
        fr: [ démo, fabmob ]
        en: [ demo, fabmob ]
    sections:
      - name: demo-datami-fabmob
        component: HtmlComponent
        options:
          columns-size: three-quarters
        files:
          fr: ./texts/gallery/demo-fabmob.html
          en: ./texts/gallery/demo-fabmob.html
      - name: Contact
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          custom-class: mt-6
          buttons:
            - link: /contact
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Nous contacter
                en: Contact us
  - name: demo-aac
    url: /demo-aac
    options:
      contrib: true
      name:
        fr: Démo appel à communs de l'ADEME
        en: Demo AAC ADEME
      description:
        fr: Démonstrateur avec les données wiki de l'appel à communs de l'ADEME
        en: Demonstrator with ADEME-AAC wiki dataset
      keywords:
        fr: [ démo, ADEME ]
        en: [ demo, ADEME ]
    sections:
      - name: demo-datami-aac
        component: HtmlComponent
        options:
          columns-size: three-quarters
        files:
          fr: ./texts/gallery/demo-aac.html
          en: ./texts/gallery/demo-aac.html
      - name: Contact
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          custom-class: mt-6
          buttons:
            - link: /contact
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Nous contacter
                en: Contact us

  # BLOG
  - name: blog
    url: /blog
    options:
      name:
        fr: Espace de blog
        en: Blog section
      description:
        fr: Espace de blog du projet Datami
        en: Blog section of Datami
      keywords:
        fr: [ blog ]
        en: [ blog ]
    sections: 
      - name: head
        component: TextComponent
        options:
          columns-size: two-thirds
        files:
          fr: ./texts/blog/fr/blog-head.md
          en: ./texts/blog/en/blog-head.md
      - name: data
        component: DataGrid
        files:
          fr: ./texts/blog/fr/blog-data.md
          en: ./texts/blog/en/blog-data.md
--- 
