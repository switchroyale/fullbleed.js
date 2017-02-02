# fullbleed.js
A script to add background videos to your site.

## Dependencies
This script requires jQuery to function.

## Examples
Website background video:

```javascript
<script>
	$(document).ready(function() {
		$('html').bodyvid({
			video: 'video.mp4',
			poster: 'poster.jpg',
			sound: 'muted' // Optional
		});
	});
</script>
```
Background video for a `div` or similar element:

```javascript
<script>
	$(document).ready(function() {
		$('html').boxvid({
			target: '.your-target-element',
			video: 'video.mp4',
			poster: 'poster.jpg',
			sound : 'muted' // Optional
		});
	});
</script>
```
