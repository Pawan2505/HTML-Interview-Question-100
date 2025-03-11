### **40. What is the purpose of the `<fieldset>` and `<legend>` elements in HTML?**

The `<fieldset>` element is used to group related form elements together within a form, making the form more organized and accessible. The `<legend>` element provides a title or caption for the group of elements inside the `<fieldset>`, helping to clarify the purpose of the grouped form elements.

**Example:**
```html
<fieldset>
  <legend>Contact Information</legend>
  <label for="name">Name:</label>
  <input type="text" id="name">
  <!-- Other form elements -->
</fieldset>
```

In this example:
- The `<fieldset>` element groups the form elements related to "Contact Information."
- The `<legend>` element provides a clear title or label for the group, improving accessibility and usability for the users.
