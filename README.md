# sinewave

Simple object for getting and setting form values using javascript

Inspiration from this stackoverflow answer (for the setting part): 

https://stackoverflow.com/a/35468919/464549

## Install

npm install --save get-set-form-values

Or 

    <script src="dist/get-set-form-values.js"></script>

## Usage

~~~js

formValues = require('get-set-form-values');
var mainForm = document.getElementById('main_form');
var values = formValues.get(mainForm);

// Example load values
var loadJsonValues = {"radio": "d", "fulltext": "Area", "range": "9", "checkbox": ["B"], "input": "Text", "select": ["saab", "mercedes"], "select-single": "volvo"};
formValues.set(mainForm, loadJsonValues);
~~~

See: [index.html](index.html)

Live example: 

See: https://codepen.io/diversen/full/yoVQZq/

MIT © [Dennis Iversen](https://github.com/diversen)

