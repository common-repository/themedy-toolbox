=== Themedy Toolbox ===
Contributors: themedy, mahodder, matthodder
Tags: shortcodes, themedy, genesis, thesis
Requires at least: 4.9
Tested up to: 6.6.2
Stable tag: 1.0.16
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The Themedy Toolbox extends functionality of our Themedy Themes. It provides a easy to use shortcodes plugin to easily add buttons and more.

== Description ==

Themedy Toolbox is a very powerful, yet easy to use shortcodes plugin. Shortcodes can be generated via the new Themedy button in your editor in the Visual tab of the WordPress editor.

You can add buttons, columns, social icons and links, accordions, toggles, tabs, alert boxes, pull quotes, responsive Youtube and Vimeo videos, and maps to your site by simply filling out a few options and clicking the Insert Shortcode button.

Please note that this plugin will work outside our <a href="https://themedy.com">Themedy themes</a>, but we will not provide support for any issues with other themes.

== Installation ==

1. Upload the `themedy-toolbox` folder to your to the `/wp-content/plugins/` directory or alternatively upload the themedy-toolbox.zip via the plugin page of WordPress by clicking 'Add New' and select the zip from your local computer.
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to the page/post editor and you should see a new button on your toolbar (the icon is a grey button with our /// logo mark)
4. On the popup that appears, choose which shortcode you would like to add from the left and then fill out the options on the right.
5. Click the Insert Shortcode button to add the shortcode to the editor.
6. To enable the Custom CSS module visit Tools -> Themedy Toolbox to enable it.

== Screenshots ==

1. Here's a screenshot of it in action

== Changelog ==

= 1.0.16 =
* Further input sanitization for button.

= 1.0.15 =
* Add input sanitization for shortcodes (Thanks @Francesco Carlucci)

= 1.0.14 =
* Update FontAwesome to 4.7.0
* Fix missing replicate menu option on multsite installs

= 1.0.13 =
* Fix WP-CLI Errors

= 1.0.12 =
* Removed Google Map options from front end, use a plugin like https://wordpress.org/plugins/ank-google-map/ instead.

= 1.0.11 =
* Remove video option from shortcode builder, you can use WordPress's default embed tools for videos. Old video / manually created video shortcodes will continue to function.

= 1.0.10 =
* Add more Google Map options to the themedy map shortcode, minZoom, maxZoom, scrollwheel, scaleControl, draggable, zoomControl, fullscreenControl.

= 1.0.9 =
* Fix JS Warning
* Upgrade FontAwesome to 4.6.1
* Tools -> Themedy Toolbox has two new options to unload the bundled FontAwesone / Fontello fonts if you are not using them. 
* Remove bundled FontAwesome files as they are loaded from MaxCDN

= 1.0.8 =
* Fix potentional conflict with Site Orgin CSS plugin

= 1.0.7 =
* Fix plugin header error

= 1.0.6 =
* Add backwards compatibility for old Font Awesome icons

= 1.0.5 =
* Load YouTube / Vimeo via HTTP / HTTPS depending on users site automatically.
* Fix conflict with Contact Forms 7 plugin
* Update Custom CSS Module
* Upgrade Font Awesome to 4.3
* Add all font awesome icons to select icon screen (now 519 choices!)
* Add the ability to use Font Awesome attributes (like spin icon)
* Add note about using double quotes in button labels
* Misc fixes

= 1.0.4 =
* Load visual editor icon on post / pages / custom post types only to reduce conflicts with visual editors with other plugins.

= 1.0.3 =
* Fix tinymce ref error

= 1.0.2 =
* Fixes for renamed wp-content directory

= 1.0.1 =
* Add compatibility mode for old Themedy Visual Designer shortcodes
* Add Themedy Replicate script to replicate demo site setup
* Add Custom CSS module

= 1.0 =
* First release.

== Upgrade Notice ==

Fork: Built on top of the wonderful Simnor Shortcodes
