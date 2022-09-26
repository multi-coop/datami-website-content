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
        fr: Page d'accueil de la documentation de Datami
        en: Homepage for Datami documentation
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
      - name: landing-clients
        component: TextComponent
        options:
          columns-size: full
          custom-class: my-6 py-6
          name:
            fr: Ils soutiennent Vizbord
            en: They support vizborad
        files:
          fr: ./texts/fr/landing/landing-clients.md
          en: ./texts/en/landing/landing-clients.md
      - name: landing-demo-intro
        component: TextComponent
        options:
          columns-size: full
          custom-class: mt-6 pt-6 is-hidden-mobile
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
      - name: btn-to-contact
        component: ButtonsComponent
        options:
          columns-size: three-quarters
          custom-class: mt-0 mb-6 pt-6 mx-6
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

  - name: main-features
    url: /main-features
    options:
      summary: true
      contrib: true
      name:
        fr: Principales fonctionnalités
        en: Main features
      description:
        fr: Les fonctionnalités principales et innovantes de nos widgets
        en: The widgets' main original features
      keywords:
        fr: [ éditer, contribuer, partager, adapter, visualiser, dataviz ]
        en: [ edit, contribute, share, adapt, visualise, dataviz ]
    sections: 
      - name: main-features
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Introduction
            en: Introduction
        files:
          fr: ./texts/fr/main-features/main-features.md
          en: ./texts/en/main-features/main-features.md
      - name: main-features-visualize
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Visualiser vos données
            en: Data-visualisaze your data
        files:
          fr: ./texts/fr/main-features/main-features-visualize.md
          en: ./texts/en/main-features/main-features-visualize.md
      - name: main-features-edit
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Éditer & contribuer online
            en: Edit & contribute online
        files:
          fr: ./texts/fr/main-features/main-features-edit.md
          en: ./texts/en/main-features/main-features-edit.md
      - name: main-features-share
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Partager vos jeux de données
            en: Share your datasets
        files:
          fr: ./texts/fr/main-features/main-features-share.md
          en: ./texts/en/main-features/main-features-share.md
      - name: main-features-adapt
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Adapter les widgets à vos besoins
            en: Adapt the widgets to your needs
        files:
          fr: ./texts/fr/main-features/main-features-adapt.md
          en: ./texts/en/main-features/main-features-adapt.md
      - name: Contact
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          custom-class: mt-6
          buttons:
            - link: "mailto:contact@multi.coop"
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Nous contacter
                en: Contact us
      - name: logo-multi
        component: TextComponent
        options:
          columns-size: full
          custom-class: mt-6
          not-in-menu: true
        files:
          fr: ./texts/fr/landing/landing-multi.md
          en: ./texts/en/landing/landing-multi.md
 
  - name: software
    url: /software
    options:
      contrib: true
      summary: true
      name:
        fr: Infos sur le logiciel
        en: Software informations
    sections: 
      - name: docs-licence
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Licence
            en: Licence
        files:
          fr: ./texts/fr/software/licence.md
          en: ./texts/en/software/licence.md
      - name: docs-stack
        component: TextComponent
        options:
          columns-size: three-quarters
          name:
            fr: Stack
            en: Stack
        files:
          fr: ./texts/fr/software/stack.md
          en: ./texts/en/software/stack.md
      - name: Contact
        component: ButtonsComponent
        options:
          columns-size: two-thirds
          buttons-size: half
          custom-class: mt-6
          buttons:
            # - link: /roadmap
            #   icon-left: map-search-outline
            #   rounded: true
            #   label: 
            #     fr: Roadmap
            #     en: Roadmap
            - link: https://gitlab.com/multi-coop/gitribute
              icon-left: gitlab
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Code source
                en: Source code
            - link: /contact
              # icon-left: email
              rounded: false
              size: is-large
              style: "box-shadow: -5px 5px 5px #D7D7D7;"
              label: 
                fr: Nous contacter
                en: Contact us
      - name: logo-multi
        component: TextComponent
        options:
          columns-size: full
          custom-class: mt-6
          not-in-menu: true
        files:
          fr: ./texts/fr/landing/landing-multi.md
          en: ./texts/en/landing/landing-multi.md


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
  - name: demo-cooptech
    url: /demo-cooptech
    options:
      contrib: true
      name:
        fr: Démo Cooptech
        en: Demo Cooptech
      description:
        fr: Démonstrateur avec les données de Cooptech
        en: Demonstrator with Cooptech dataset
      keywords:
        fr: [ démo, cooptech ]
        en: [ demo, cooptech ]
    sections:
      - name: demo-datami-cooptech
        component: HtmlComponent
        options:
          columns-size: three-quarters
        files:
          fr: ./texts/gallery/demo-cooptech.html
          en: ./texts/gallery/demo-cooptech.html
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
  - name: demo-odf-observatoire
    url: /demo-odf-observatoire
    options:
      contrib: true
      name:
        fr: Démo Open Data France | Observatoire
        en: Demo Open Data France | Observatory
      description:
        fr: Démonstrateur avec les données de l'Observatoire d'Open Data France
        en: Demonstrator with Open Data France Observatory dataset
      keywords:
        fr: [ démo, ODF ]
        en: [ demo, ODF ]
    sections:
      - name: demo-datami-odf-observatoire
        component: HtmlComponent
        options:
          columns-size: three-quarters
        files:
          fr: ./texts/gallery/demo-odf-observatoire.html
          en: ./texts/gallery/demo-odf-observatoire.html
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
  - name: demo-odf-ressources
    url: /demo-odf-ressources
    options:
      contrib: true
      name:
        fr: Démo Open Data France | Ressources
        en: Demo Open Data France | Ressources
      description:
        fr: Démonstrateur avec les données des Ressources d'Open Data France
        en: Demonstrator with Open Data France Ressources dataset
      keywords:
        fr: [ démo, ODF ]
        en: [ demo, ODF ]
    sections:
      - name: demo-datami-odf-ressources
        component: HtmlComponent
        options:
          columns-size: three-quarters
        files:
          fr: ./texts/gallery/demo-odf-ressources.html
          en: ./texts/gallery/demo-odf-ressources.html
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
