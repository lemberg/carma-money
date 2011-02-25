
Description
-----------
This module defines the "money" CCK field. It uses the Currency API, which is
included in the Currency module, to get a list of valid currencies.

Only amounts with 2 decimals can be used. Any decimal separator and any digit
group separator can be used, but it defaults to the comma and the dot
respectively, which is according to ISO 31-0. The separators can be changed at
any point, only integers are stored in the database.


Dependencies
------------
* CCK (http://drupal.org/project/cck)
* Currency API (http://drupal.org/project/currency)


Installation
------------
1) Place this module directory in your modules folder (this will usually be
"sites/all/modules/").

2) Enable the module.


Sponsor
-------
Etienne Leers of http://creditcalc.biz.


Author
------
Wim Leers

* mail: work@wimleers.com
* website: http://wimleers.com/work

The author can be contacted for paid customizations of this module as well as
Drupal consulting, development and installation.
