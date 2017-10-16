# Sleev-player
Video.js 6.3.3
### Quick Start

```html
<script src="dist/sleev.js"></script>

<video id="play" class="sleev" ></video>

<script>
var Player = videojs('play',{ 
    "controls": true, 
    "autoplay": false, 
    "preload": "auto" ,
    "poster": "http://vjs.zencdn.net/v/oceans.png",
    "width": 960,
    "height": 400,
     sources: [
{ src: 'https://vjs.zencdn.net/v/oceans.mp4', type: 'video/mp4'},
{ src: 'https://vjs.zencdn.net/v/oceans.webm', type: 'video/webm'},
{ src: 'https://vjs.zencdn.net/v/oceans.ogg', type: 'video/ogg'},
],})
</script>

```
