Commerce CiviCRM Membership
===============

Commerce CiviCRM Membership is a powerful, flexible, user-friendly module which provide integration between Drupal Commerce and CiviCRM.

Installation & Getting Started
------------------------------

- Download and enable this module, its required modules.
- (Optional) To setup Membership start date please also enable "Line Item", "Line Item UI" and "Date" module.
- Goto  Store » Configuration » Line item types » Product.
- Added New field:
  - Title: Membership Start Date
  - Check Machine should be: field_membership_start_date
  - Select Field Type: Date
  - Select Field Widget: Select List


Documentation
-------------

1. It let you create a CiviCRM user and exposes most of regular field in provided in Store » Configuration » CiviCRM Member Settings.
2. It add Commerce Product Type and Product Display (content type).
3. It create CiviCRM Membership as Product type entities.
4. It create a Membership Product display node for purchasing membership.
5. Its  Store » Configuration » CiviCRM Member settings/config let you to create new user or update existing along with add new membership which user purchased.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/k-zafar/dc_civicrm_mem/issues

Credits
-------

- Written by [Kamran Zafar](https://github.com/k-zafar).
