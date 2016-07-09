# funkstrap
Functional CSS for Bootstrap

This library builds directly on top of the amazing functional CSS libraries [BassCSS](http://basscss.com) by [jxnblk](https://github.com/jxnblk) and [Tachyons](http://tachyons.io) by [mrmrs](https://github.com/mrmrs).

It follows the "verbose" class API found in BassCSS, but extends the codebase to ensure that every class has viewport-specific versions, allowing you the flexibility to turn on and off any property at any viewport.

It also adapts the class API slightly to conform with the Bootstrap class API. Thus, dashes are used to separate name sections; viewport sizes are `xs`, `sm`, `md`, and `lg`; viewport sizes comes _before_ numbers (e.g. `col-xs-12-25`).

Finally, it adds a Flexbox-based 25-column grid, to be used in addition to Bootstrap's 12-column grid.
