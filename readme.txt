=== Woo Sendle API ===
Contributors: oldlabel
Donate link: https://www.oldlabel.com/
Tags: freight, sendle, package, woocommerce, woo, parcel, send
Requires at least: 4.7
Tested up to: 5.0
Stable tag: 1.0.4
Requires PHP: 5.2.4
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Book Sendle pickup from your WooCommerce orders screen! A plugin for WooCommerce that enables shop owners to book packages on Sendle and retrieve packing labels without leaving WooCommerce.

== Description ==

Book Sendle pickup from your WooCommerce orders screen! A plugin for WooCommerce that enables shop owners to book packages on Sendle and retrieve packing labels without leaving WooCommerce.

This plugin was developed as a tool for self education - there will be bugs and issues! If you find any feel free to make contact. Over time I hope to close them out.

== Getting Started ==

=== Prerequisites ===
To use Woo Sendle API you need to have:
* WordPress with WooCommerce plugin activated
* A Sendle account with an API username and password

==== WooCommerce ====
The plugin has been tested with WooCommerce versions 3.2.6 to 3.4.2. This plugin is likely to work with all releases of WooCommerce under 3.4.

**Note** _Actions_ must be enabled under _Screen Options_ in WooCommerce v3.4 to show Woo Sendle API actions.

==== Sendle ====
Follow the steps in this [Sendle API support article](https://support.sendle.com/hc/en-us/articles/210798518-Sendle-API) to gain access to your Sendle API key.

=== Installing ===
Copy the files into your WordPress plugins folder and activate via the WordPress _plugins_ page.

==== Configuration ====
The plugin is configured in an extra tab called _Sendle API_ in the standard WooCommerce Settings section. The settings page lets you configure:
* Enable/disable the plugin
* Connection mode (sandbox or live)
* API username and key
* Default pickup information

=== Usage ===
The plugin is used by an extra button in the _Actions_ section of the WooCommerce orders page. The booking button is only available for orders in a status of __**processing**__. If order has been booked then the button will always be available.

**Note** The plugin can only create one booking per order. To create a second booking you will need to login to the Sendle website and book directly via the dashboard.

== FAQ Section ==

See https://www.oldlabel.com/woo-sendle-api for FAQ/How To.

=== License ===
The project is licensed under GNU v3 - see LICENSE file for details.

=== Acknowledgments ===
Thanks to all those who contribute answers to questions on various websites, whose code was used for inspiration and often simplicity.

=== Issues and Future Enhancements ===
Please make contact if you find any issues.
