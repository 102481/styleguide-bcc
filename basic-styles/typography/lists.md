## Lists

Lists organise written information for users and are the preferred way to display items one after the other, instead of using `<br />` tags.

### Unordered Lists

An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.  
The list items will be marked with bullets by default.

{% codetabs name="HTML", type="html" -%}
<ul>
  <li>list item</li>
  <li>list item</li>
  ...
</ul>
{%- endcodetabs %}

**Website example**

![](/assets/lists-unordered.PNG)

### Ordered Lists {#ordered}

Use lists ordered by numbers or letters for instructions, to indicate priority or chronology, or for where items need to be identified for later reference. The list items will be marked with numbers by default.

{% codetabs name="HTML", type="html" -%}
<ol>
  <li>List item</li>
  <li>List item</li>
  ...
</ol>
{%- endcodetabs %}

**Website example**

![](/assets/lists-ordered.PNG)
