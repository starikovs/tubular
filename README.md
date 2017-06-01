tubular
=======

Forked from https://github.com/mccambridge/tubular :)

jQuery tubular turns cat videos into website backgrounds.  It's that dangerous.

## TODO: what I'm going to change

Example: https://jsfiddle.net/ea4bk0mw/2/

- use passed element as a container (.w), not window
- position absolute for tubularContainer instead of fixed
- remove $('html,body').css({'width': '100%', 'height': '100%'}); assume that it is by default
- prepend tubularContainer to the passed container not body
- //$node.css({position: 'relative', 'z-index': options.wrapperZIndex});
- take width & height, when calc the size for the window: width = $('.w').width(), height = $('.w').height(),
- calc aspect ratio and then pass to plugin (<iframe width="560" height="315" src="h...)
