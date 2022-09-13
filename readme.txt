=== BricksExtras ===
Contributors: David Browne, Sridhar Katakam
Tags: bricks, bricks builder
Requires at least: 4.7
Tested up to: 10.0.0
Requires PHP: 5.6
Stable tag: trunk
License: GPL3
License URI: http://www.gnu.org/licenses/gpl-3.0.txt

Lightweight component library for Oxygen Builder

== Description ==

Current elements:

1. Burger Trigger
2. Content Switcher
3. Dynamic Chart
4. Dynamic Lightbox
5. Dynamic Table
6. Fluent Form
7. Header Notification Bar
8. Header Search
9. Image Hotspots
10. Lottie
11. Modal (template)
12. Modal
13. Offcanvas (template)
14. Offcanvas
15. Pro Alert
16. Read More/Less
17. Shortcode Wrapper
18. Slide Menu
19. Star Rating
20. Table of Contents
21. Toggle Switch

Current features:

1. Dynamic Tags
2. Floating Effect
3. Parallax Scroll
4. Tilt Hover

== Installation ==

1. Click on the download link in your purchase confirmation email if you have not already downloaded it after your purchase.

2. Download the plugin's zip file.

3. Go to Plugins > Add New in your WordPress admin. Click "Add New" button, then "Upload Plugin" button, then "Choose File", browse to and select the plugin's zip file.

4. Activate the plugin.

5. Enter the license key and activate your plugin license at Bricks → BricksExtras → License.

Valid license key should be entered for the plugin to function and to receive automatic updates.

== Changelog ==

= 1.1 ( Sep 13, 2022 ) =
* [General] - Fixed an issue where inline CSS wasn't correctly output on some installs.

= 1.0.9 ( Sep 12, 2022 ) =
* [Header Search] - New element for creating different types of header searches.
* [Lottie] - New element for adding interactive Lottie animations.
* [Toggle Switch] - New element for adding toggle switches (supports multiple toggles).
* [Content Switcher] - New element for switching multiple versions of any content.
* [Lightbox] - Added iFrame option for lightbox content.
* [Dynamic Table] - Now supports being inside nested query loops.
* [Image Hotspots] - Now supports being inside nested query loops.
* [Dynamic Chart] - Now supports being inside nested query loops.
* [Dynamic Chart] - If no data found, will now output nothing, instead of an empty chart.
* [Modal] - Performance improvement (prevent images/video loading until modal opened).
* [Star rating] - Added "gap" setting for stars.
* [Lightbox] - Fixed lazy loading images not always showing in Safari.
* [General] - Removed all slider controls to replace with number controls (to align with Bricks v1.5.1 removing the units dropdown).
* [General] - Minor CSS specificity changes for Bricks v1.5.1.
* [General] - Performance improvement for element CSS to prevent FOUC (also now respects user preferred CSS loading method as set in Bricks settings - inline or external files)

= 1.0.8 ( Aug 23, 2022 ) =
* [Dynamic tag - Loop Index] - New tag "x_loop_index" for count inside query loops (with offset filter).
* [Interactive features] - Now available for the div and block elements.
* [Modal, Lightbox] - Added flex layout controls to main "content" settings for easier control over the inner content layout.
* [Table of Contents] - Now supports including headings found inside separate containers.
* [Burger Trigger] - Added "active line color" control.

= 1.0.7 ( Aug 17, 2022 ) =
* [Modal] - Added option to disable scroll when open.
* [Star Rating] - Improved logic for star rating to avoid issue when using empty values from dynamic data.

= 1.0.6 ( Aug 16, 2022 ) =
* [Dynamic Lightbox] - New element for being able to popup dynamic content from inside post loops.
* [Offcanvas, Modal] - New nestable elements to replace older versions (previous "template" versions still available for backward compatibility or if you prefer to use templates).
* [Read More / Less, Header Notification Bar, Pro Alert, Shortcode Wrapper, Pro Alert] - now supports nesting elements.
* [Dynamic Tags] - Now supports being used inside AJAX added content (ex.: when using inside content dynamically added using WP Grid Builder's filters).
* [Star Rating] - Now allows for any number of total stars.
* [Slide Menu] - Now allows for elements being inside, either above/below the menu items.
* [Table of contents] - Added ability to have "closed on page load".
* [Burger Trigger] - Better default CSS to prevent bottom gap if changing the display setting.
* [Fluent Form] - Fixed issue with dynamic data for Form ID not displaying form correctly.
* [Fluent Form] - Fixed CSS specificity issues where styles added via class were being overridden by defaults.
* [General] - A few small CSS fixes to account for Bricks v1.5's new default CSS.
* [General] - Added support for Bricks' experimental feature "Add Element ID & class only as needed" (elements that need the element ID to function, will have an ID added automatically if there isn't one).

= 1.0.5 ( Jul 31, 2022 ) =
* Fixed a fatal error due to change in the attributes of bricks/element/render_attributes filter.

= 1.0.4 ( Jul 05, 2022 ) =
* [Dynamic Table] - Added option to specify column data type as "number", to allow for sorting by numbers.
* [Dynamic Table] - Now allows for HTML tags from WYSIWYG fields inside the cells.
* [Slide Menu] - Added "text indent" setting for indenting nested sub menu items.
* [Image Hotspots] - Fixed the issue where marker background style wasn't visible.
* [Table of Contents] - Fixed the issue with unique ID setting causing table not to show.

= 1.0.3 ( Jun 24, 2022 ) =
* [Parallax] - Improved the parallax scroll feature, new "default" setting for all devices.
* [Star Rating] - Small improvement for the default CSS.

= 1.0.2 ( Jun 21, 2022 ) =
* [Dynamic Chart] - New element for displaying line/bar charts using dynamic data.
* [Read More/Less] - New element for expanding/revealing content.
* [Star Rating] - New element for displaying star ratings (for testimonials, reviews etc).
* [Dynamic Data Tags] - Added multiple new tags for use inside Bricks' dynamic data options.
* [Dynamic Table] - Added an option to make columns resizable.
* [Dynamic Table] - Added an option to prevent column text wrapping.
* [Dynamic Table] - Added cell overflow control.
* [Dynamic Table] - Added an option to specify a min-width for each column.
* [OffCanvas] - Added an option to prevent site scrolling when open.
* [Modal & OffCanvas] - iFrame embeds, videos and forms inside will now be automatically reset/stopped when closed.

= 1.0.1 ( Jun 08, 2022 ) =
* [Image Hotspots] - Added the ability to control animation for popovers.
* [Fluent Form] - Fixed the issue with box-shadow not being applied.
* [General] - Fixed an error when using WP Toolkit searching for updates.
* [General] - Fixed an error if Bricks theme is deactivated with BricksExtras still active.

= 1.0.0 ( Jun 06, 2022 ) =
* Initial release.
