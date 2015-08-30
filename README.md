# color-wheel-picker
Javascript plugin to create a color picker through a wheel and specific colors

### Simple usage:

```html
<script src="path-to/color-wheel-picker.js"></script>
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
            "canvas", //--  Id of canvas object
            400, //-- Width of container object
            200, //--- Width of center object
            "container-canvas", //--- Id of container object
            "center-canvas", //--- Id of center circle object
            "value-canvas" //--- Id of input object for set selected color
    );
}

```


## Author

* [Ali Camargo](http://github.com/alicamargom)