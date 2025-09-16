# Path Access
The Path Access module gives site administrators an additional layer of access
control to all pages of a Backdrop CMS site. It allows roles to either deny or
allow certain paths or patterns of paths.

## Benefits
Although a lot of Backdrop CMS modules provide some degree of access control
permissions it never covers all possible requirements users have. Path Access
provides the means to restrict pages based on their path alias - meaning you
can lock out certain user role groups from whole sections of a site using
wildcards.

## Requirements
<!--
List any dependencies here. Remove this section if not needed.
-->
This module requires that the following modules are also enabled:
- [Chain Menu Access API](https://backdropcms.org/project/chain_menu_access)

## Installation
<!--
List the steps needed to install and configure the module. Add/remove steps as
necessary.
-->
- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.
- Navigate to Admin > Configuration > User Accounts > Path Access
(`admin/config/people/path-access/`) to define the settings for each role.
- Configuring the module requires the "Administer permissions" permission.

## Issues
<!--
Link to the repo's issue queue.
-->
Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/path_access/issues.

## Current Maintainers
<!--
List the current maintainer(s) of the module, and note if this module needs
new/additional maintainers.
-->
- [Martin Price](https://github.com/yorkshire-pudding) -
[System Horizons Ltd](https://www.systemhorizons.co.uk)
- Collaboration and co-maintainers welcome!

## Credits
<!--
Give credit where credit's due.
If this is a Drupal port, state who ported it, and who wrote the original Drupal
module. If this module is based on another project, or uses third-party
libraries, list them here. You can also mention any organisations/companies who
sponsored the module's development.
-->
- Ported to Backdrop CMS by - [Martin Price](https://github.com/yorkshire-pudding) -
[System Horizons Ltd](https://www.systemhorizons.co.uk)
- Port sponsored by [French Leaseback Community](https://frenchleaseback.net/)
- Module originally created for Drupal by [Mike Carter](https://www.drupal.org/u/budda)
- Inital development sponsored by [Ixis](http://www.ixis.co.uk/)
- Maintenance and development of [Drupal module](https://www.drupal.org/project/path_access) also includes:
  - [Tom Kirkpatrick](https://www.drupal.org/u/mrfelton)
  - [Adirael](https://www.drupal.org/u/adirael)
  - [László CSÉCSY](https://www.drupal.org/u/boobaa)

## License
<!--
Mention what license this module is released under, and where people can find
it.
-->
This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
