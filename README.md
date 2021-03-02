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
$('select:not([multiple])').selectability();
```

You can pass a property of position to arrange where the rendered markup will appear in relation to the original select element.

Possible values: `above` / `below`

```javascript
$('select:not([multiple])').selectability({
    'position': 'above'
})
```

You can pass a property of floatLabel to add support for a floating label design pattern, where the label overlays the field like a placeholder would, but transitions above the field once a value has been set via an animation. This requires some additional CSS to set up, but essentially an empty option will be set to the value of the field label in the listbox when opened. This avoids an empty slot in the listbox when the field already has a value and a new value is being set.

```javascript
$('select:not([multiple])').selectability({
	'floatLabel': true
})
```

Colophon
========

Selectability was originally developed for the National Assessment of Educational Progress (NAEP) in partnership with ETS, using funding from the US Department of Education.
