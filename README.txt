Biblio Mendeley Module
======================

About
-----

This module adds, updates and deletes documents on Mendeley as they get changed in a Drupal Biblio installation.

Dependencies
------------

To contact Mendeley you need both the OAuth Library and the Mendeley API client. I recommend installing them to /sites/all/libraries/.

Usage
-----

1. Activate Biblio Mendeley module in Drupal
2. Set user permissions
3. If you want all documents to go in a special Mendeley group, set the group id on the Biblio Mendeley settings page.
  3a. On mendeley.com you find the group id when you click on "group details": it's in the URL like this: http://www.mendeley.com/groups/ID-HERE/
4. On your first action, you need to authenticate your consumer key from Mendeley. This has to be done only once.

© 2010 Jakob Stoeck