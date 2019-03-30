# Changelog

## 1.2.2 _(2017-02-12)_
* Change: Check that there is a `HTTP_USER_AGENT` before doing attempting to use its value
* Change: Minor code and code documentation reformatting (spacing)
* Change: Minor readme.txt tweaks
* Change: Note compatibility through WP 4.7+
* Change: Update copyright date (2017)

## 1.2.1 _(2016-03-20)_
* New: Add LICENSE file.
* New: Add empty index.php to prevent files from being listed if web server has enabled directory listings.
* Change: Note compatibility through WP 4.4+.
* Change: Update copyright date (2016).

## 1.2 _(2015-02-28)_
* Hook `pre_site_transient_browser_` instead of `site_transient_browser_` to avoid unnecessary transient handling by WP
* Reformat plugin header
* Change documentation links to wp.org to be https
* Note compatibility through WP 4.1+
* Update copyright date (2015)
* Add plugin icon

## 1.1 _(2014-01-30)_
* Remove `__return_null()` it has since been added to core
* Add check to prevent execution of code if file is directly accessed
* Re-license as GPLv2 or later (from X11)
* Add 'License' and 'License URI' header tags to readme.txt and plugin file
* Remove ending PHP close tag
* Documentation improvements
* Minor code reformatting (spacing)
* Note compatibility through WP 3.8+
* Drop compatibility with versions of WP older than 3.4
* Update copyright date (2014)
* Change donate link
* Add assets directory to plugin repository checkout
* Add screenshot
* Add banner

## 1.0.1
* Note compatibility through WP 3.3+
* Add phpDoc for `__return_null()`
* Add link to plugin directory page to readme.txt
* Add Upgrade Notice section to readme.txt
* Update copyright date (2012)

## 1.0
* Initial release
