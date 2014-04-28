jQuery Inactivity Timeout
===============

This script can be used to warn users that they will be logged out due to inactivity, and subsequenty log them out if they do not choose to continue.  It works across multiple tabs/browser windows by storing a cookie, or by using localStorage with [store.js](https://github.com/marcuswestin/store.js).

Demo
------------
A simple demo is available at http://adesigns.github.io/jquery-inactivity-timeout

Dependencies
------------
* jQuery 1.7+
* Optional: [store.js](https://github.com/marcuswestin/store.js) if you'd prefer to use localStorage over browser cookies.

Usage
-----

The script works out of the box with minimal configuration.  Simply include jquery.inactivityTimeout.js in your document, and initialize it, like so:

```js
$(document).inactivityTimeout();
```

Usage with [store.js](https://github.com/marcuswestin/store.js)
-------

Simply add store.js to your page, and this script will automatically use store.js.

Options
-------

You can refer to the defaults in the script to see customization options.

===============

TO DO: More documentation.