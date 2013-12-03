Ractive.js scale transition plugin
=================================

*Find more Ractive.js plugins at [ractivejs.org/plugins](http://ractivejs.org/plugins)*

Allows you to scale in / out elements. Optional fade animation transition is turned on by default for fancines and this can be turned off (see usage example below).

Usage
-----

Include this file on your page below Ractive, e.g:

```html
<script src='lib/Ractive.js'></script>
<script src='lib/Ractive-transitions-scale.js'></script>
```

Or, if you're using a module loader, require this module:

```js
// requiring the plugin will 'activate' it - no need to use the return value
require( 'Ractive-transitions-scale' );
```
Note: you may need to change the paths where it says `require( 'ractive' )` or `define([ 'Ractive' ]...)`.

Example
-----
```html
<div intro='scale:{"fade":false, "duration":400}'>This will scale</div>
```

Plugin defaults
-----
```js
{
	duration: 250,
	easing: 'ease-out',
	fade: true,
	from: 0.3,
	to: 1
}
```




License
-------

Copyright (c) 2013 Ayman Mackouly. Licensed <a href="http://www.wtfpl.net/">WTFPL</a>
