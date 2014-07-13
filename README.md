# jQuery Flickr Photoset

jQuery plugin for generating photoset gallery using [Bootstrap](http://getbootstrap.com) and [Bootstrap Image Gallery](https://github.com/blueimp/Bootstrap-Image-Gallery).

I know, I know, too many depencencies, but somebody might find it useful.

## Example

[https://cdn.rawgit.com/hadalin/jquery-flickr-photoset/55c6594f3fb2b11d0ca826760a54baacd76a365a/index.html](https://cdn.rawgit.com/hadalin/jquery-flickr-photoset/55c6594f3fb2b11d0ca826760a54baacd76a365a/index.html)

## Dependencies

- [jQuery](http://jquery.com)
- [Bootstrap](http://getbootstrap.com)
- [imagesLoaded](https://github.com/desandro/imagesloaded)
- [Gallery](https://github.com/blueimp/Gallery)
- [Bootstrap-Image-Gallery](https://github.com/blueimp/Bootstrap-Image-Gallery)

## Instructions

Add dependencies, include gallery thumbnails and blueimp gallery snippets and call flickr plugin (see `index.html`):
```
<script type="text/javascript">
$(function() {
    $('.gallery').flickr({
        apiKey: '60ac8913e80833ef7as73138g9cddjdk',
        photosetId: '74157336137235911'
    });
});
</script>
```
