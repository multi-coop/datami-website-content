<div>

  <!-- <hr> -->

  <!-- DATAMI - contribute with GIT ...but without minding it-->
  <!-- An open source widget coded with 🤍  by the tech cooperative multi : https://multi.coop -->

  <!-- DATAMI WIDGET'S HTML BLOCK-->
  <datami-multi-files
    title="Données d&lsquo;Open Data France"
    options='{
      "display": "horizontal"
    }'
    gitfiles='[
    {
      "title": "Données de l&lsquo;observatoire",
      "activate": true,
      "gitfile": "https://github.com/multi-coop/gitribute-content-test/blob/main/data/csv/odf/ODF-Observatoire-apiviz_data-export_solidata-220425b-simplified.csv",
      "default-tab": true,
      "options": {
        "height": "500px",
        "separator": ";",
        "lockcolumns": true,
        "customfilters": {
          "activate": true,
          "filterfields": [
            {
              "name": "type",
              "filtering": "OR"
            },
            "platform_clean",
            "depcode"
          ]
        },
        "schema": {
          "file": "https://github.com/multi-coop/gitribute-content-test/blob/main/data/json/odf/ODF-Observatoire-apiviz_data-schema.json"
        },
        "fields-custom-properties": {
          "file": "https://github.com/multi-coop/gitribute-content-test/blob/main/data/json/odf/ODF-Observatoire-apiviz_data-fields-custom-props.json"
        },
        "cardsview": {
          "activate": true,
          "default": false
        },
        "cardsdetail": true,
        "cardssettings": {
          "mini": {
            "nom": {
              "position": "title"
            },
            "id_odf": {
              "position": "subtitle",
              "prefix": "Identifiant :"
            },
            "adress": {
              "position": "adress"
            },
            "siren": {
              "position": "resume",
              "prefix": "Numéro SIREN :"
            },
            "tags": {
              "position": "tags"
            }
          },
          "detail": {
            "nom": {
              "position": "title"
            },
            "id_odf": {
              "position": "subtitle",
              "prefix": "Identifiant :"
            },
            "adress": {
              "position": "adress"
            },
            "siren": {
              "position": "description",
              "prefix": "Numéro SIREN :",
              "block_title": "Description"
            },
            "url_ptf": {
              "position": "links",
              "block_title": "Lien vers la plateforme"
            },
            "url_datagouv": {
              "position": "links",
              "block_title": "Lien vers data.gouv.fr"
            },
            "dep_label": {
              "position": "tags",
              "block_title": "Département(s)"
            },
            "tags": {
              "position": "tags",
              "block_title": "Tags thématiques",
              "right": true
            }
          },
          "templates": {
            "siren": {
              "use_on_mini": true,
              "use_on_detail": true,
              "paragraphs": [
                {
                  "text": {
                    "fr": "L‘organisation {{ nom }} est une {{ type }} et se situe dans le département {{ depcode }} ({{ dep_label }}) en région {{ reg_code_short }}."
                  }
                },
                {
                  "text": {
                    "fr": "Cette commune représente une population de {{ pop_insee }} habitants."
                  }
                },
                {
                  "text": {
                    "fr": "{{ nom }} publie sur {{ merge }} avec une plateforme de type {{ platform_clean }}."
                  }
                },
                {
                  "text": {
                    "fr": "Cette organisation a publié {{ nb_ptf }} jeux de données sur sa plateforme et {{ nb_datagouv }} jeux sur data.gouv.fr."
                  }
                },
                {
                  "text": {
                    "fr": "Plus d‘infos en cliquant sur ici : ~~ url_ptf ~~"
                  }
                }
              ]
            }
          },
          "minimap": {
            "activate": true,
            "right_side": true,
            "mapOptions": {
              "zoom": 5,
              "maxZoom": 18,
              "minZoom": 2,
              "item_geo_fields": {
                "latitude": "lat",
                "longitude": "lon"
              },
              "zoom_item": 13,
              "marker_icon": "map-marker",
              "marker_height": 45,
              "marker_width": 45,
              "marker_color": "#4a4a4a"
            }
          }
        },
        "datavizview": {
          "activate": true,
          "default": false,
          "file": "https://github.com/multi-coop/data-odf-observatoire/blob/main/json/ODF-Observatoire-dataviz-settings.json"
        },
        "mapview": {
          "activate": true,
          "default": true,
          "maps": [
            {
              "title": {
                "fr": "CARTOGRAPHIE DES ACTEURS DE L‘OPEN DATA"
              },
              "cols": 12,
              "file": "https://github.com/multi-coop/data-odf-observatoire/blob/main/json/ODF-Observatoire-map-settings.json"
            }
          ]
        }
      },
      "usertoken": ""
    },
    {
      "title": "Thématiques",
      "activate": true,
      "gitfile": "https://github.com/multi-coop/gitribute-content-test/blob/main/data/csv/odf/ODF-Observatoire-thematiques.csv",
      "options": {
        "height": "500px",
        "separator": ",",
        "lockcolumns": true,
        "customfilters": {
          "activate": true,
          "filterfields": [
            "Tags",
            "Organisations_Noms"
          ]
        },
        "schema": {
          "fields": [
            {
              "name": "Organisations copy",
              "type": "boolean"
            }
          ]
        },
        "fields-custom-properties": {
          "file": "https://github.com/multi-coop/gitribute-content-test/blob/main/data/json/odf/ODF-thematiques-fields-custom-props.json"
        }
      },
      "onlypreview": true,
      "usertoken": ""
    },
    {
      "title": "Schéma des données de l&lsquo;observatoire",
      "activate": true,
      "default-tab": false,
      "gitfile": "https://github.com/multi-coop/gitribute-content-test/blob/main/data/json/odf/ODF-Observatoire-apiviz_data-schema.json",
      "options": {
        "defaultDepth": 2,
        "allowKeyEdit": true
      },
      "onlypreview": false,
      "usertoken": ""
    },
    {
      "title": "Présentation de l&lsquo;Observatoire de l&lsquo;Open data",
      "activate": true,
      "gitfile": "https://github.com/multi-coop/gitribute-content-test/blob/main/texts/markdown/odf/ODF-observatoire-intro.md",
      "options": ""
    }
    ]'
    locale="fr"
  ></datami-multi-files>

  <!-- DATAMI WIDGET'S APP.JS SCRIPT -->
  <script src="https://datami-widget.multi.coop/js/app.js" type="text/javascript" defer></script>

  <!-- <hr> -->

</div>
