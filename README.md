This is designed to let users rate how happy they are with something using a 
smiley faced slider.

[See the Demo](http://lkorth.github.com/smiley-slider/)

Use:

```javascript
// add the slider to a div with id "slider"
var s = new SmileySlider(document.getElementById("slider"))

s.position(0) // make it sad
s.position(1) // make it happy

var p = s.position() // get it's position
s.position(p / 2) // make it half as happy

s.position(function (p) {
	// do something when it changes
})
```