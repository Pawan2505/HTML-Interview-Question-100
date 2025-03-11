### **37. How can you create an image with a clickable hyperlink in HTML?**

To create an image with a clickable hyperlink, you wrap the `<img>` element inside an `<a>` (anchor) element. The `<a>` element will define the hyperlink, and the `<img>` element will display the image. When the image is clicked, it will take the user to the URL specified in the `href` attribute of the `<a>` tag.

**Example**:
```html
<a href="https://www.example.com">
  <img src="image.jpg" alt="Example Image">
</a>
```

In this example:
- The `<a>` element defines the hyperlink and the `href` attribute specifies the destination URL.
- The `<img>` element displays the image (`image.jpg`), and the `alt` attribute provides an alternative text for the image in case it cannot be displayed.
