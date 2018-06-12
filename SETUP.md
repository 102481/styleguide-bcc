# Set up

Brisbane City Council uses the Sass preprocessor [Compass](http://compass-style.org/) to compile `.scss` files into CSS. Before attempting to use the classes or mixins defined in this style guide, download [bcc-sass-framework.zip](/asssets/bcc-sass-framework.zip) and include it in your project.

## Example usage

Extract the framework into your project:

```
src/scss
└── vendor
    └── bcc-sass-framework
        ├── fonts
        |   ├── OpenSans
        |   └── ProximaNova
        ├── components
        |   └── _promo-panel.scss
        ├── _fonts.scss
        ├── _mixins.scss
        ├── _variables.scss
        └── init.scss
```

Then, import `init.scss` into your root `.scss` file:

{% codetabs name="SCSS", type="scss" -%}
@import 'vendor/bcc-sass-framework/init';
{%- endcodetabs %}
