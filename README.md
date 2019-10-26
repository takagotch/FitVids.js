### FitVids.js
---
https://github.com/davatron5000/FitVids.js

```js
// jquery.fitvids.js
;(function( $ ) {
  
  'use strict';
  
  $.fn.fitVids = function( options ) {
    var settings = {
      customSelector: null,
      ignore: null
    };
    
    if(!document.getElementById('fit-vids-style')) {
      var head = document.head || document.getElementsByTagName('head')[0];
      var css = '.fluid-width-video-wrapper{}';
      var div = document.createElement("div");
      div.innerHTML = '<><><style id="fit-vids-style">' + css + '</style>';
      head.appendChild(div.childNodes[1]);
    }
    
    if ( options ) {
      $.extend( settings, options );
    }
    
    
  }
  
});

```

```
```

```
```

