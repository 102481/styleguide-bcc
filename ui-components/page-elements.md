# Page elements

## Promotional panel

This section displays items of the Promotion content type that are flagged as 'Promoted to front page'.

**Drupal how to**

1. Create your promotions in Content &gt; Add Content &gt; Promotions first.
2. In the Content tab press the + button on the right. Select Promotion pane. 
3. Title: the text will go above the promos.
4. References: add four entries. Enter the names of the promos you created for this page. If you don't know which ones you want to use, you can come back and add them later. There should always be 4 or, with permission from your team leader or higher, a number that is divisible by 4 \(8, 12, etc.\)
5. View mode: Full \(default\)
6. Select Finish

**Example **![](/assets/elements_promo panels.png)**&lt;/&gt; Source**

```html
<div class="panel-pane pane-fieldable-panels-pane pane-current-2086 pane-bundle-promotion-pane">

  <div class="pane-inner">
          <h2 class="pane-title">Quick links</h2>
        <div class="field field-name-field-promotion-references field-type-entityreference field-label-hidden">
  <div class="
  grid-container
  grid-count-4        grid-count-multiple    ">
          <div class="grid-item">
```

---

## Stackla 

Stackla aggregates social media feeds and displays them on a number of pages on the corporate website.

**Drupal how to**

1. Create new content or edit existing content
2. Click 'Disable rich text' to show HTML
3. Paste the embed code in the HTML view
4. Enable rich text to continue editing
5. Save page
6. Refresh the page to view the gallery or module

**Example **

![](/assets/elements_Stackla.png)

**&lt;/&gt; Source**

```html
<div class="pane-inner">
          <h2 class="pane-title">Right now in Brisbane</h2>
        <div class="stacklafw" data-id="10853" data-hash="579fefaeaa29f" data-ct="" data-alias="social.brisbane.qld.gov.au" data-ttl="30" data-uid="1" style="transition: height 1s; height: 2088px;"><iframe src="https://widget.stackla.com/widget/show/?wid=579fefaeaa29f&amp;ct=&amp;domain=social.brisbane.qld.gov.au&amp;ttl=30&amp;unique_id=1" frameborder="0" id="stack-widget-embed-10853" scrolling="no" width="100%" allowtransparency="true" style="visibility: visible; transition: height 0.5s;" height="2088" title="CorpWeb homepage"></iframe></div>
  </div>
```



