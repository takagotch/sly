### sly
---
https://github.com/darsain/sly

```js
var options = {
  horizontal: 1,
  itemNav: 'basic',
  speed: 300,
  mouseDragging: 1,
  touchDragging: 1
};
var frame = new Sly('#frame', options).init();

var options = {
  horizontal: 1,
  itemNav: 'basic',
  speed: 300,
  mouseDragging: 1,
  touchDragging: 1
};
$('#frame').sly(options);
```

```js
var sly = new Sly( frame, options [, callbackMap ] );

sly.init();

var sly = new Sly(frame, options, callbackMap).init();

sly.activate(1);
sly.reload();

$(window).resize(function(e) {
  $frame.sly('reload');
});

var sly = new Sly('#frame');
var sly = new Sly(document.getElementById('frame'));
var sly = new Sly(jQuery('#frame'));

var sly = new Sly(frame, options, {
  load: function () {},
  move: [
    function () {},
    function () {}
  ]
});

$('#frame').sly( [ options [, callbackMap ] ] );

$('#frame').sly(options, {
  load: function () {},
  move: [
    function () {},
    function () {}
  ]
});
```

```
```

