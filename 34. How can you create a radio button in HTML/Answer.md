### **34. How can you create a radio button in HTML?**

To create a radio button in HTML, use the `<input>` element with the `type="radio"` attribute. You should also use the `name` attribute to group related radio buttons together, ensuring that only one radio button in the group can be selected at a time.

**Example**:
```html
<input type="radio" name="gender" value="male" id="male">
<label for="male">Male</label>

<input type="radio" name="gender" value="female" id="female">
<label for="female">Female</label>
```

In this example:
- The `name="gender"` groups both the radio buttons together. This ensures that only one option can be selected at a time.
- The `value="male"` and `value="female"` represent the values submitted when each radio button is selected.
- The `id` attribute allows for labeling the buttons and helps with associating the `<label>` with the respective radio button.
