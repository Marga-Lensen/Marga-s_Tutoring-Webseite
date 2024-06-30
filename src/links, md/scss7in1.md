# Sass & parcel

- Install sass

  ```bash
  npm i sass --save-dev
  ```

- install parcel

  ```bash
  npm i parcel-bundler --save-dev
  ```

- Ändere dein Script in `package.json`
  ```bash
  "start": "parcel src/index.html",
  "build": "parcel build src/index.html"
  ```

**Strukturen für Projekt**  
Es gibt verschiedenen Methoden, wie man die Ornder für ein Projelt anlegen soll. Die drei bekannteste Methoden sind:

1. SMACSS

   - Base:
   - Moduls:
   - Layout:
   - Themen:

2. ITCSS

   - Settings
   - Tools
   - Generic
   - Elements
   - Objects
   - Components
   - Utilities

3. 7in1

- Struktur **_7in1_**

  ```bash
    src/
  |
  |– abstracts/
  |   |– _variables.scss    # Sass Variablen
  |   |– _functions.scss    # Sass Funktionen
  |   |– _mixins.scss       # Sass Mixins
  |   |– _placeholders.scss # Sass Platzhalter
  |
  |– base/
  |   |– _reset.scss        # Reset/normalize
  |   |– _typography.scss   # Regeln für Typographie
  |   …                     # Etc.
  |
  |– components/
  |   |– _buttons.scss      # Buttons
  |   |– _carousel.scss     # Carousel
  |   |– _cover.scss        # Cover
  |   |– _dropdown.scss     # Dropdown
  |   …                     # Etc.
  |
  |– layout/
  |   |– _navigation.scss   # Navigation
  |   |– _grid.scss         # Grid system
  |   |– _header.scss       # Header
  |   |– _footer.scss       # Footer
  |   |– _sidebar.scss      # Sidebar
  |   |– _forms.scss        # Forms
  |   …                     # Etc.
  |
  |– pages/
  |   |– _home.scss         # Home spezifische Styles
  |   |– _contact.scss      # Contact spezifische styles
  |   …                     # Etc.
  |
  |– themes/
  |   |– _theme.scss        # Default-Theme
  |   |– _admin.scss        # Admin-Theme
  |   …                     # Etc.
  |
  |– vendors/
  |   |– _bootstrap.scss    # Bootstrap
  |   |– _jquery-ui.scss    # jQuery UI
  |   …                     # Etc.
  |
  |
  `– main.scss              # Haupt Sass-Datei
  ```

  **Weitere führende Links**

  👉 [Sass with auto-refresh (and more) made easy](https://www.youtube.com/watch?v=wYWf2m_yzBQ&t=263s)\
  👉 [Get your stylesheets more organized with Sass partials](https://www.youtube.com/watch?v=9Ld-aOKsEDk)\
  👉 [Sass-Guide](https://sass-guidelin.es/de/)\
  👉 [Regel für Projekt nach ](https://gist.github.com/rveitch/84cea9650092119527bc)
