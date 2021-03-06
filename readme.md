=== Plugin Name ===
Contributors: mbsatunc, gilbitron
Requires at least: 3.4
Tested up to: 4.9.6
Stable tag: 1.2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add "like" functionality to your posts and pages

== Description ==

Add "like" functionality to your posts and pages. Display your most liked posts via widget.

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Configure the settings via the menu item that appears
1. Place `<?php if( function_exists('zilla_likes') ) zilla_likes(); ?>` in your templates
1. Use the `[zilla_likes]` shortcode in your posts and pages

== Changelog ==

= 1.2.2 =
06-20-2018
- Change required user capabilities for accessing settings from update_core to manage_options.

= 1.2.1 =
06-19-2018
- Fixed deprecation warning.

= 1.2.0 =
01-10-2016
- Added `withCredentials: true` to ajax call so https backend will work with http frontend

= 1.1.1 =
Fixes a javascript error that occurs for sites using AJAXed likes.

= 1.1 =
Add most liked widget for displaying top posts

= 1.0 =
Initial release

== Upgrade Notice ==

= 1.1.1 =
Fixes a JS error for AJAXed likes

= 1.1 =
Adds most liked widget