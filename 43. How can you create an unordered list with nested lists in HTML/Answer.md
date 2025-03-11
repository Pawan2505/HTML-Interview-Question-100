**43. How can you create an unordered list with nested lists in HTML?**

To create an unordered list with nested lists, include additional `<ul>` (unordered list) and `<li>` (list item) elements within existing list items. This allows you to create a hierarchy of list items, with some list items containing sub-lists.

### **Example:**
```html
<ul>
  <li>Item 1</li>
  <li>Item 2
    <ul>
      <li>Subitem 1</li>
      <li>Subitem 2</li>
    </ul>
  </li>
  <li>Item 3</li>
</ul>
```

In this example, `Item 2` has a nested unordered list containing two subitems, `Subitem 1` and `Subitem 2`. This demonstrates how to organize content hierarchically using nested lists in HTML.
