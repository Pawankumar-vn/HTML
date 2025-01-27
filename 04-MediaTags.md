```html
<!-- Media Tags in HTML -->

<!-- Image -->
<img src="image.jpg" alt="Description of image" width="500" height="300" />
<!-- 'src': image source, 'alt': alternative text, 'width'/'height': dimensions -->

<!-- Video -->
<video width="640" height="360" controls>
  <source src="video.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
<!-- 'controls': play/pause buttons, 'source': video file and format -->

<!-- Audio -->
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
  Your browser does not support the audio element.
</audio>
<!-- 'controls': play/pause buttons, 'source': audio file and format -->

<!-- Media Attributes -->
<!-- 'src', 'width', 'height', 'alt', 'muted', 'loop', 'autoplay', 'controls', 'media' -->

<!-- Audio Example with Attributes -->
<audio src="audio.mp3" controls muted loop autoplay>
  Your browser does not support the audio element.
</audio>
<!-- 'muted': starts muted, 'loop': repeats, 'autoplay': plays on load -->

<!-- Video Example with Attributes -->
<video src="video.mp4" width="640" height="360" controls autoplay loop muted>
  Your browser does not support the video tag.
</video>

<!-- Responsive Design Using Media Query -->
<link
  rel="stylesheet"
  href="styles.css"
  media="screen and (max-width: 600px)" />
<!-- 'media': applies CSS when screen width ≤ 600px -->

<!-- Multiple Source Elements for Compatibility -->
<audio controls>
  <source src="audio.mp3" type="audio/mp3" />
  <source src="audio.ogg" type="audio/ogg" />
  Your browser does not support the audio element.
</audio>

<video width="640" height="360" controls>
  <source src="video.mp4" type="video/mp4" />
  <source src="video.webm" type="video/webm" />
  <source src="video.ogg" type="video/ogg" />
  Your browser does not support the video tag.
</video>

<!-- Iframe Example -->
<iframe
  src="https://www.example.com"
  width="600"
  height="400"
  frameborder="0"
  allowfullscreen>
  Fallback content if iframe fails.
</iframe>
<!-- 'src': URL, 'width'/'height': dimensions, 'frameborder': no border, 'allowfullscreen': fullscreen support -->
```
