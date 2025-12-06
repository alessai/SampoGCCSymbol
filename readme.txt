=== GCC Currency Symbols ===
Contributors: sampo
Tags: woocommerce, currency, omani rial, omr, oman, saudi riyal, sar, saudi arabia, uae dirham, aed, gcc
Requires at least: 5.0
Tested up to: 6.7
Requires PHP: 7.2
Stable tag: 1.3.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Replaces WooCommerce currency symbols for Omani Rial (OMR), Saudi Riyal (SAR), and UAE Dirham (AED) with their official new symbols.

== Description ==

This plugin replaces the standard currency symbols in WooCommerce with the official new currency symbols for Gulf Cooperation Council (GCC) currencies:

* **Omani Rial (OMR)** - Replaces "ر.ع." with official symbol
* **Saudi Riyal (SAR)** - Replaces "ر.س." with official symbol
* **UAE Dirham (AED)** - Replaces "د.إ" with official symbol

Features:

* Uses official currency symbol designs
* SVG format for crisp display at any size
* Automatically matches text color (uses currentColor)
* Works in cart, checkout, product pages, and emails
* PNG fallback for email clients that don't support SVG
* Compatible with WooCommerce Blocks
* Compatible with WooCommerce HPOS (High-Performance Order Storage)
* Supports both classic and block-based themes

== Installation ==

1. Upload the `omr-currency-symbol` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Make sure WooCommerce is installed and your store currency is set to one of the supported currencies (OMR, SAR, or AED)

== Frequently Asked Questions ==

= Does this plugin require WooCommerce? =

Yes, this plugin requires WooCommerce to be installed and activated.

= Which currencies are supported? =

Currently, the plugin supports:
* Omani Rial (OMR)
* Saudi Riyal (SAR)
* UAE Dirham (AED)

= Can I customize the symbol size? =

The symbol automatically scales with text. You can add custom CSS to adjust the size if needed using the `.currency-symbol` class.

= Does it work with WooCommerce Blocks? =

Yes, the plugin includes CSS pseudo-elements and JavaScript to ensure symbols display correctly in WooCommerce Blocks.

= Does it work in emails? =

Yes, emails use PNG images with base64 encoding for maximum compatibility with email clients.

== Screenshots ==

1. OMR currency symbol displayed on product page
2. SAR currency symbol in cart
3. AED currency symbol at checkout

== Changelog ==

= 1.3.0 =
* Security: Added input sanitization for admin page detection
* Updated readme.txt to reflect all supported currencies
* Code quality improvements

= 1.2.2 =
* Fixed raw SVG code appearing in WooCommerce settings dropdown
* Admin pages now show standard text symbols in dropdowns

= 1.2.1 =
* Added AED (UAE Dirham) currency support
* Added woocommerce_currencies filter to ensure AED is available

= 1.2.0 =
* Added AED (UAE Dirham) currency support with official symbol

= 1.1.0 =
* Added SAR (Saudi Riyal) currency support with official symbol
* Improved WooCommerce Blocks compatibility

= 1.0.0 =
* Initial release with OMR support

== Upgrade Notice ==

= 1.3.0 =
Security update with input sanitization improvements. Recommended for all users.
