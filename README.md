CSS Slider
==========

Pure CSS, simple slider.

## Examples

Here are some examples:

- [Dark](http://rawgithub.com/drygiel/csslider/master/examples/dark.html)
- [Bright](http://rawgithub.com/drygiel/csslider/master/examples/light.html)
- [Basic](http://rawgithub.com/drygiel/csslider/master/examples/basic.html)


## Installation

- Include the CSS stylesheet at the end of `<head>` element:

	```html
	<link rel="stylesheet" href="/path/to/csslider.css" />
	```            
- Put code into webpage:
	
	```html
<div class="csslider">
    <input type="radio" name="slides" id="slides_0" checked />
    <input type="radio" name="slides" id="slides_1" />
    <input type="radio" name="slides" id="slides_2" />
    <input type="radio" name="slides" id="slides_3" />
    <input type="radio" name="slides" id="slides_4" />
    <ul>
        <li><h1>Most basic config</h1>Slide 1</li>
        <li>Slide 2</li>
        <li>Slide 3</li>
        <li>Slide 4</li>
        <li>Slide 5</li>
    </ul>
    <div class="arrows">
        <label for="slides_0"></label>
        <label for="slides_1"></label>
        <label for="slides_2"></label>
        <label for="slides_3"></label>
        <label for="slides_4"></label>
    </div>
    <div class="navigation">
        <label for="slides_0"></label>
        <label for="slides_1"></label>
        <label for="slides_2"></label>
        <label for="slides_3"></label>
        <label for="slides_4"></label>
    </div>
</div>
	```

