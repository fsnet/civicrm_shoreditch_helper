# CiviCRM Shoreditch Helper

CiviCRM Shoreditch Helper is a Drupal 8/9 module that adds certain body classes to CiviCRM admin pages.
The Shoreditch CSS styles rely on body classes like `page-civicrm page-civicrm-contact page-civicrm-contact-view` which are present in Drupal 7 but not in Drupal 8/9.
This module sole pupose is to provide a hook_preprocess_html() function which adds these classes.

## Requirements

* Drupal 9 (tested) or >= 8.8.0 (untested)
* CiviCRM
* [CiviCRM Shoreditch theme](https://github.com/civicrm/org.civicrm.shoreditch)

## Installation (git/cli)

Since this module is not available as Composer package for now, installation in the custom module directory is recommended.

```bash
# Navigate to your custom module directory, e.g.
cd modules/custom

# Download the module
git clone https://github.com/fsnet/civicrm_shoreditch_helper

# Enable the module, e.g. with Drush
drush en civicrm_shoreditch_helper
```
