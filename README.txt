
Description
-----------
This module defines the "money" field. It uses the Currency API, which is
included in the Currency module, to get a list of valid currencies.

Only amounts with 2 decimals can be used. Any decimal separator and any digit
group separator can be used, but it defaults to the comma and the dot
respectively, which is according to ISO 31-0. The separators can be changed at
any point, only integers are stored in the database.


Dependencies
------------
* Currency API (http://drupal.org/project/currency)
* Format Number (http://drupal.org/project/format_number)
* Formatted Number CCK (http://drupal.org/project/formatted_number)
  [D7 sandbox: http://drupal.org/sandbox/nouriassafi/1603812]

The currency conversion dialog submodule requires
jQuery 1.3.x (jQuery Update 6.x-2.x) and jQuery UI 1.7+ to work properly.

Installation
------------
See: http://drupal.org/documentation/install/modules-themes/modules-7

Maintainers
-----------
Drupal 7 version:
Rafal W (kenorb)
* contact: http://drupal.org/user/191974

Drupal 6 version:
Marc Ferran (aka Markus) [markus_petrux]
* contact: http://drupal.org/user/39593

Drupal 5 version (original author):
Wim Leers
* mail: work@wimleers.com
* website: http://wimleers.com/work
* contact: http://drupal.org/user/99777

The authors can be contacted for paid customizations of this module as well as
Drupal consulting, development and installation.
