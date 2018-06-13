# Buttons

Use buttons to signal actions or points for user interaction. This framework offers a few different button styles, applied through CSS classes on HTML tags.

The HTML tags suitable for use as buttons are:
* `<button>`
* `<a>`
* `<input type="button" />`
* `<input type="submit" />`

## Default button

The default button used around Council's corporate website. To use this button, add the `bcc-button-default` class to your desired HTML tag.

<p id="buttons-example-1">
<button class="bcc-button-default">Click me!</button>
</p>

{% codetabs name="HTML", type="html" -%}
<button class="bcc-button-default">Click me!</button>
{% language name="SCSS", type="scss" -%}
.bcc-button-default {
  @extend %bcc-button-default;
}
{%- language name="CSS", type="css" -%}
.bcc-button-default {
  display: inline-block;
  -webkit-appearance: none;
  -moz-appearance: none;
  border: none;
  cursor: pointer;
  border-radius: .35em;
  padding: .5em 1em;
  background-color: #106db2;
  color: white;
}
.bcc-button-default:hover {
  background-color: #ffd200;
  color: #333333;
  text-decoration: none;
}
{%- endcodetabs %}

## Large button

This button is commonly found in Council's webforms. To use this button, add the `bcc-button-large` class to your desired HTML tag.

<p id="buttons-example-2">
<input class="bcc-button-large" type="submit" value="Submit" />
</p>

{% codetabs name="HTML", type="html" -%}
<input class="bcc-button-large" type="submit" value="Submit" />
{% language name="SCSS", type="scss" -%}
.bcc-button-large {
  @extend %bcc-button-large;
}
{%- language name="CSS", type="css" -%}
.bcc-button-large {
  display: inline-block;
  -webkit-appearance: none;
  -moz-appearance: none;
  border: none;
  cursor: pointer;
  font-size: 1.42857em;
  font-weight: bold;
  line-height: 1.155em;
  border-radius: .35em;
  padding: .5em 1em;
  background-color: #106db2;
  color: white;
}
.bcc-button-large:hover {
  background-color: #ffd200;
  color: #333333;
  text-decoration: none;
}
{%- endcodetabs %}

## Chevron button

A different style of button found in lists and some panels on the corporate site. To use this button, add the `bcc-button-chevron` class to your desired HTML tag.

<p id="buttons-example-3">
<a class="bcc-button-chevron">Click me!</a>
</p>

{% codetabs name="HTML", type="html" -%}
<a class="bcc-button-chevron">Click me!</a>
{% language name="SCSS", type="scss" -%}
.bcc-button-chevron {
  @extend %bcc-button-chevron;
}
{%- language name="CSS", type="css" -%}
.bcc-button-chevron {
  display: inline-block;
  -webkit-appearance: none;
  -moz-appearance: none;
  border: none;
  cursor: pointer;
  position: relative;
  padding: 1em;
  background-color: #efefef;
  border-bottom: 1px solid #e2e2e2;
  border-right: 3em solid #e2e2e2;
}
.bcc-button-chevron:hover {
  color: #0c5083;
  background-color: #e2e2e2;
  text-decoration: none;
}
.bcc-button-chevron:after {
  content: '';
  position: absolute;
  top: calc(50% - .375em);
  right: -1.7em;
  width: .75em;
  height: .75em;
  margin: -1px;
  transform: rotate(45deg);
  border: 2px solid #0c5083;
  border-bottom: none;
  border-left: none;
}
{%- endcodetabs %}
