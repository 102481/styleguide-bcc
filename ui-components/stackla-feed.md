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



