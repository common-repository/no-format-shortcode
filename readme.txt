=== No Format Shortcode ===
Contributors: freshbrewedweb
Donate link: https://freshbrewedweb.com
Tags: wpautop, formatting, shortcode, disable, html
Requires at least: 3.7
Tested up to: 4.7.4
Stable tag: 1.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.html

This plugin provides a shortcode to selectively disable WordPress' automatic formatting. Very useful for anyone looking to write some custom HTML, but doesn't want to completely diasble wpautop.

== Installation ==

1. Upload the `no-format-shortcode` folder to the `/wp-content/plugins` directory
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. That's it! Start using the [noformat] shortcode.

== Usage ==

Wrap any HTML content, or content for which you wish to disable formatting inside of the [noformat] shortcode, like this:

<pre>
[noformat]
<ul>
  <li>This content won't be
    formatted.
</ul>

You'll notice no automatic <p>'s or <br/>'s are added within this shortcode.
[/noformat]
</pre>

== Screenshots ==

1. The plugin in action.

== Upgrade Notice ==

= 1.0 =
Hello, this is the first version.

== Changelog ==

= 1.0 =
* Start of a simple plugin.
