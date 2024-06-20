# Usage
## Initiate Locale
To use `Locale`, simply include the Locale.php file and create a new instance of the `Locale` class.

```php
<?php

// Import additionnal class into the global namespace
use LaswitchTech\coreLocale\Locale;

// Load Composer's autoloader
require 'vendor/autoload.php';

// Initiate Locale
$Locale = new Locale();
```

### Properties
`Locale` provides the following properties:

- [Configurator](https://github.com/LaswitchTech/coreConfigurator)
- [Logger](https://github.com/LaswitchTech/coreLogger)

### Methods
`Locale` provides the following methods:

- [config()](methods/Locale/config.md)
- [isInstalled()](methods/Locale/isInstalled.md)
- [lookup()](methods/Locale/lookup.md)
- [ping()](methods/Locale/ping.md)
- [scan()](methods/Locale/scan.md)
