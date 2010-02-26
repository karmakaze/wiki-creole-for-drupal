Creole wiki input filter Drupal module
======================================

Provides the Wiki Creole markup input filter for Drupal. Wiki Creole is
intended to be a common basic markup shared between many different wiki
implementations and acts as a foundation of knowledge and communication.
Often Creole is used in conjunction with other wiki markups which provide
more advanced formatting.

If using the Drupal-supplied URL filter with this filter, have this Creole
filter configured with a smaller weight (earlier) before the URL filter.

This software is provide AS-IS without warranty of any kind under the
conditions of the GNU General Public License v3 as described in the
LICENSE.txt file.

For more information on Wiki Creole markup, see http://wikicreole.org


Quickstart
----------

1. Move the entire "creole" directory into your Drupal installation's
   sites/all/modules folder (or your site specific directory).

2. Enable the module on Administer >> Site building >> Modules

3. Set up a new input format or add Creole support to an existing format at
   Administer >> Site configuration >> Input formats

4. For best security, ensure that the Drupal-supplied HTML filter is after
   the Creole filter on the "Reorder" page of the input format and that the
   HTML filter is configured.


Credits and Support
-------------------
Creole wiki input filter created by Keith Kim <http://keithkim.org>
Look in file creole.module for the version number.
Latest version can be found at https://code.google.com/p/wiki-creole-for-drupal
Issues with this module can also be searched and reported there.
