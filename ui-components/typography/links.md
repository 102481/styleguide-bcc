## Links

### Styles

Links lead users to a different page or further information.

This is [a link](javascript:void%280%29;) in its default state.

```html
<p>This is <a href="#">a link</a>in its default state</p>
```

For Brisbane City Council digital standards, links should be styled as follows:

* An unvisited link is blue
* A visited link is underlined and a darker blue 
* An active link is underlined and a darker blue 

**&lt;/&gt; Source**

```html
<a href="#" target="_blank">Add text to link here</a>
```

```css
a:link {
color: #106db2;
text-decoration: none;
}

a:hover {
color: #0c5083;
text-decoration: underline;
}

a:active {
color: #0c5083;
text-decoration: underline;
}
```

---

### Target Attributes

A target to use for internal and external links and for image area links.

To align with our digital standards, any links to internal Brisbane City Council content should open in the same window \(active window\). However, a link to external content should open in a new window or tab.

In order to open a link in a new window / tab, simply add `target="_blank"` inside the `<a>` tag:

```html
<a href="#" target="_blank">Open in new window or tab</a>
```



