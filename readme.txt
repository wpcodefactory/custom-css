=== Custom CSS, JS & PHP ===
Contributors: wpcodefactory, algoritmika, anbinder, karzin, omardabbas
Tags: css, js, php, javascript
Requires at least: 4.4
Tested up to: 6.7
Stable tag: 2.4.2
License: GNU General Public License v3.0
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Just another custom CSS, JavaScript & PHP tool for WordPress.

== Description ==

**Custom CSS, JS & PHP** is a lightweight plugin that lets you add:

* custom **CSS** (front-end and/or back-end),
* custom **JavaScript** (front-end and/or back-end), and
* custom **PHP**.

### &#128472; Feedback ###

* We are open to your suggestions and feedback. Thank you for using or trying out one of our plugins!

== Frequently Asked Questions ==

= How do I disable (non-valid) PHP code? =

Add `alg_disable_custom_php` parameter to the URL, e.g.:
```
http://example.com/wp-admin/tools.php?page=alg-custom-php&alg_disable_custom_php
```

== Installation ==

1. Upload the entire plugin folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the "Plugins" menu in WordPress.
3. Start by visiting plugin settings at "Tools > Custom CSS", "Tools > Custom JS" or "Tools > Custom PHP".

== Screenshots ==

1. Custom CSS.
2. Custom JS.
3. Custom PHP.

== Changelog ==

= 2.4.2 - 31/03/2025 =
* Dev - Security - Added user permissions check and nonce verification when saving options.

= 2.4.1 - 06/01/2025 =
* Dev - Custom PHP - "Execute" option added. Defaults to "Execute on `plugins_loaded` action". New option: "Execute in `[alg_custom_php]` shortcode".
* Dev - Changed the deploy script.

= 2.4.0 - 22/11/2024 =
* Dev - Security - Output escaped.
* Dev - Coding standards improved.
* Dev - Code refactoring.
* Tested up to: 6.7.

= 2.3.0 - 05/09/2024 =
* Dev - Code editors added.
* Dev - Custom PHP - Now allows/recommends the opening tag.
* Dev - PHP 8.2 compatibility - "Creation of dynamic property is deprecated" notice fixed.
* Dev - Admin settings restyled.
* Dev - Code refactoring.
* Tested up to: 6.6.

= 2.2.1 - 09/12/2022 =
* Tested up to: 6.1.
* Readme.txt updated.
* Deploy script added.

= 2.2.0 - 28/09/2021 =
* Dev - Plugin is initialized on the `plugins_loaded` action now.
* Dev - Localization - `load_plugin_textdomain()` moved to the `init` action.
* Dev - Code refactoring.
* Tested up to: 5.8.

= 2.1.0 - 03/03/2020 =
* Dev - Admin settings - Split into three separate sections: "Custom CSS", "Custom JS" and "Custom PHP"; menu added.
* Dev - Admin settings - Descriptions updated; restyled.
* Dev - Admin settings - Checkbox - Wrapped in `<label>` now.
* Donate link removed.
* Tested up to: 5.3.

= 2.0.1 - 18/10/2018 =
* Dev - "CSS position" and "JS position" options added.

= 2.0.0 - 28/09/2018 =
* Feature - "Custom JS" section added.
* Feature - "Custom PHP" section added.
* Dev - Major code refactoring.
* Dev - Settings screen restyled.
* Dev - POT file added.

= 1.0.0 - 07/04/2017 =
* Initial Release.

== Upgrade Notice ==

= 1.0.0 =
This is the first release of the plugin.
