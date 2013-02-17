js-dashboard-rotater
====================

The goal of this project is to provide a simple browser-based utility to rotate through a series of web-based dashboards.

To add a page, modify the 'pages' array.

Supports scrolling of pages that do not violate browser cross origin policies.  Cross origin security can be bypased some browsers, but this is not recommened for machines with active users or when configuring display of non-trusted sites. In chrome, this can be accomplished by starting chrome with the `--disable-web-security` option.