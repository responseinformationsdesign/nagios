# TYPO3 Extension: Nagios

This open-source software is an extension for the enterprise content management system [TYPO3](https://typo3.org). The extension gathers information about the TYPO3 instance and exposes the data for a Nagios® monitoring server. [Nagios®](https://www.nagios.org) is the industry standard in open-source server/service/network monitoring.


## Documentation

A comprehensive [documentation](https://github.com/schams-net/nagios/blob/release/Documentation/Index.md) is available at GitHub. It contains information about the [installation process](https://github.com/schams-net/nagios/blob/release/Documentation/InstallationAndSetup/Index.md), [system requirements](https://github.com/schams-net/nagios/blob/release/Documentation/InstallationAndSetup/Requirements/Index.md), [configuration options](https://github.com/schams-net/nagios/blob/release/Documentation/AdministrationAndConfiguration/Index.md), [security aspects](https://github.com/schams-net/nagios/blob/release/Documentation/SecurityAspects/Index.md), and more.

➤ Read more: [Documentation](https://github.com/schams-net/nagios/blob/release/Documentation/Index.md).


## Installation

The TYPO3 extension “Nagios” is available as a [Composer](https://getcomposer.org/) package at [Packagist](https://packagist.org/packages/schams-net/nagios).

```bash
composer require schams-net/nagios
```

More details and alternative installation methods can be found in the [documentation](https://github.com/schams-net/nagios/blob/release/Documentation/Index.md).


## Git Branches, Versions, and Compatibility

The TYPO3 extension “Nagios” follows [semantic versioning](https://semver.org/) since version 3.x.

| Major version: | Git branch:                                                            | Status:          | TYPO3 compatibility: |
|---------------:|:----------------------------------------------------------------------:|:-----------------|:---------------------|
|           v1.x | [v1-oldstable](https://github.com/schams-net/nagios/tree/v1-oldstable) | archived         | TYPO3 v4.5 and v6.2  |
|           v2.x | [v2-oldstable](https://github.com/schams-net/nagios/tree/v2-oldstable) | old stable       | TYPO3 v7, v8, and v9 |
|           v3.x | [release](https://github.com/schams-net/nagios/tree/release)           | **stable**       | TYPO3 v9 and v10     |
|                | [testing](https://github.com/schams-net/nagios/tree/testing)           | development/test | *to be determined*   |


## License

(c) 2010-2021 Michael Schams <[schams.net](https://schams.net)>, all rights reserved

This software free software; you can redistribute it and/or modify it under the terms of the GNU General Public License, either version 2 of the License, or any later version. For the full copyright and license information, please see the documentation that was distributed with this source code.

➤ Read more: [The GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html).

Nagios® was originally developed by Ethan Galstad and is licensed under the GNU GPL V2. No parts or components of Nagios® are used in the TYPO3 extension.

➤ Read more about Nagios® at: <https://www.nagios.org>.
