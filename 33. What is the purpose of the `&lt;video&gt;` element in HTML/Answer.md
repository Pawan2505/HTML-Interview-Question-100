### **33. What is the purpose of the `<video>` element in HTML?**

The `<video>` element is used to embed video content on a web page. It provides an easy way to display videos directly within the page, and it allows you to specify video sources in different formats. It also provides built-in controls for video playback, such as play, pause, volume control, and fullscreen.

**Example**:
```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

In this example:
- The `controls` attribute adds the video playback controls.
- The `<source>` element specifies the video file (`video.mp4`) and its format (`video/mp4`).
- The text "Your browser does not support the video tag" will be displayed if the browser does not support the `<video>` element.
