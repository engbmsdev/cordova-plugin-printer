Cordova Print Plugin
====================

Fork of katzer's plugin.
Bugfix on `isAvailable` method that now is called `isServiceAvailable`

```javascript
/**
 * Checks if the printer service is avaible (iOS)
 * or if connected to the Internet (Android).
 *
 * @param {Function} callback
 *      A callback function
 * @param {Object?} scope
 *      The scope of the callback (default: window)
 *
 * @return {Boolean}
 */
cordova.plugins.printer.isServiceAvailable(
    function (isAvailable) {
        alert(isAvailable ? 'Service is available' : 'Service NOT available');
    }
);
```

## License

This software is released under the [Apache 2.0 License][apache2_license].

© 2013-2014 appPlant UG, Inc. All rights reserved

Thanks to: [katzer]

[apache2_license]: http://opensource.org/licenses/Apache-2.0
[katzer]: katzer@appplant.de
