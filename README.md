# Liquid video

Super easy script to make your `iframe` or `embed` responsive / liquid. To use it grab a copy of minified file and instantiate a new LiqudVideo object passing your query as an argument. It doesn't require any other dependencies like jQuery and it super lightweight - only 417 Bytes minified and around 998 Bytes unminified.

## Manually inject to source code of your project

```html
<script src="js/liquid-video.min.js"></script>
<script>
var lv = new LiquidVideo(document.querySelectorAll('.post iframe'));
</script>
```

## Use with npm

```bash
npm i -S liquid-video
```

```bash
npm install --save liquid-video
```

```js
var LiquidVideo = require('liquid-video');
var lv = new LiquidVideo(document.querySelectorAll('.post iframe'));
```
## Demo

[Example on Codepen](http://codepen.io/pawelgrzybek/pen/vGxqaq)
