Selectability
=============

An accessible, themable dropdown widget.

About
=====

Selectability is a jQuery plugin to create a custom themable dropdown widget that follows accessibility best practices out of the box. We use [WAI-ARIA](http://www.w3.org/TR/wai-aria/) role and state markup and follow the focus model to provide an almost-native experience for users, no matter the device.

This repository is a fork by BarkleyREI to add functionality we find necessary to improve the developer experience of using the plugin. No change to the accessible nature of the plugin has been altered.

Usage
=====

```javascript
$('select').selectability();
```

You can pass a property of position to arrange where the rendered markup will appear in relation to the original select element.

Possible values: `above` / `below`

```javascript
$('select').selectability({
    'position': 'above'
})
```

Colophon
========

Selectability was originally developed for the National Assessment of Educational Progress (NAEP) in partnership with ETS, using funding from the US Department of Education.
