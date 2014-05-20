jquery.formsaver.js
===================

Easy jQuery plugin for saving and restoring form data into LocalStorage

## Usage:
```javascript
$(".save_button").click(function () {
    $("#form_id").saveForm();
});

$(".restore_button").click(function () {
    $("#form_id").restoreForm();
});
```
Live demo [here](http://hackprime.github.io/jquery.formsaver.js/).

## Requirements:
* jQuery 1.0+
* LocalStorage support (IE 8.0+, Firefox 3.5+, Safari 4.0+, Chrome 4.0+, Opera 10.5+, iOS Safari 2.0+, Android 2.0+)
* JSON support (IE 8.0+, Firefox 3.1+, Safari 4.0+, Chrome 3.0+, Opera 10.5+, iOS Safari 4.0+, Android 2.1+) or [JSON.js library](https://github.com/douglascrockford/JSON-js)
