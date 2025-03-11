### **15. What is the purpose of the `<form>` element in HTML?**

The **`<form>`** element is used to create a **form** on a web page, allowing users to input data and submit it to a server for processing. Within the form, you can use various form elements like:

- **`<input>`**: To collect different types of user input (e.g., text, password, etc.).
- **`<select>`**: To create a dropdown list.
- **`<textarea>`**: To collect multi-line text input.

**Example**:
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  
  <input type="submit" value="Submit">
</form>
```

This form collects user data and submits it to the server when the "Submit" button is clicked.
