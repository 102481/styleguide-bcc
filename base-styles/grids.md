## Grids

The Drupal theme for our corporate site includes the [Zen Grids](http://zengrids.com/) plugin for Compass. This plugin allows any number of columns to be added to a HTML element, and for content to be placed arbitrarily within these columns.

<div id="grid-example">
  <h4 class="grid-example-header">Header<br />zen-grid-item(8, 1);</h4>
  <p class="grid-example-box-a">Box A<br />zen-grid-item(2, 1);</p>
  <p class="grid-example-box-b">Box B<br />zen-grid-item(5, 4);</p>
  <p class="grid-example-box-c">Box C<br />zen-grid-item(6, 2);</p>
</div>

{% codetabs name="HTML", type="html" -%}
<div id="grid-example">
  <h4 class="grid-example-header">Header<br />zen-grid-item(8, 1);</h4>
  <p class="grid-example-box-a">Box A<br />zen-grid-item(2, 1);</p>
  <p class="grid-example-box-b">Box B<br />zen-grid-item(5, 4);</p>
  <p class="grid-example-box-c">Box C<br />zen-grid-item(6, 2);</p>
</div>
{% language name="SCSS", type="scss" -%}
$zen-columns: 8;                  // Defines how many columns should exist.
$zen-gutters: 1em;                // Sets the gutter between columns.

#grid-example {
  @include zen-grid-container();  // Designates this element as a Zen Grid.

  .grid-example-header {
    @include zen-grid-item(8, 1); // Span 8 columns, starting in column 1.
  }
  .grid-example-box-a {
    @include zen-new-row();       // Start a new grid row.
    @include zen-grid-item(2, 1); // Span 2 columns, starting in column 1.
  }
  .grid-example-box-b {
    @include zen-grid-item(5, 4); // Span 5 columns, starting in column 4.
  }
  .grid-example-box-c {
    @include zen-new-row();       // Start a new grid row.
    @include zen-grid-item(6, 2); // Span 6 columns, starting in column 2.
  }
}
{%- endcodetabs %}
