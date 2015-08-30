# color-wheel-picker
Javascript plugin to create a color picker through a wheel and specific colors

### Simple usage:


```html
<script src="path-to/color-wheel-picker.js"></script>


<div id="container-canvas">
    <canvas id="canvas"></canvas>
    <div id="center-canvas"></div>
</div>

<input id="value-canvas">
        
```

```javascript

window.onload = createColorWheelPicker;

function createColorWheelPicker() {

    var wheelPicker = new colorWheelPicker(
            [
                "#FFDAB9", "#FF0000", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9",
                "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA",
                "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF",
                "#FFDAB9", "#E6E6FA", "#E0FFFF", "#FFDAB9", "#E6E6FA", "#E0FFFF",
            ], //-- Array of colors 
            "canvas", //--  Id of canvas tag
            400, //-- Width of container tag
            200, //--- Width of center tag
            "container-canvas", //--- Id of container tag
            "center-canvas", //--- Id of center circle tag
            "value-canvas" //--- Id of input tag for set selected color
    );
}

```


## Author

* [Ali Camargo](http://github.com/alicamargom)