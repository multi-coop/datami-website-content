---
app_name: Datami
show_app_name: true
app_default_locale: fr
app_locales: [
  en,
  fr
]
app_md_flavor: github
app_icon: ./images/logos/logo-DATAMI-rect-colors-03.png
app_favicon: https://raw.githubusercontent.com/multi-coop/datami-website-content/main/images/logos/logo-DATAMI-favicon.ico

routes: ./config/routes.md
navbar: ./config/navbar.md
footer: ./config/footer.md
legal: ./config/legal.md

# contents: 
#   texts: ./texts
#   images: ./images
#   data: ./data

custom_colors: true
colors:
  primary: '#000000'
  # loading_color: '#6fdcbf'
  # accent: '#572a99'
  # secondary: '#6fdcbf'
  # info: '#53657D'
  # warning: '#ff9947'
  # error: '#D1335B'
  # success: '#03BD5B'

custom_css: true
custom_css_files:
  - ./styles/custom-css-datami.css

matomo:
  matomo_active: true
  matomo_server: multi.matomo.cloud
  matomo_site_id: 4
  matomo_track_outlinks: true

seo_keywords: [
  widget, datami, git, no code, viz, board, map, table, dataviz, wiki,
  csv, md, json,
  open source
]

---


# Config file

This file `config.md` contains the main configuration in the yaml part on top... :kissing_heart:
