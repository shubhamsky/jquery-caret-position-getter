Usage
=====

```js
var pos = $('textarea').getCaretPosition();

// now you can use left, top(they are relative position)

$my_tip.css({
	left: this.offsetLeft + pos.left,
	top: this.offsetTop + pos.top
});
```
