=== MMWD Remove Add To Cart for WooCommerce ===
Contributors: mcgregormedia
Donate link: https://paypal.me/mcgregormedia
Requires at least: 4.7
Tested up to: 4.8
License: GNU General Public License v3.0
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Removes all Add to Cart buttons throughout a WooCommerce website without affecting anything else hooked into the Add to Cart actions.

== Description ==
This plugin removes all Add to Cart buttons throughout a WooCommerce website by using the woocommerce_is_purchasable filter rather than the Add to Cart actions, thus not affecting anything else hooked into these actions. This plugin also offers the option to remove prices in product archive and single product pages. *Please note removing prices may not work with themes that do not use the standard WooCommerce hooks.*

= How to use this plugin =

Navigate = to Admin > WooCommerce > Settings > Products and click the Remove Add to Cart settings tab. Use the checkboxes to enable the Remove Add to Cart and/or Remove Prices options.

= WooCommerce compatibility =

This plugin is compatible with WooCommerce 3.x versions.

== Installation ==
Install as usual by going to Plugins > Add New and searching for MMWD Remove Add To Cart for WooCommerce or download the plugin file and upload to your-site.com/wp-content/plugins.

== Changelog ==
1.3.0 12-10-2017
ADDED: WC requires at least and WC tested up to tags fo WooCommerce 3.2+
UPDATED: .pot file
FIXED: typo in readme.txt

1.2.0 16-08-2017
ADDED: check to see if WooCommerce is activated on plugin activation
ADDED: note to reflect theme issues
ADDED: .pot file for translation
TWEAK: edited description to make the usage instructions clearer
REMOVED: erroneous remove_actions

1.1.0 21-03-2017
ADDED: option to remove prices too, following user feedback

1.0.1 20-03-2017
FIXED: some users received a php warning when the plugin was in use

1.0.0 15-12-2016
Initial release