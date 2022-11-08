## X-Up Cards
[link to Figma component]()

### Required templates

[section-title-link.html.twig]()

[card-md.html.twig]()

[btn-wayfinding.html.twig]()

[link-base.html.twig]()


### Required css
[btn-wayfinding.css]()

### Required js

In Drupal, add `ts_btn_wayfinding` library to theme_name.libraries.yml:
```
ts_btn_wayfinding:
  css:
    theme:
      templates/_patterns/btns/btn-wayfinding/btn-wayfinding.css: {}
