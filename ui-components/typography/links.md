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
<!DOCTYPE html>
<html>
<head>
<style>
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
</style>

</head>
<body>

<a href="#" target="_blank">Add text to link here </a> 

</body>
</html>
```

---

### Target Attributes

A target to use for internal and external links and for image area links. 

By default, links to internal Brisbane City Council content should open in the same window \(active window\). However, a link to external content \(a non-BCC website\) should open in a new window. 









