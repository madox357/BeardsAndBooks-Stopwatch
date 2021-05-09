# BeardsAndBooks-Stopwatch
This is a stopwatch made by the non profit "Beards and Books"

This is the required HTML to be added to the header:
```html
<link rel="preload" href="https://github.com/VyeFox/BeardsAndBooks-Stopwatch/edit/main/style.js" as="style">
<link rel="preload" href="https://github.com/VyeFox/BeardsAndBooks-Stopwatch/edit/main/script.js" as="script">
```

This is the stopwatch HTML:
```html
<div class='timer'>
  <style src="https://github.com/VyeFox/BeardsAndBooks-Stopwatch/edit/main/style.js"/>
  <div class="stopwatch">
    <div class='timertitle'><div class="gold">Beards and Books</div> STOPWATCH</div>
    <div class="circle">
      <span class="time" id="display">00:00:00</span>
    </div>

    <div class="controls">
      <button class="timer_button">
        <img id="playButton" src="https://res.cloudinary.com/https-tinloof-com/image/upload/v1593360448/blog/time-in-js/play-button_opkxmt.svg" />

        <img id="pauseButton" src="https://res.cloudinary.com/https-tinloof-com/image/upload/v1593360448/blog/time-in-js/pause-button_pinhpy.svg" />
      </button>

      <button class="timer_button">
        <img id="resetButton" src="https://res.cloudinary.com/https-tinloof-com/image/upload/v1593360448/blog/time-in-js/reset-button_mdv6wf.svg" />
      </button>
    </div>
  </div>
  <script type="text/javascript" src="https://github.com/VyeFox/BeardsAndBooks-Stopwatch/edit/main/script.js"/>
</div>
```
