## Lists

Lists organise written information for users and are the preferred way to display items one after the other, instead of using &lt;br&gt; tags. 

### Unordered Lists

An unordered list starts with the &lt;ul&gt; tag. Each list item starts with the &lt;li&gt; tag. The list items will be marked with bullets by default.

```
<ul>
  <li>List item</li>
  <li>List item</li>
  <li>List item</li>
</ul>
```

**Website example**

![](/assets/lists-unordered.PNG)

### Ordered Lists {#ordered}

This list is used to create and indexed list, such as a numbered or alphabetical list. The list items will be marked with numbers by default.

```
<ol>
  <li>List item</li>
  <li>List item</li>
  <li>List item</li>
</ol>
```

**Website example**

![](/assets/lists-ordered.PNG)

### Other ordered list types

The **type **attribute of the &lt;ol&gt; tag, defines the type of the list item marker:

| Type | Description |
| :--- | :--- |
| type="1" | The list items will be numbered with numbers \(default\) |
| type="A" | The list items will be numbered with uppercase letters |
| type="a" | The list items will be numbered with lowercase letters |
| type="I" | The list items will be numbered with uppercase roman numbers |
| type="i" | The list items will be numbered with lowercase roman numbers |



