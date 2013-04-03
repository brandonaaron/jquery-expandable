# expandable

A jQuery plugin that auto-expands textareas to fit the contents as a user types.


## Settings

The expandable plugin has 5 settings:

* `duration` - The speed of the animation when expanding (or shrinking). Default is 'normal'.
* `init` - If true, the textarea will be resized to fit its content on initialization.
* `interval` - The interval at which it checks the textarea. Default is 750.
* `within` - The number of rows left before expanding. Default is 1.
* `by` - The number of rows to expand by. Default is 2.
* `maxRows` - The maximum number of rows the textarea can be expanded to. Default is false which will allow the textarea to keep expanding.


## Dynamic Updating

If you need, you can trigger an update to the textarea by doing the following:

    $('textarea').trigger('update');

This is useful if you are injecting content into the textarea via JavaScript.


## License

The expandable plugin is licensed under the MIT License (LICENSE.txt).

Copyright (c) 2013 [Brandon Aaron](http://brandonaaron.net)

## Contributors

* Karl Swedberg
* Pistos
