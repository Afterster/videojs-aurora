# Video.js Aurora

Video.js Aurora.js Tech plug-in

A Video.js tech plugin that add [Aurora.js](https://github.com/audiocogs/aurora.js) to decode WAV, OGG (Opus/Vorbis), MP3, M4A, AAC and FLAC media files in JavaScript.

## Getting Started

Once you've added the plugin script to your page, you can use it with any supported media:
 * Include JavaScript files
```html
<!-- Always include aurora.js (wav decoder by default) -->
<script src="aurora.js"></script>
<!-- Include flac.js for FLAC decoder -->
<script src="flac.js"></script>
<!-- Include mp3.js for MP3 decoder -->
<!--<script src="mp3.js"></script>-->
<!-- Include alac.js for M4A decoder -->
<!--<script src="alac.js"></script>-->
<!-- Include aac.js for AAC decoder -->
<!--<script src="aac.js"></script>-->
<!-- Include ogg.js, vorbis.js, opus.js for OGG Vorbis/Opus decoders -->
<!--<script src="ogg.js"></script>-->
<!--<script src="vorbis.js"></script>-->
<!--<script src="opus.js"></script>-->

<script src="video.js"></script>
<script src="videojs-aurora.js"></script>
```
 * And add this new tech to the player:
```html
data-setup='{ "techOrder": ["aurora"] }'
```

There's also a [working example](example.html) of the plugin you can check out if you're having trouble.

## Documentation
### Plugin Options

This plugin doesn't have any option.

## Release History

 - 0.1.0: Initial release
