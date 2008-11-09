;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;; Money CCK field for CCK 2 and Drupal 6
;; $Id$
;;
;; Current maintainer: markus_petrux
;;   http://drupal.org/user/39593
;; Original author: Wim Leers
;;   http://drupal.org/user/99777
;;   http://wimleers.com/work
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

OVERVIEW
========

This module defines the "money" CCK field. It uses the Currency API, which is
included in the Currency module, to get a list of valid currencies.

Only amounts with 2 decimals can be used. Any decimal separator and any digit
group separator can be used, but it defaults to the comma and the dot
respectively, which is according to ISO 31-0. The separators can be changed at
any point, only integers are stored in the database.


REQUIREMENTS
============

- CCK (http://drupal.org/project/cck)
- Currency API (http://drupal.org/project/currency)
- Format Number API (http://drupal.org/project/format_number)


INSTALLATION
============

- Copy all contents of this package to your modules directory preserving
  subdirectory structure.

- Goto Administer > Site building > Modules to install this module.

- Create or edit content types and start adding Money fields. :)
