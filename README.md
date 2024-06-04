Conditional Fields
======================

Define dependencies between fields based on their states and values. Conditional
Fields is basically a user interface for the States API, plus the ability to
hide fields on certain conditions when viewing content.

The Conditional Fields module allows you to manage sets of dependencies between
fields. When a field is "dependent", it will only be available for editing and
displayed if the state of the "dependee" field matches the right condition.
When editing a node (or any other entity type that supports fields, like users
and categories), the dependent fields are dynamically modified with the States
API.

You can, for example, define a custom “Article teaser" field that is shown only
if a "Has teaser" checkbox is checked.

**Limitations and Known Issues**

- Conditional Fields, for now, supports only core fields and widgets as dependee
fields. Fields from other modules might work, but probably won't. Dependent
fields, though, can be of any type.

Installation
------------

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

Configuration and Usage
-----------------------

Users with the "administer dependencies" permission can administer dependencies
at **admin/structure/dependencies**.

More details may be found (or contributed to) in the [Wiki](https://github.com/backdrop-contrib/conditional_fields/issues)

Issues
------

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/conditional_fields/issues)

Current Maintainers
-------------------

- [Laryn Kragt Bakker](https://github.com/laryn)
- Co-maintainers wanted

Credits
-------

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn)
- Ongoing Backdrop development is supported by [Aten Design Group](https://aten.io)
- Initial port to Backdrop sponsored by [CEDC.org](https://CEDC.org)
- Originally written by and maintained for Drupal by [Gregorio Magini](https://www.drupal.org/u/peterpoe)

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
