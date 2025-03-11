In HTML, comments that are visible on the web page are not directly supported by the standard HTML comment syntax (`<!-- -->`), which hides comments from the browser. However, if you want to display text as a comment **visibly** on the web page, you would need to use an HTML element, such as a `<p>`, `<div>`, or any other element, to contain the comment text.

Here is how you can achieve that:

### **Example:**
```html
<!-- This is a standard HTML comment (not visible on the web page) -->

<p>This is a visible "comment" on the web page.</p>
```

To make a "comment" visible on the page, you would display the text as content within an element like `<p>`, but the text would not technically be a "comment" in the standard sense. HTML comments (`<!-- -->`) are not visible to the user on the page, but they can be useful for developers.

If you wish to show actual comments in a more prominent way, you would use elements such as `<div>` or `<span>`. 

### **Example of visible comment:**
```html
<!-- This is a visible comment -->
<div style="border: 1px dashed gray; padding: 10px;">This is a visible comment displayed on the webpage.</div>
```

This would display the text **"This is a visible comment displayed on the webpage"** inside a dashed box.
