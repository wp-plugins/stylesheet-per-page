=== Stylesheet Per Page ===
Contributors: jkohlbach
Donate link: http://www.codemyownroad.com
Tags: stylesheet, page styles, ie, ie stylesheet
Requires at least: 3.0
Tested up to: 3.1
Stable tag: trunk

Allows you to add individual stylsheets for each page or even posts. You can also add IE specific stylesheets and iOS device specific stylsheets. Supports custom post types.

== Description ==

Adds a custom stylesheet/s all of the pages on your WordPress install with options to check for the existence of the stylesheet before adding.

Allows for adding IE specific stylesheets all the way back to version 6. Just enable in the plugin options and add the stylesheets to your theme directory.

NEW in 0.5 - Stylesheet Per Page now allows adding of an iOS specific stylesheet. Simply enable in the plugin options and add the stylesheet to your theme directory.

This plugin supports use with custom post types.

== Installation ==

1. Upload the plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

To use this plugin, just add stylesheets in the following formats to your theme's base directory or a "css" subdirectory inside your theme's base directory:

* For pages use page-[page_name].css where "page_name" is the slug of the page.

* For author pages use user.css and for individual user pages user-[username].css.

* For different post types user [post_type].css where "post_type" is the name of the custom post type or just 'post' for regular posts.

* For individual posts use [post_type]-[post_name].css where "post_type" is the custom post type or just 'post' for regular posts, and "post_name" is the slug of the post.

* To activate IE specific stylesheets just create css files with the following naming:
ie.css (covers all IE versions), ie7.css (covers IE 7 and below), ie6.css (covers IE 6 and below).

* To activate an iOS specific stylsheet create ios.css and enable in the plugin options.

== Frequently Asked Questions ==

= How do I activate IE stylesheets? =
To activate stylesheets enable the option in the plugin options and create css files with the following naming convention:
ie.css (covers all IE versions), ie7.css (covers IE 7 and below), ie6.css (covers IE 6 and below).

= How do I get Stylesheet Per Page to check for the files first before trying to include them? =

Easy, just tick the option under the Stylesheet Per Page admin options under found under the Settings menu.

= How do I enable an iOS stylesheet? =

To activate an iOS specific stylsheet create ios.css and place it in your theme's base directory or css subdirectory inside your theme's base directory. You will also need to enable the checkbox in the plugin options.

= Is there a development version of this plugin? =

Yes, you can find it on github at http://github.com/jkohlbach, but it's more often than not the same version as here unless I'm actively working on it.

== Screenshots ==

N/A

== Upgrade Notice ==

N/A

== Changelog ==

* 0.5 Added iOS specific stylesheet support and fixed option handling
 - Fixed option handling to use a single option for easy handling throughout the plugin
 - Added an iOS option for optionally printing ios.css for iOS devices.

* 0.4 Fixing a bug with stylesheet generation on custom post types
 - Bug fix for sheets with no name appearing when using with custom post types

* 0.3 Adding support for IE specific stylesheets
 - Added new functionality to allow optional generation of IE specific sheets
 
* 0.2 Initial code revisions
 Changes:
 - Structured the code better
 - Added a menu for the options page
 - Improved commenting
 - Added option to not print the stylesheet if the file doesn't exist

* 0.1 Initial version
 Changes:
 - Add a stylesheet for every page