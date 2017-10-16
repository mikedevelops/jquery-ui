# [jQuery UI](http://jqueryui.com/) - Interactions and Widgets for the web

jQuery UI is a curated set of user interface interactions, effects, widgets, and themes built on top of jQuery. Whether you're building highly interactive web applications, or you just need to add a date picker to a form control, jQuery UI is the perfect choice.

This is a bespoke build with only the following components being concatenated into the final build.

```javascript
[
    "core.js",
    "widget.js",
    "widgets/mouse.js",
    "widgets/draggable.js",
    "widgets/droppable.js",
    "widgets/resizable.js",
    "widgets/selectable.js",
    "widgets/sortable.js",
    "effect.js"
]
```

Additional widgets can be added to the build by adding them to the `widgets` array on line 20 of `Gruntfile.js`

## Installation

```
npm install mikedevelops/jquery-ui --save
```
