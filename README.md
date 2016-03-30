# Filtered Webform Results
A Drupal 7 feature that provides a filterable view of webform submission results, and downloadable report.
A menu item will be created under "Reports" (Webform Reports) that links to a page with a list of links to the report page for each existing webform. Any forms added after installing the module, will have to be added manually.

* Path to links page: /webform-reports
* Path to reports pages: /admin/[nid]/filtered-form-results (where [nid] is the node id for the form to report on).
* Aliases are created for the reports pages: /admin/[form name]/results
