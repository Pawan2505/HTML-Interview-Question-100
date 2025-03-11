### **9. How can you include CSS styles in an HTML document?**

You can include CSS styles in an HTML document in two main ways:

1. **External CSS**: Use the `<link>` element in the `<head>` section to link to an external CSS file.
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

2. **Internal CSS**: Use the `<style>` element within the `<head>` section to define CSS styles directly in the HTML document.
   ```html
   <style>
     body {
       background-color: lightblue;
     }
   </style>
   ```

**Example**:
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- External CSS -->
    <link rel="stylesheet" href="styles.css">

    <!-- Internal CSS -->
    <style>
      h1 {
        color: green;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
  </body>
</html>
```

Both methods allow you to style HTML elements, with external CSS being more scalable for larger projects.