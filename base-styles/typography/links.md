## Links

### Styles

Links lead users to a different page or further information. For Brisbane City Council digital standards, links should be styled as follows:

* Links are the standard Council blue
* Hovered and active links are underlined and a darker blue

This is <a id="link-example" href="#">a link</a> in its default state.

{% codetabs name="HTML", type="html" -%}
<p>This is <a href="#">a link</a> in its default state.</p>
{% language name="SCSS", type="scss" -%}
a {
  &, &:visited {
    color: $link-color;
    text-decoration: none;
  }
  &:hover {
    color: $link-color-active;
    text-decoration: underline;
  }
}
{%- language name="CSS", type="css" -%}
a, a:visited {
  color: #106db2;
  text-decoration: none;
}
a:hover {
  color: #0c5083;
  text-decoration: underline;
}
{%- endcodetabs %}

---

### Attributes

**`target`**

To align with our digital standards, any links to internal Brisbane City Council content should open in the same window (active window). However, a link to external content should open in a new window or tab.

In order to open a link in a new window or tab, simply add `target="_blank"` inside the `<a>` tag:

{% codetabs name="HTML", type="html" -%}
<a href="#" target="_blank">Open in new window or tab</a>
{%- endcodetabs %}
