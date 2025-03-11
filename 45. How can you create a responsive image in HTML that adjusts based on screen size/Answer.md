**45. How can you create a responsive image in HTML that adjusts based on screen size?**

To create a responsive image that adjusts its size based on the screen width, you can use the `<img>` element and set its `width` to `100%` in CSS. This ensures the image will scale relative to its parent container, maintaining its aspect ratio while adjusting to different screen sizes.

### **Example:**
```html
<style>
  img {
    width: 100%;
    height: auto;
  }
</style>

<img src="image.jpg" alt="Responsive Image">
```

In this example, the CSS rules applied to the `<img>` element ensure that:

- The `width: 100%` makes the image stretch to fill the width of its container.
- The `height: auto` ensures the image maintains its aspect ratio (i.e., its height adjusts automatically in proportion to its width).

This makes the image responsive, so it adapts smoothly to different screen sizes, whether viewed on a desktop, tablet, or mobile device.
