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

1. Back to Top
2. Before / After Image
3. Burger Trigger
4. Content Switcher
5. Content Timeline
6. Dynamic Chart
7. Dynamic Lightbox
8. Dynamic Table
9. Evergreen Countdown
10. Fluent Form
11. Header Notification Bar
12. Header Row
13. Header Search
14. Image Hotspots
15. Interactive Cursor
16. Lottie
17. Modal (template), Modal
18. Offcanvas (template), Offcanvas
19. Popover / Tooltips
20. Pro Accordion
21. Pro Alert
22. Pro Slider, Pro Slider Control, Pro Slider Gallery
23. Reading Progress Bar
24. Read More / Less
25. Shortcode Wrapper
26. Site Breadcrumbs
27. Slide Menu
28. Social Share
29. Star Rating
30. Table of Contents
31. Toggle Switch

Current features:

1. Dynamic Tags
2. Floating Effect
3. Header Extras
4. Parallax Scroll
5. Tilt Hover
6. X-Ray Mode
7. Adjacent Posts query loop extension
8. Related Posts query loop extension

== Installation ==

1. Click on the download link in your purchase confirmation email if you have not already downloaded it after your purchase.

2. Download the plugin's zip file.

3. Go to Plugins > Add New in your WordPress admin. Click "Add New" button, then "Upload Plugin" button, then "Choose File", browse to and select the plugin's zip file.

4. Activate the plugin.

5. Enter the license key and activate your plugin license at Bricks → BricksExtras → License.

Valid license key should be entered for the plugin to function and to receive automatic updates.

== Changelog ==

= 1.2.6 ( May 10, 2023 ) =
* [Evergreen Countdown] - New element for evergreen countdowns.
* [Dynamic Chart] - New query loop option for dynamically adding new data points.
* [Header Search] - Added "expand" search type.
* [Pro Accordion] - Added an option to auto-add FAQ schema to all accordion items.
* [Notification Bar] - The "show again until user clicks dismiss" now allows for showing again after a set time.
* [Pro Slider Gallery] - Added an option to change the size of image when adding links (for use with Dynamic Lightbox).
* [Hotspots] - Markers can now be links.
* [Slide Menu] - Added customizable aria-label for dropdown arrows.
* [Table of Contents] - Added "conditional display" option to remove table if no headings found.
* [X-Ray] - Moved position of icon and can now be enabled/disabled from plugin settings page.
* [Dynamic Lightbox] - Plyr assets no longer being fetched from the CDN.
* [General] - Added support for using elements inside content filtered by Piotnet Grid's facets.
* [General] - Some minor UI changes ready for Bricks v1.8.
* [Lottie] - Fixed an issue with "hover" trigger where child elements would restart animation.
* [Pro Slider] - Fixed an issue where styling wasn't correct inside builder if was inside Bricks' template element.
* [Table of Contents] - Fixed an issue where adding non-numeric values in offset wasn't accepted.
* [Modal] - Fixed an issue where very bottom of modal sometimes wasn't visible on mobile devices.

= 1.2.5 ( Apr 12, 2023 ) =
* [Adjacent Posts] - New Query Loop extension for building custom prev/next post layout.
* [Related Posts] - New Query Loop extension for displaying related posts within specific taxonomies.
* [General] - Support added for JetSmartFilters for using the elements inside loops being filtered (Modal, Lightbox, OffCanvas, Pro Accordion, Social Share, Read More, Pro Slider & Popover).
* [Dynamic Lightbox] - Now supports being inside nested query loops.
* [Pro Slider] - Now supports being inside nested query loops (including syncing and controls).
* [Pro Slider] - Added "adaptive height" option to allow slider to adapt to current active slide height.
* [Pro Slider] - Added support for re-triggering "big" inner animations - fadeInUpBig, fadeInDownBig etc. from Bricks' interactions.
* [Pro Slider Gallery] - Gallery images can now be linked to Bricks v1.7.2+ Lightbox.
* [Site breadcrumbs] - Added more controls over output - excluding specific post/product categories or disabling categories.
* [Dynamic Chart] - New horizontal option for bar/line charts. (labels up the Y-axis, values along the X-axis).
* [Dynamic Chart] - Now allows for adding units before or after the values.
* [Dynamic Chart] - Added option to add tooltips to charts.
* [Dynamic Chart] - Fixed an issue where using large 7+ digit numbers (that resemble telephone numbers) as values wouldn't plot correctly if viewed on iOS.
* [Header Extras] - Fixed Header Extras tab sometimes not appearing inside page settings.
* [Header Search] - Fixed an issue with icons not changing size/colors if using custom SVGs.
* [Dynamic Table] - Fixed an issue with "if no rows found" text not being customizable when pagination is disabled.

= 1.2.4 ( Mar 09, 2023 ) =
* [Social Share] - New element for adding social share buttons.
* [Site Breadcrumbs] - New element for adding site-wide breadcrumbs.
* [Modal] - Now supports being inside nested query loops (up to 3 levels deep).
* [OffCanvas] - Now supports being inside nested query loops (up to 3 levels deep)
* [OffCanvas] - Added an option to fade in in addition to slide in for the Transition type.
* [Pro Slider] - Added Splide lazy loading option.
* [Pro Slider Gallery] - Added a setting to enable slider lazy loading for all gallery images (either Bricks or Splide lazy load).
* [Pro Slider Gallery] - Added a setting to enable/disable SRCSET on images.
* [General] - Added out-of-the-box support for WP Grid Builder's facets. Modal, OffCanvas, Pro Accordion, Pro Slider, Dynamic Lightbox, Social Share, Read More, Popover (for being used inside query loops when building filtered).
* [Tilt Effect] - Scale now accepts decimal values ( 1.5 = 150%).
* [Pro Accordion] - Added an option to change the HTML tag on the wrapper (for doing ul>li etc).
* [Dynamic Table] - Added an option to set a fixed height for a scrollable table (header & footer remain fixed).
* [Dynamic Lightbox] - Added an option to change UI color for video player in manual link mode.
* [Dynamic Lightbox] - Can now use class added to headings or images directly for link selectors (before you may have needed to use `.my-class a` due to Bricks not adding the classes to the links, this is done automatically now).
* [Content Timeline] - Reworked the logic for the line, for more accurate positioning.
* [Content Timeline] - Added a `—x-timeline-progress` CSS variable that changes value from 1 - 100 as the timeline progresses (can be used to change styles on any inner elements based on timeline position).
* [Interactive Cursor] - Added an option to change border-radius of ball/trails.
* [X-Ray] - Slightly darker outlines by default for better visibility (users can change `—x-xray-color` CSS variable from Bricks CSS settings if wishing to change color).
* [Modal] - Fixed the issue with close button not triggering if multiple modals are open simultaneously.
* [Slide Menu] - Fixed the issue of not correctly outputting menu when populating `menu slug` using dynamic tags.

= 1.2.3 ( Jan 26, 2023 ) =
* [Read More] - Accessibility improvement (aria-expanded label).
* [Dynamic Lightbox] - Fixed specificity issue causing width to appear incorrectly in builder.
* [General] - Fixed an issue with Bricks v1.6.2 where some style settings were hidden if class selected.

= 1.2.2 ( Jan 23, 2023 ) =
* [Content Timeline] - New element for creating content timeline layouts.
* [X-Ray Mode] - In-builder option for quickly viewing layout structures visually.
* [Dynamic Lightbox] - Added "gallery" option to lightbox content for pulling in galleries into single lightbox.
* [Dynamic Lightbox] - Added better support for WPGB infinite scroll (see support FAQ in docs).
* [Image hotspots] - Added an option to add custom alt text to image.
* [Dynamic Table] - No longer outputs "NaN" if column set to numbers and cell has no value.
* [Dynamic Lightbox] - Fixed the issue with UI styles styling both close buttons and navigation together.
* [Fluent Form] - Updated some selectors to match Fluent Forms flex-box column gaps.
* [Header Extras] - Slight CSS change to avoid small jump if header set to be sticky immediately after scrolling.
* [General] - Removed various default CSS settings for better support for mobile-first.

= 1.2.1 ( Jan 04, 2023 ) =
* [Pro Slider / Gallery] - Added an option to change the slide list HTML tag (for changing to <ul> lists etc. if needed).
* [Interactive Cursor] - Fixed the issue where cursor wasn't visible on some desktop devices that have touchscreen.
* [Header Extras] - Fixed breakpoint issue causing warning with some older versions of PHP.

= 1.2.0 ( Jan 03, 2023 ) =
* [Header Extras] - New features added to Bricks' header template - (overlay headers, sticky on scroll, hide header after scrolling X added to any breakpoint globally, or per page/template).
* [Header Row] - New element for more easily building headers in bricks (supports conditionally appearing in overlay or sticky headers, change styles when sticky etc).
* [Pro Slider] - Added an option to change all aria-labels for pagination, nav arrows etc.
* [Pro Slider] - Added a "conditional slider" option to disable slider if not enough slides to fill the slider viewport.
* [Pro Slider] - Added an option to set horizontal flex alignment if there are not enough slides.
* [Pro Slider] - Added an option to delay the first staggered animation.
* [Pro Slider] - "Focus" setting can now be changed per breakpoint.
* [Toggle Switch] - Query loop can now be used to populate "multiple labels".
* [Dynamic Table] - New "Stackable table" option for stacking columns on mobile.
* [Burger Trigger] - Now possible to hide the button text at different breakpoints.
* [Interactive Cursor] - Cursor will now automatically shrink if moving position over an iFrame.
* [Interactive Cursor] - Fixed the issue with cursor not reacting to readmore/less buttons.
* [General] - Fixed compatibility issue with OffCanvas/Modal template dropdown with Bricks v1.6+.
* [Dynamic Lightbox] - Fixed an issue with overflow resetting to "auto" on mobile.
* [Table of Contents] - Fixed an issue where collapse depth wouldn't apply.

= 1.1.9 ( Nov 23, 2022 ) =
* [Pro Accordion] - New element for building nestable and accessible accordions.
* [Table of Contents] - Now supports different open/close positions at different screen widths.
* [Pro Slider] - Added support for Bricks v.1.5.6 interactions (for triggering fadein type animations on elements inside slides).
* [Pro Slider] - Added overflow setting to allow slides to go outside of slide track.
* [Dynamic Table] - Added an option to change "no records found" text if there are no rows.
* [Toggle Switch] - Added an option to disable labels and just use the toggle switch.

= 1.1.8 ( Nov 15, 2022 ) =
* [Toggle Switch] - Added label layout controls to allow for stacking labels on mobile.
* [Toggle Switch / Switcher] - Accessibility improvement - tablist/tabpanel & ARIA labels added when using multiple labels like tabs.
* [Back to Top] - Fixed BricksProps CSS overriding the button SVG.
* [Back to Top] - Fixed background circle being slightly visible over progress when on darker backgrounds.
* [Read More] - Fixed read more not always opening when inside query loops.
* [Dynamic Table] - Fixed an issue with columns not being resizable.

= 1.1.7 ( Nov 10, 2022 ) =
* [Back to Top] - New element for creating animated back to top buttons.
* [Interactive Cursor] - New element for adding cursors that interact with other elements.
* [Popovers/Tooltips] - New element for adding popovers or tooltips to elements.
* [Modal] - Modals using "click" as trigger can now be used inside query loops.
* [Interactive features] - Now added to most native elements.
* [Fluent Form] - Added "progress steps" to progress bar style controls.
* [Lightbox] - Fixed the issue where CSS grid inside lightbox content wouldn't display correctly inside the builder.

= 1.1.6 ( Oct 30, 2022 ) =
* [Pro Slider] Fixed a bug with the counter being blank unless navigated.

= 1.1.5 ( Oct 28, 2022 ) =
* [Pro Slider Control] - Added an option to create custom navigation arrows/buttons for Slider.
* [Pro Slider Gallery] - Added an ability to link gallery images to Bricks' Lightbox.
* [Dynamic Table] - Added "static" option - add rows/cells manually without query loop.
* [Dynamic Table] - Alternative row styles for background / text colors.
* [Modal] - Added "hashlink to close" option.
* [Dynamic Lightbox] - Added "hashlink to close" option.
* [Dynamic Lightbox] - Added "manual links" option to populate content dynamically from links. Supports images/videos/iFrames.
* [Modal] - Fixed the issue with exit intent trigger not triggering in Safari.

= 1.1.4 ( Oct 21, 2022 ) =
* [Reading Progress Bar] - New element for adding reading progress bars based on scroll position of containers, or of the whole page.
* [Before / After Image] - New element for adding accessible before/after image sliders.
* [Table of Contents] - Added option to automatically use heading text for the anchor links.
* [Table of Contents] - Better support for Bricks' "Add Element ID & class as needed" setting (no longer required to add an ID to the element).
* [Modal] - Added an option to disable "auto focus on first focusable element" when opened.
* [Dynamic Table] - Added options to change/translate all text inside the pagination summary.
* [Dynamic Table] - Bumped to the latest GridJS version.
* [Dynamic Table] - Added an option to customize the number of pagination buttons.
* [Dynamic Table] - Fixed the issue with certain characters ( åäö ) not displaying correctly inside the builder.
* [Dynamic Lightbox] - Removed the default 900px max-width restriction on the container.

= 1.1.3 ( Oct 13, 2022 ) =
* [Pro Slider] - Added option to change "focus" (was originally set to "center" as default).
* [Pro Slider] - Added controls for navigation by mouse wheel.
* [Pro Slider] - Reduced default slide padding and now no default padding if using code element to add custom slides.
* [Image Hotspots] - Better style control over marker icon.

= 1.1.2 ( Oct 07, 2022 ) =
* [Pro Slider] - New element for building sliders/carousels.
* [Pro Slider Control] - New element for adding extras to sliders: Progress bars, counters, autoplay play/pause button.
* [Pro Slider Gallery] - New element for allowing to use the Pro Slider for dynamic galleries ex.: use ACF Gallery field or Meta Box Image Advanced or Media Library as the source of slide images.
* [Dynamic Chart] - Added "pie / doughnut" chart type.
* [Dynamic Lightbox] - Added easy way to add custom close buttons - "data-x-lightbox-close" attribute.
* [Burger Trigger] - Added option to add button text.
* [Table of Contents] - Smooth scrolling can now be disabled.
* [Modal] - Clicking backdrop to close and ESC key to close now optional.
* [Read More / Less] - Fixed issue where read more wouldn't size correctly when inside a modal.
* [OffCanvas] - Fixed issue where Safari that would cause lazy loaded images not to render.
* [Developer docs] - gLightbox instance now exposed, so lightbox can be controlled programmatically easily.

= 1.1.1 ( Sep 14, 2022 ) =
* [Header Search] - Fixed an issue with return (enter) key in Safari causing the search form to close.
* [Fluent Forms] - Switched over some control types to allow for CSS variables.
* [Modal] - When using custom link for closing, browser will now follow the link after closing the modal.
* [General] - Addressed an issue that was causing styling not to be applied when elements were being pulled from other templates inside of templates (ex.: the "template" element or "post content" element).
* [Modal/OffCanvas] - Fixed issue with "template" versions that would cause the "hide in builder" setting to reset sometimes when moving the elements in the structure panel.

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
* [Table of Contents] - Added ability to have "closed on page load".
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
