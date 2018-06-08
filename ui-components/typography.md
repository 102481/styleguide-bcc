# Typography

Consistent typefaces \(fonts\) used across Council's digital channels is part of our unique visual identity. Any inconsistency could undermine our brand.

---

## Typefaces \(Fonts\)

PC/desktop typefaces \(fonts\) have been created and optimised specifically for use on websites, using CSS.

### Proxima Nova \(headings\)

This font is used for headings/titles.

<p id="proxima-nova-example">Proxima Nova AaBbCcDdEeFfGgHhIiJjKkLl</p>

This font has two weights available, and uses the following code:

{% codetabs name="SASS", type="scss" -%}
font-family: $proxima-nova;
font-weight: normal / $semibold;
{%- language name="CSS", type="css" -%}
font-family: ProximaNova, Arial, sans-serif;
font-weight: normal / 600;
{%- endcodetabs %}

### Open Sans \(body\)

This font is used for body copy/paragraphs.

<p id="open-sans-example">Open Sans AaBbCcDdEeFfGgHhIiJjKkLl</p>

This font has four weights available, and uses the following code:

{% codetabs name="SASS", type="scss" -%}
font-family: $open-sans;
font-weight: normal / $semibold / bold / $extrabold;
{%- language name="CSS", type="css" -%}
font-family: OpenSans, Arial, sans-serif;
font-weight: normal / 600 / bold / 900;
{%- endcodetabs %}

---

## Font Sizes

To help users gain a sense of Brisbane City Council's content at a glance we have set formatting options.

# Heading 1 example

{% codetabs name="HTML", type="html" -%}
<h1>Heading 1 example</h1>
{% language name="SASS", type="scss" -%}
h1 {
  font-family: $proxima-nova;
  font-weight: normal;
  font-size: $h1-font-size;
  line-height: 1.5em;
  color: $blue;
}
{%- language name="CSS", type="css" -%}
h1 {
  font-family: ProximaNova, Arial, sans-serif;
  font-weight: normal;
  font-size: 2.2rem;
  line-height: 1.5em;
  color: #106db2;
}
{%- endcodetabs %}

_Tip: There should only be one H1 heading per page._

## Heading 2 example

{% codetabs name="HTML", type="html" -%}
<h1>Heading 2 example</h1>
{% language name="SASS", type="scss" -%}
h2 {
  font-family: $proxima-nova;
  font-weight: normal;
  font-size: $h2-font-size;
  line-height: 1.5em;
  color: $blue;
}
{%- language name="CSS", type="css" -%}
h2 {
  font-family: ProximaNova, Arial, sans-serif;
  font-weight: normal;
  font-size: 1.87rem;
  line-height: 1.5em;
  color: #106db2;
}
{%- endcodetabs %}

_Tip: Use subheadings \(H2 and H3 etc.\) to break up the text and explain what each section of information is about._

### Heading 3 example

{% codetabs name="HTML", type="html" -%}
<h1>Heading 3 example</h1>
{% language name="SASS", type="scss" -%}
h3 {
  font-family: $proxima-nova;
  font-weight: normal;
  font-size: $h3-font-size;
  line-height: 1.5em;
  color: $blue;
}
{%- language name="CSS", type="css" -%}
h3 {
  font-family: ProximaNova, Arial, sans-serif;
  font-weight: normal;
  font-size: 1.54rem;
  line-height: 1.5em;
  color: #106db2;
}
{%- endcodetabs %}

#### Heading 4 example

{% codetabs name="HTML", type="html" -%}
<h1>Heading 4 example</h1>
{% language name="SASS", type="scss" -%}
h4 {
  font-family: $proxima-nova;
  font-weight: normal;
  font-size: $h4-font-size;
  line-height: 1.5em;
  color: $blue;
}
{%- language name="CSS", type="css" -%}
h4 {
  font-family: ProximaNova, Arial, sans-serif;
  font-weight: normal;
  font-size: 1.43rem;
  line-height: 1.5em;
  color: #106db2;
}
{%- endcodetabs %}

Body copy \(paragraph\) example

{% codetabs name="HTML", type="html" -%}
<h1>Body copy (paragraph) example</h1>
{% language name="SASS", type="scss" -%}
p {
  font-family: $open-sans;
  font-weight: normal;
  font-size: $base-font-size;
  line-height: $base-line-height;
  color: $body-text;
}
{%- language name="CSS", type="css" -%}
p {
  font-family: OpenSans, Arial, sans-serif;
  font-weight: normal;
  font-size: 14px;
  line-height: 22px;
  color: #333;
}
{%- endcodetabs %}

_Tip: To make long sections of text easier to read, divide the content into logical paragraphs._
