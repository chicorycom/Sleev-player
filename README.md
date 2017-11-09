# Sleev-player

_Sleev-player [Download][Download]_

[Download]: https://github.com/maluklo/Sleev-player/releases
<img src="https://raw.githubusercontent.com/maluklo/Sleev-player/master/sleev%20player.png">
### Quick Start
Includes videojs-panorama, hola_videojs_hls, videojs-resolution-switcher.
```html
<script src="sleev.js"></script>

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
