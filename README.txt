;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;; Money CCK field for CCK 2 and Drupal 6
;; $Id$
;;
;; Current maintainer: markus_petrux  (http://drupal.org/user/39593)
;; Original author   : Wim Leers      (http://drupal.org/user/99777)
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

OVERVIEW
========

This module defines the "money" CCK field. It uses the Currency API, which is
included in the Currency module, to get a list of valid currencies.

Decimal points and thousands separators are formatted using the Format Number
API module (http://drupal.org/project/format_number), where these options are
configured from site and/or user settings.


REQUIREMENTS
============

- CCK (http://drupal.org/project/cck)
- Currency API (http://drupal.org/project/currency)
- Format Number API (http://drupal.org/project/format_number)
- Formatted Number CCK (http://drupal.org/project/formatted_number)


INSTALLATION
============

- Please, make sure all required modules are installed first.

- Copy all contents of this package to your modules directory preserving
  subdirectory structure.

- Goto Administer > Site building > Modules to install this module.

- Create or edit content types and start adding Money fields. :)
