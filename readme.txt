=== BMoney Custom Meta Boxes ===
Contributors: briandichiara
Donate link: https://www.paypal.com/cgi-bin/webscr?&cmd=_xclick&business=briandichiara@gmail.com&currency_code=USD&amount=&item_name=BMoney%20Custom%20Metaboxes
Tags: trunk
Requires at least: 3.5
Tested up to: 3.5.2
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allows developers to easily add meta boxes with custom fields into their posts or pages. Requires WordPress 3.5+ and is updated frequently.

== Description ==

Documentation can be found here:

[https://github.com/solepixel/bmoney-custom-metaboxes/wiki](https://github.com/solepixel/bmoney-custom-metaboxes/wiki)

== Installation ==

1. Upload `bmoney-custom-metaboxes` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the bmcm_metaboxes filter to your theme or plugin using the instructions provided here: [Getting Started](https://github.com/solepixel/bmoney-custom-metaboxes/wiki/Getting-Started)

== Frequently asked questions ==

Coming Soon...

== Screenshots ==

1. http://plugins.briandichiara.com/bmoney-custom-metaboxes/screenshot1.jpg
2. http://plugins.briandichiara.com/bmoney-custom-metaboxes/screenshot2.jpg

== Changelog ==

= 1.536 =
* Added new parameter "display" to metabox. Accepts boolean
* Added new field type "code" and supports HTML
* Added Section break heading
* Adjusted priorities for loading metaboxes to optimize theme support
* Bug fix when removing all gallery metabox items

= 1.535 =
* Fixed a bug with enqueue media causing problems with featured image dialog

= 1.534 =
* Consistency of before/after/description in field outputs

= 1.533 =
* Adjustments to media javascript and when it's called.

= 1.532 =
* Minor bug in media.js fixed.
* Failed at version numbering. Will figure out a fix soon.
 
= 1.531 =
* Fixed an issue with the 1.53 update not working

= 1.53 =
* Any field parameter now accepts a callback. (must be declared as callback)
* Added gallery field type
* Fixed an issue with single checkboxes
* Updated Readme
* Minor adjustments/code cleanup

= 1.52 =
* Added Number field type
* Enhancements to repeatable field types
* Minor adjustments/code cleanup

= 1.51 =
* Added URL field type

= 1.5 =
* Many bug fixes
* CSS changes
* Added meta box class support
* Added "multi" field with sorting
* Added tabs support
* Rewrote Media/Upload Javascript code with more usability
* Additional CSS classes on each item

= 1.4 =
* Better Upload Field Interface
* Slider field type (jquery-ui)
* Taxonomy field type
* CSS Adjustments
* PHP Notice fix

= 1.3 =
* Added date field support

= 1.2 =
* Fixed bug with Media Uploader

= 1.1 =
* Added documentation
* More supported field types
* Added some filters for validating user input
* Action priority adjustment
* Minor bug fixes

= 1.0 =
* Initial build

== Upgrade notice ==

Nothing of note.