Webform Layout
==============

This module adds a new type of Webform component: the layout box. By placing webform fields inside layout boxes, you can arrange them into rows and columns. By placing fieldsets or additional layout boxes inside a layout box, you can achieve multicolumn or grid-like layouts.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  <https://backdropcms.org/guide/modules>

How to use
----------

- Go to the main field list of a webform.
- Add a layout box to your form.
- For alignment, choose "Horizontal" or "Equal Width" to divide the space equally.
- Save the component.
- Add or drag other fields into the container.
- To create columns, add any number of vertically-aligned layout boxes inside a horizontally-aligned one.
- Be careful, some components are too wide by default (e.g. textfield). So, you may need to adjust them in order to fit side-by-side.
- If you need a title and/or description for your group you can add markup to the form, or insert the layout container into a fieldset.
- Note: The "Equal Width" feature works up to 9 children.
- To output the values separately in a submission e-mail, use the following token: `[submission:values:layoutboxkey:key]`

Compatibility
-------------

Supports the form_builder module (if ported from Drupal).

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
<https://github.com/backdrop-contrib/webform_layout/issues>

Current Maintainers
-------------------

- Herb v/d Dool <https://github.com/herbdool>

Credits
-------

- Ported to Backdrop by Herb v/d Dool <https://github.com/herbdool>
- Originally developed for Drupal by colemanw <https://www.drupal.org/u/colemanw>.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
