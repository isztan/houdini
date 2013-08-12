# Houdini
Houdini is a lightweight and progressively enhanced expand-and-collapse widget.


## How to use Houdini

### 1. Include Houdini on your site.

    <link rel="stylesheet" href="houdini.css">
    <script src="houdini.js"></script>

### 2. Add the markup to your HTML.

    <div class="collapse" id="show-me">
        <p>Now you see me, now you don't.</p>
    </div>

    <a class="collapse-toggle" data-target="#show-me" href="#">
        <span class="collapse-text-show">Show +</span>
        <span class="collapse-text-hide">Hide -</span>
    </a>

If you'd prefer to show content by default, include the .active class along with the .collapse and .collapse-toggle classes.

    <button class="collapse-toggle active" data-target="#hide-me">
        <span class="collapse-text-show">Show</span>
        <span class="collapse-text-hide">Hide</span>
    </button>

    <div class="collapse active" id="hide-me">
        <p>Hide me!</p>
    </div>

### 3. Pat yourself on the back.

Seriously, you're done. Nice work! Modify as needed.


## Browser Support

Houdini works in all modern browsers, and IE 8 and above.

## Changelog
* v2.2 (August 5, 2013)
  * Added variable for `$(this)` (better for performance).
* v2.1 (June 24,2013)
  * Added alternating "show/hide" text to toggle buttons.
* v2.0 (June 7, 2013)
  * Switched to MIT license.
* v2.0 (June 3, 2013)
  * Removed `href` as element selector. Just `data-target` supported now.
* v1.2 (February 13, 2013)
  * Renamed `example.html` to `index.html`.
  * Removed "Convert to Vanilla JS" from the roadmap.
* v1.1 (February 5, 2013)
  * Switched to relative sizing.
* v1.0 (January 24, 2013)
  * Initial release.

## License
Houdini is free to use under the [MIT License](http://gomakethings.com/mit/).
