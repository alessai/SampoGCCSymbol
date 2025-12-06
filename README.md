# GCC Currency Symbols for WooCommerce

A WordPress plugin that replaces text currency codes with authentic currency symbols for Gulf Cooperation Council (GCC) currencies in WooCommerce.

## Supported Currencies

| Currency | Code | Symbol |
|----------|------|--------|
| Omani Rial | OMR | <img src="omr-symbol.png" alt="OMR" height="20"> |
| Saudi Riyal | SAR | <img src="sar-symbol.png" alt="SAR" height="20"> |
| UAE Dirham | AED | <img src="aed-symbol.png" alt="AED" height="20"> |

## Features

- **Authentic Symbols**: Displays proper Arabic currency symbols instead of text codes
- **Smart Detection**: Automatically activates when WooCommerce uses a supported currency
- **Email Compatible**: PNG fallback ensures symbols display correctly in order emails
- **Admin Friendly**: Shows text codes in admin dropdowns for easy identification
- **Color Matching**: SVG symbols inherit text color via `currentColor`
- **Lightweight**: No JavaScript, no external dependencies

## Installation

### From GitHub
1. Download the latest release zip file
2. Go to WordPress Admin > Plugins > Add New > Upload Plugin
3. Upload the zip file and activate

### Manual
1. Clone this repository into `/wp-content/plugins/`
2. Activate the plugin through the WordPress admin

## Requirements

- WordPress 5.0+
- WooCommerce 3.0+
- PHP 7.2+

## Compatibility

- WooCommerce HPOS (High-Performance Order Storage)
- WooCommerce Blocks
- Classic and Block themes

## Changelog

### 1.3.0
- Added Saudi Riyal (SAR) support
- Added UAE Dirham (AED) support
- Security improvements
- Code quality enhancements

### 1.2.2
- Initial public release
- Omani Rial (OMR) support

## License

GPL v2 or later

## Author

Starter Starter
