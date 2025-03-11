**52. How can you play audio and video files using HTML5?**

You can play audio and video files using the `<audio>` and `<video>` elements in HTML5. These elements allow you to embed media content directly into the webpage, and they support optional controls such as play, pause, and volume control.

### Example (Audio):
To play an audio file, use the `<audio>` element, specifying the source file with the `src` attribute. You can also add the `controls` attribute to display the default media controls (like play, pause, and volume).

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```

### Example (Video):
Similarly, to play a video file, use the `<video>` element. You can add the `controls` attribute for video controls such as play, pause, and volume adjustment.

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

### Key Points:
- **`<audio>`**: Used for playing audio files (e.g., MP3, Ogg).
- **`<video>`**: Used for playing video files (e.g., MP4, WebM, Ogg).
- Both elements have a `controls` attribute to provide the default player interface.
- If the browser doesn't support these elements, the fallback text inside the tags will be displayed.

These HTML5 elements offer a simple and effective way to embed multimedia content directly within web pages without relying on third-party plugins.
