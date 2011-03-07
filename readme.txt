=== Stylesheet Per Page ===
Contributors: jkohlbach
Donate link: http://www.codemyownroad.com
Tags: stylesheet, page styles, ie, ie stylesheet
Requires at least: 3.0
Tested up to: 3.1
Stable tag: trunk

Adds a custom stylesheet/s all of the pages on your WordPress install and also allows adding IE specific stylesheets.

== Description ==

Adds a custom stylesheet/s all of the pages on your WordPress install with options to check for the existence of the stylesheet before adding.

Also allows for adding IE specific stylesheets all the way back to version 6. Just enable in the plugin options and add the stylesheets to your theme directory.

== Installation ==

1. Upload the plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

To use this plugin, just add stylesheets in the following formats to your theme's base directory or a "css" subdirectory inside your theme's base directory:

* For pages use page-[page_name].css where "page_name" is the slug of the page.

* For author pages use user.css and for individual user pages user-[username].css.

* For different post types user [post_type].css where "post_type" is the name of the custom post type or just 'post' for regular posts.

* For individual posts use [post_type]-[post_name].css where "post_type" is the custom post type or just 'post' for regular posts, and "post_name" is the slug of the post.

* To activate stylesheets just create css files with the following naming:
ie.css (covers all IE versions), ie7.css (covers IE 7 and below), ie6.css (covers IE 6 and below).

== Frequently Asked Questions ==

= How do I activate IE stylesheets? =
To activate stylesheets just create css files with the following naming:
ie.css (covers all IE versions), ie7.css (covers IE 7 and below), ie6.css (covers IE 6 and below).

= How do I get Stylesheet Per Page to check for the files first before trying to include them? =

Easy, just tick the option under the Stylesheet Per Page admin options under found under the Settings menu.

== Screenshots ==

N/A

== Upgrade Notice ==

N/A