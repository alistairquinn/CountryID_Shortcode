# Currency Conversion Shortcode
This WordPress shortcode has been created to convert country ID's to the countries name. It was orginally developed to convert the ID supplied in the Star XML feed.

## Install

1. Copy the file into your theme directory ./inc folder
2. Add the following code to your functions.php file:

<pre>
/**
 * Load Country Code Conversion Shortcode.
 */
require get_template_directory() . '/inc/country-codes.php';
</pre>

## Usage

[country id=GB]    //United Kingdom

