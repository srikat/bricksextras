=== BricksExtras ===
Contributors: David Browne, Sridhar Katakam
Tags: bricks, bricks builder
Requires at least: 6.4.3
Tested up to: 10.0.0
Requires PHP: 8.0
Stable tag: trunk
License: GPL3
License URI: http://www.gnu.org/licenses/gpl-3.0.txt

Lightweight component library for Bricks Builder

== Description ==

Current elements:

1. Back to Top
2. Before / After Image
3. Burger Trigger
4. Content Switcher
5. Content Timeline
6. Copy To Clipboard
7. Dynamic Chart
8. Dynamic Lightbox
9. Dynamic Table
10. Evergreen Countdown
11. Favorite Button
12. Fluent Form
13. Header Notification Bar
14. Header Row
15. Header Search
16. Image Hotspots
17. Interactive Cursor
18. Lottie
19. Media Player, Media Player Audio, Media Control, Media Playlist
20. Modal (template), Modal
21. Nestable Table
22. Offcanvas (template), Offcanvas
23. Page Tour and Page Tour Step
24. Panorama Viewer and Panorama Scene
25. Popover / Tooltips
26. Pro Accordion
27. Pro Alert
28. Pro Slider, Pro Slider Control, Pro Slider Gallery
29. Pro Tabs
30. QR Code
31. Reading Progress Bar
32. Read More / Less
33. Shortcode Wrapper
34. Site Breadcrumbs
35. Slide Menu
36. Social Share
37. Star Rating
38. Table of Contents
39. Toggle Switch
40. WPGB Facet Styler
41. WS Form

Current features:

1. Extra Conditions - General, Membership, WooCommerce
2. Dynamic Tags
3. Floating Effect
4. Header Extras
5. Parallax Scroll
6. Tilt Hover
7. X-Ray Mode
8. Adjacent Posts query loop extension
9. Related Posts query loop extension
10. Favorites / Wishlist query loop extension
11. Gallery (ACF Gallery field, Meta Box Image Advanced field etc.) query loop extension
12. WP Menu query loop extension
13. Helper functions to allow control elements dynamically via interactions (see interactions tab in docs)

== Installation ==

1. Click on the download link in your purchase confirmation email if you have not already downloaded it after your purchase.

2. Download the plugin's zip file.

3. Go to Plugins > Add New in your WordPress admin. Click "Add New" button, then "Upload Plugin" button, then "Choose File", browse to and select the plugin's zip file.

4. Activate the plugin.

5. Enter the license key and activate your plugin license at Bricks → BricksExtras → License.

Valid license key should be entered for the plugin to function and to receive automatic updates.

== Changelog ==
Changelog page: https://bricksextras.com/changelog/

= 1.6.0 ( Nov 18, 2025 ) =
* [Media Player Audio] - New control types will now display conditionally based on current media settings.
* [Media Player Audio] - Replaced attribute option with new UI for adding download options.
* [Media Player Control] - Fixed the missing "replay icon" settings on default UI option.

= 1.5.9 ( Nov 17, 2025 ) =

* [Media Player Audio] - Added two new control types: "artist" and "download".
* [Dynamic Chart] - Can now customize the chart's canvas aspect-ratio.
* [Table of Contents] - Improved heading ID generation with language-aware transliteration (replacing umlaut characters etc.).
* [Media Player] - In-builder performance improvements.
* [Dynamic Lightbox] - Fixed issue which could cause multiple lightboxes to trigger with Bricks' filter elements.
* [Before After Image] - Fixed issue where input background-color visible in Firefox.

= 1.5.8 ( Nov 11, 2025 ) =
* [Panaroma Viewer / Scenes] - Stable version. Improved workflow & performance in the builder and added loading spinner and nav instructions overlay.
* [Social Share] - Added option to set separate custom image and description for Pinterest pinning.
* [Media Player Control] - Added option to show remaining time in time control.
* [Dynamic Lightbox] - Fixed issue where Lightbox 'iframe' wouldn't work when both inside of a condition and inside infinite scrolled AJAX content.
* [Media Player Audio] - Fixed an issue where title wouldn't display if populating with Bricks' query_api dynamic tag.
* [Media Player Audio] - Fixed an issue where audio waveform could flicker when changing audio sources via playlist.
* [Media Player] - Fixed poster-image control inside default UI not picking up poster changes.

= 1.5.7 ( Oct 27, 2025 ) =
* [Page Tours] (stable) - Out of beta, slight changes to behavior and fixes.
* [Panorama Viewer] (beta) - New element for navigating panorama images with hotspots, and creating multi-scene virtual tours.
* [Panorama Scene] (beta) - New element for creating individual panorama scenes with hotspots.
* [FluentCart Conditions] - New element conditions based on user purchases and current subscription status with FluentCart products.
* [General Conditions] - Added "sequence pattern" to loop item condition (for allowing odd/even, 2n+1 type conditions inside query loops).
* [Media Player] - Added auto-detect language option for captions (for making page's current language the default caption language, if it exists, when toggled on).
* [Dynamic Table] - Added an option to choose which column controls the initial sort order.
* [Pro Accordion] - Now allows custom HTML tags on the main wrapper element.
* [Pro Accordion] - Fixed 'collapse' event not triggering if sibling item opened.
* [Site Breadcrumbs] - Fixed the issue where 'exclude product category' not excluding some categories for a large number of categories.

= 1.5.6 ( Sep 18, 2025 ) =
* [QR Code] - New element for generating custom QR code designs based on dynamic data.
* [Page Tour & Steps] (beta) New nestable elements for creating a sequence of popovers to guide users through steps.
* [WP Menu Query] - Added an option to narrow down which items are output - top level items, or sub items of specific menu item.
* [Media Player Audio] - Waveform feature now out of beta (fixed a rare issue which could cause longer audio to fall out of sync with the waveform).
* [Pro tabs] - Added an option to prevent closing sibling items for mobile accordion for having multiple items open.
* [Media Player] - Better RTL support for all controls.
* [Media Player] - Dynamic tags can now be used within URLs (not just as the full URL).
* [Pro Slider] - Added an option to auto-pause media player when sliders moves to new slide (enabled by default).
* [Modal] - The auto-refresh of forms inside modal on close now optional (for better compatibility with BricksForge's searchable select dropdowns).
* [Social Share] - Can now add custom data attributes to individual share links.
* [Toggle Switch] - Added control over keyboard arrow navigation behavior for switching tabs or moving focus.
* [Media Player] - Fixed an issue where closing fullscreen could cause page scroll.
* [Media Player] - Fixed an issue where poster image wouldn't show on Android lock screen if media player had custom title.
* [Favorites] - Fixed an issue where posts could be removed from favorites list when updated.

= 1.5.5 ( Aug 01, 2025 ) =
* [General] - Fixed issue that could cause BricksExtras' elements not to register in Bricks v2 (Ex.: when Lazy Blocks plugin active).
* [Media Player] - New Start Time URL Param option (for creating video timestamp links).
* [Media Player] - Can now customize all the player keyboard shortcuts.
* [Media Player] - "Replayed" and "Media Switched" interaction triggers added.
* [Media Player Control] - Better keyboard behavior for waveform and settings toggles when using custom UI.
* [Media Player Control] - Added missing label/tooltip settings from Chapter Menu control type.
* [WooCommerce Conditions] - "User just purchased product condition" now allows for use on custom thank you pages.
* [WPGB styler] - Fixed issue where WP Grid Builder defaults could override general style settings for select dropdowns.

= 1.5.4.1 ( Jul 29, 2025 ) =
* [Media Player Audio] - Fixed media player stylesheet file slug.

= 1.5.4 ( Jul 29, 2025 ) =
* [General] - Support across all elements for Bricks' components feature.
* [General] - Support using all elements inside nested components.
* [General] - Added "component scope" option to all elements that control/target other elements.
* [Media Player] - New nestable element for building custom video players.
* [Media Player Audio] - New nestable element for building custom audio players.
* [Media Control] - New controller element for adding control buttons to the media players.
* [Media Playlist] - New controller element for adding playlist items for the media players.
* [WP Menu Query] - Added support for custom field dynamic tags from menu items inside menu loop.
* [WP Menu Query] - New tag for changing link targets as per individual menu item settings.
* [Slide Menu] - Added option to replace sub menus with Bricks' mega menu template for top menu items.
* [Dynamic Table] - New interaction for allowing users to download table data as a CSV file.
* [Pro Tabs] - New interactions for moving to prev/next tabs.
* [WooCommerce Conditions] - Added "User just purchased product" (for on Thank You pages)
* [General] - Adjusted default CSS where needed for when Bricks' cascade layer system enabled.
* [Dynamic Chart] - Chart now supports using CSS variables for color styles.
* [Before/After Image] - Better control over touch area for mobile.
* [Modal] - Improved focus behavior for when Auto focus on first focusable element has been disabled.
* [Dynamic Lightbox] - Added DOM lazy loading option for content inside lightbox (performance improvement).
* [Header Search] - Added option to change Action URL and to add additional parameter settings within the search form.
* [Header Search] - Added option to force keyboard open on reveal for iOS.
* [Dynamic Table] - Added option to adjust scope attribute for the table header per column.
* [Dynamic Table] - Default sorting is now case-insensitive.
* [Image Hotspots] - Marker titles now support including HTML tags.
* [Favorites] - Count dynamic tags now allows counting multiple lists.
* [Favorites] - Favorites now saved as post meta.
* [Favorites] - Better support for page caching.
* [Social Share] - Added Bluesky and Threads to share buttons services.
* [Social Share] - Tooltip will now reflect custom label if one has been added.
* [Shortcode Wrapper] - Now allows for using dynamic tags for the shortcodes.
* [Pro Slider Control] - Can now be used to play/pause an autoscrolling slider.
* [Popover] - Allow to be used with Bricks' infinite scroll option.
* [WSForms] - Changed style selectors conditionally if using WS Form's own built-in form styler.
* [Pro Slider] - Fixed issue where fade mode wouldn't show slides if RTL.
* [Pro Slider] - Fixed issue where drag couldn't be changed per breakpoint.
* [Pro Slider Control] - Fixed issue where the intersection option could cause autoplay button to require two clicks to play.
* [Header Extras] - Fixed issue where setting sticky header wouldn’t override template settings.
* [Pro Tabs] - Fixed issue where moving tabs could close Bricks' mega menu dropdown to close.
* [Pro Tabs] - Fixed issue that could cause browser to scroll if tabs placed below tab content.

= 1.5.3 ( Nov 08, 2024 ) =
* [Pro Countdown] - Added support for city/county timezone format.
* [Toggle Switch] - Fixed an issue from v1.5.2 preventing toggle to work in some cases.
* [General] - Added little 'x' next to all elements in builder to help distinguish between native elements when searching. Screenshot: https://d.pr/i/hqhtiS.

= 1.5.2 ( Nov 05, 2024 ) =
Highlights: https://bricksextras.com/whats-new-bricksextras-v1-5-2/

* [Favorite Button] - New element to allow users to add/remove individual posts to favourite lists / wishlists.
* [Query Loop Extras] New Favorites Query Loop, for displaying user's favorite posts.
* [Query Loop Extras] - New WP Menu Query for looping through WP menu items.
* [Query Loop Extras] - New Gallery Query for looping through images from a gallery (supports ACF Gallery field and Meta Box Image Advanced fields).
* [Dynamic Tags] - Dynamic tags added for menu item labels, URLs, descriptions and classes.
* [Conditions] - New "current taxonomy term has parent" condition.
* [Site breadcrumbs] - Added an option to choose which taxonomy to display for each CPT.
* [WooCommerce Conditions] - New condition for cart total excluding shipping cost.
* [Star Rating] - Added an option to change color to show rating, rather than different icons.
* [Pro Countdown] - New action "Count Up" for counting back up once the end date is in the past.
* [General] - Better RTL support across elements.
* [Pro Slider] - Added support for mobile-first breakpoints.
* [Pro Slider] - Add support for using Bricks' infinite scroll on slide element query loop to add new slides dynamically as the slider moves.
* [Pro Slider Gallery] - Added support for captions and thumbnails when linked with for Bricks' Lightbox.
* [General Conditions] - "Is parent" condition now supports hierarchical CPTs.
* [Header Search] - Now supports use with Bricks' live search and filter elements nested in search overlay.
* [Dynamic Chart] - New option to show data labels inside charts.
* [Dynamic Table] - Can now sort columns by date.
* [Dynamic Table] - Can now remove sorting per column.
* [Interactive Cursor] - Can now change cursor colors when moving over elements.
* [Popover] - Added "append to footer" to allow popover to always be above all other elements.
* [Member Conditions] - Added "active" or "cancelled" status to Wishlist Member conditions.
* [Member Conditions] - Added "active", "cancelled", "expired", "pending" status to RCP conditions.
* [Pro Accordion] - Improved behavior when nesting accordions inside accordions.
* [Slide Menu] - Added option to have slide menu open at current active page.
* [Social Share] - Added option to have links open in the same tab.
* [Social Share] - Fixed the issue where custom URL would output as NULL.
* [Read More] - Fixed the issue where readmore wouldn't re-open inside modal.
* [Read More] - Fixed the issue where readmore could cause page scroll.
* [Lottie] - Fixed the issue where URL was not accepting dynamic data.
* [Header Extras / Rows] - Fixed the issue where Bricks' mega menu dropdown could have wrong position when opened if inside hidden header row.
* [WooCommerce Conditions] - Fixed the issue where "Current Product in cart" set to 'false' wouldn't work.
* [General] - Amended some default CSS to prevent ACSS from adding gaps inside nested element structures.
* [Read More] - Prevent ACSS from affecting height transition with interpolate-size.
* [WooCommerce Conditions] - Added "Product in cart has a coupon applied" condition. Enables you to render elements if the selected product is in the cart and has a valid coupon applied.

= 1.5.1 ( Apr 22, 2024 ) =
* [Conditions] - Added a new "Current Taxonomy Term Has Child" condition for use on taxonomy archives.
* [Dynamic Lightbox] - Now supports using Cloudflare CDN image delivery URLs when using gallery mode.
* [Popovers] - Added two new "action" interactions to allow for controlling via interaction settings.
* [Pro Accordion] - Now supports filtering individual accordion items using WPGridBuilder facets.
* [Toggle Switch] - Can now be used inside query loops.
* [Pro Slider] - Adjusted the default "wheel sleep" setting to 700ms when using wheel navigation, preventing skipping multiple slides.
* [WPGB Styler] - Now uses min-height rather than height for the select facet, preventing overflow when using combobox and multiselect.
* [Pro Slider Control] - Fixed an issue where the progress bar value did not match the slide index.
* [General] - Added more control over ARIA labeling and roles across multiple elements.

= 1.5.0 ( Apr 18, 2024 ) =
* [Dynamic Tags] - Improved reading time logic to support use with more languages.
* [Header Search] - Now allows adding text inside the open toggle button.
* [Image Hotspots] - Added an option to replace icons with custom images for each marker individually.
* [Pro Accordion] - Moved the header tag outside the accordion header by default.
* [Pro OffCanvas] - Added an option to change inner content HTML tag.
* [Pro Slider] - Fixed an issue where Splide was adding `role=group` to slides that were list items.
* [General] - Enhanced keyboard navigation across some elements.

= 1.4.9 ( Apr 16, 2024 ) =
* [Social Share] - Added more print options, including the ability to print specific parts of the page.
* [Social Share] - Added an option to customize the subject/body text of email.
* [Copy to Clipboard] - Added support for copying user-added content from inputs/textareas.
* [Table of Contents] - Conditional display - choose a minimum number of headings found in content to display the table.
* [Pro Tabs] - Improved keyboard accessibility.
* [Pro Tabs] - Added a "tab orientation" setting to allow for changing left/right key navigation to up/down if building a vertical layout.
* [Image Hotspots] - Added a new interaction option for selected markers.
* [Popover] - Added new interaction options for popovers opening/closing.
* [Image Hotspots] - Added an option to toggle moving user focus into popover content when a marker is selected via keyboard.
* [Toggle Switch] - Labels now support HTML.
* [WPGB Facet styler] - Added a "gap" control for the pagination facet.
* [Dynamic Table] - Column headings now support using custom functions with the echo tag.
* [Pro Slider] - Fixed an issue with conditional slider where it could also hide slider controls from nearby sliders.

= 1.4.8 ( Mar 21, 2024 ) =
* [Popover] - Now supports being used inside query loops using Bricks' infinite scroll.
* [Social Share] - Added Print button as a new option.
* [Hotspots] - Exposed the instance so can be controlled via JS (see dev docs).
* [Hotspots] - Can now be closed with data-x-close attribute inside hotspot content.
* [Pro Slider Gallery] - Fixed the issue with Splide lazy loading sometimes causing images to not display.
* [Pro Slider] - Adjusted the default arrow CSS to prevent user uploaded SVGs from being targeted.
* [Dynamic Table] - Fixed the issue where the table wouldn't complete loading if empty attributes were added to columns.

= 1.4.7 ( Mar 18, 2024 ) =
* [Modal / Modal Template] - Added the ability to show modal only once per session.
* [Slide Menu] - Can now use custom icons for the sub menu dropdown button and control over transform/colors.
* [Read More] - New interactions added to toggle/collapse/expand via Bricks' interactions.
* [Read More] - Fixed the issue with read more links no longer collapsing when used with Bricks' Load more interaction.
* [Pro Tabs] - New interactions added to open any tab (or accordion) at the chosen index.
* [Nestable Table] - Added sticky table header option.
* [Pro Slider] - Performance - icon library no longer loaded by default for prev/next icons.
* [Pro Slider Control] - Performance - icon library no longer loaded by default for icons.
* [Nestable Table] - Fixed the issue where labels weren't updating after changing.
* [General] - JS Performance improvements on frontend.

= 1.4.6 ( Mar 15, 2024 ) =
* [Lottie] - Fixed JS error in builder when on hover mode.
* [Nestable Table] - Added more style settings & better default styles.

= 1.4.5 ( Mar 15, 2024 ) =
* [Nestable Table] - New element for creating nestable tables. Supports Bricks' AJAX filters, search and pagination, column stacking for mobile and using any elements inside the table.

= 1.4.4 ( Mar 13, 2024 ) =
* [General] - Security improvement.

= 1.4.3 ( Mar 12, 2024 ) =
* [Star Ratings] - Fixed issue with icon size not working with SVGs.
* [Lottie] - Addressed issue with multiple lottie elements not being able to be used when inside a GutenBricks template.
* [General] - Security patch update.

= 1.4.2 ( Feb 27, 2024 ) =
* [Header Extras] - Overlay/sticky header now compatible with sites/pages using Bricks' "boxed" layout option.
* [Dynamic Table] - Fixed an issue where the "echo" dynamic tag wasn't always outputting correctly inside cells.

= 1.4.1 ( Feb 15, 2024 ) =
* [General] - Added support for elements to be used inside Bricks' new AJAX search results, AJAX filters and AJAX popup content.
* [Element Interactions] - New "triggers" added in Bricks interactions options for many elements.
* [Pro Accordion] - New option for toggling accordion behavior across breakpoints.
* [Countdown] - Now includes fixed end times/date via dynamic data (renamed to Pro Countdown).
* [Pro Tabs] - Can now open tabs/accordion with URL parameters.
* [General Conditions] - Added "post ancestor" & "post type" conditions.
* [Dynamic Table] - New option for adding custom attributes to cells (for custom styling per column).
* [WS Form] - New styling options for international phone inputs and country dropdown.
* [Site Breadcrumbs] - Added PHP filter for customizing/adding to breadcrumb trail output.
* [General] - Added better support for JetSmartFilters facets.
* [General] - Better support for WPML auto-translate across elements.
* [Interactive Options] - New option to change glare color.
* [Pro Slider Gallery] - Added option to change animation type for Bricks' Lightbox.
* [Pro Slider Gallery] - Fixed issue where offset/randomize could cause error if no images found in gallery.
* [Pro Slider Gallery] - Fixed issue where Bricks' lightbox would group all images if slider was repeated inside query loop.
* [Social Share] - Fixed "links not crawlable" warning if using Mastodon link.
* [Developer] - Instances for dynamic table / dynamic chart now exposed, now can be used inside filtered content.
* [Developer] - Lost of helper functions added to allow control elements dynamically via interactions (see interactions tab in docs).

= 1.4.0 ( Dec 1, 2023 ) =
* [Pro Slider Control] - Added the ability to display data from prev/next or current slides.
* [Breadcrumbs] - Added an option to remove current page/post title from breadcrumbs.
* [Dynamic Lightbox] - Added an option to reposition the captions directly underneath the lightbox content.
* [Pro Offcanvas] - Focus moving back to trigger when Offcanvas closed is now optional.
* [Pro Tabs] - Now supports multiple "Read more" elements inside tab content.
* [WPGridBuilder Facets] - Added options to align radio/checkboxes horizontally.
* [Copy to Clipboard] - Added option to strip HTML tags from copied content.
* [WS Forms] - More typography settings for general text/headings inside the form.
* [Conditions] - Added != operator to "Author has CPT" entry condition.
* [General] - Elements/features will now continue to function if the license is removed from client sites (needs to be active to receive updates).

= 1.3.9 ( November 17, 2023 ) =
* [Pro Slider] - Now supports multiple synced sliders.
* [Pro Slider] - New option for allowing independent slider scrolling when using syncing.
* [Fluent Forms] - Submit button styling will now override Fluent Forms new default inline styles.
* [Fluent Forms] - Reworked the checkbox/radio styling for more control.
* [Pro Tabs] - Addressed an issue causing first item to be open in mobile accordion.
* [General] - Fixed stdClass() issue.

= 1.3.8 ( November 09, 2023 ) =
* [Slide Menu] - Fixed WordPress 6.4 preventing slide menu from opening in some cases.
* [General] - Fixed CSS from v1.3.7 causing a few ACSS variables to not be applied.

= 1.3.7 ( November 07, 2023 ) =
* [Copy to Clipboard] - New nestable button element for copying text from elements, or from dynamic data.
* [Dynamic Lightbox] - Added support for captions (for both gallery and manual link options).
* [Pro Slider] - Added gradient fade effect option for 'loop' sliders.
* [Pro Slider] - Defaults changed for new sliders - no default background styles added to slide element.
* [Slide Menu] - Accessibility improvement, will now close with ESC key or clicking outside the menu.
* [Popover] - Accessibility improvement, Open a popover via keyboard will close the previously opened ones.
* [Popover] - Accessibility improvement, focused popover will now close with ESC key.
* [Social Share] - Custom URL option now accepts dynamic tags.
* [Pro Accordion] - Support added for having pro accordions inside of pro accordions.
* [WS Forms] - Can now style the 'success messages' that appears outside of the form itself.
* [WPGB styler] - New style options for the selection facet buttons.
* [Content Timeline] - Option added to alternate text-align.
* [Conditions] - Fixed the issue with some conditions where zero value would still show element.
* [Pro Tabs] - Fixed z-index issue with animated tabs showing behind tab background color.
* [Site Breadcrumbs] - Fixed issue where the 'name' attribute wasn't being output on the 'blog' page.

= 1.3.6 ( September 21, 2023 ) =
* [General] Support for Bricks' infinite scroll + AJAX pagination added to all interactive elements.
* [WPGB Facet Styler] Added more style controls for dropdowns (multiple selection).
* [Star Rating] Fixed an issue from v1.3.5 with some dynamic tags not working for star values.
* [Pro Slider Gallery] Added "offset" option for images.

= 1.3.5 ( September 19, 2023 ) =
* [Pro Tabs] New nestable element for adding accessible tabs with mobile accordion.
* [WPGB Facet Styler] - A new element based on WP Grid Builder's facet element for easier and comprehensive styling.
* [Popover] Added an option for popover to follow cursor.
* [Popover] Added interaction delay option.
* [Popover] Improvement on how the popover moves when moving between multiple triggers.
* [Pro Slider Gallery] Added options to add max no. of images and randomize order.
* [Pro Slider] Accessibility improvement - keyboard setting default changed to "focused".
* [General Conditions] "Published during last.." condition can now be used for any post type.
* [WooCommerce Conditions] Added "Current product in cart" condition.
* [Table of Contents] - Added JS event that fires conditionally if table of contents is empty.
* [General] Performance improvement - reduced database queries on front end.
* [Header Extras] - Fix issue where sticky header wouldn't be applied when using across multiple header templates.
* [Star Rating] Addressed PHP deprecation notice for PHP 8.1+.

= 1.3.4 ( August 30, 2023 ) =
* [General Conditions] - Added "Date field value", "Datetime field value", "Has child category", "TranslatePress language", "Author has CPT entry" and "At least 1 entry exists (for the selected CPT)" conditions.
* [WooCommerce Conditions] - Added "Product allows backorders", "Product on backorder", "Product upsell count", "Product Cross-sell count", "Product has category" and "Product has tag" conditions.
* [Pro Slider] - Added "intersection" options to autoplay & autoscroll, for starting only when slider comes into view.
* [Site Breadcrumbs] - Added an option to include CPT archive link for CPTs.
* [Social Share] - Now can be used to share taxonomy archive URLs.
* [Read More] - Improved button width setting to allow any units and variables.
* [Header Extras] - Sticky header CSS removed from pages where it is disabled.
* [Member Conditions] - Fixed an issue with EDD subscriptions product dropdown not displaying.
* [General Conditions] - Fixed an issue that could cause JetEngine custom fields not to display on archive pages.

= 1.3.3 ( August 02, 2023 ) =
* [WooCommerce Conditions] - New conditions based around products/cart/users.
* [General Conditons] - New general conditions (now 24 in total) for various common use-cases within WP. Added these: Body classes, Current day of month, Current month, Current year, Has custom excerpt, Has post content, Language (Polylang), Loop item number, Published during the last.
* [Membership Conditions] - Added Paid Membership Pro.
* [Membership Conditions] - Added WooCommerce Subscriptions.
* [Pro Accordion] - Improved the scroll-to logic to make it easier to have reader-friendly hash links when using loops.
* [General] - Improvement on Lenis support, to make sure popup type elements are still scrollable if they contain content larger than the viewport height.

= 1.3.2 ( July 31, 2023 ) =
* [Membership Conditions] - Added SureMembers (Access group) condition.
* [General Conditions] - Added "Page type", "Page parent" and "WPML language" conditions.
* [Modal/OffCanvas/Lightbox] - Added support for stopping scroll when opened if using Lenis smooth scrolling (like with BricksForge).
* [Pro Slider] - Fixed an issue with clip direction not being applied.
* [General] - Fixed PHP warning for PHP 8.2.

= 1.3.1 ( July 27, 2023 ) =
* [Conditions] - Fixed an issue where some conditions weren't being applied.
* [Conditions] - Added WishList Member condition.

= 1.3.0 ( July 27, 2023 ) =
* [Conditions] - Added the first batch of extra conditions to Bricks for a variety of use cases + integrations with membership plugins.
* [Dynamic Lightbox] - Added support for adding custom prev/next buttons inside lightbox content area when using nest elements and grouping.
* [Site Breadcrumbs] - Added truncate option to add post title character limit. 
* [Site Breadcrumbs] - Added an option to use icon as home link.
* [Pro Slider] - Added better support for adding sliders inside sliders.
* [Content Timeline] - Can now change the HTML tag on the inner container (ideal for ul > li).
* [Dynamic Tags] - Added "x_parent_loop_index" for getting index from parent / grand parent query loops.
* [Pro Slider] - Fixed an issue where image elements wouldn't always be picked up by Bricks lazy load if autoscroll was enabled.
* [Dynamic Chart] - Fixed issue where tooltips wouldn't pick up values from doughnut type charts.
* [Dynamic Chart] - Updated from v3.x to v4.x of chartJS.
* [General] - Fixed an issue where Piotnet Grid's AJAX search facet wouldn't work.
* [General] - Improved how element CSS is being added to allow for elements to be used inside post content area or inside Bricks' popup templates.

= 1.2.9 ( June 16, 2023 ) =
* [General] - Compatibility for Bricks v1.8.1+.
* [Pro Accordion] - Improve default structure (heading instead of text element for accordion title).
* [Pro Accordion] - Improve how Schema markup is added to allow for use with Perfmatters' "delay until user interaction" setting.
* [Fluent Form] - Added checkbox typography settings.
* [Fluent Form] - New style settings for form wrapper.

= 1.2.8 ( June 02, 2023 ) =
* [Pro Slider] - Fixed the issue that was causing the new autoplay control to not be correctly synced with the slider.

= 1.2.7 ( June 02, 2023 ) =
* [WS Form] - New element for adding/styling individual WS Form forms.
* [Dynamic Lightbox] - No longer restricted by styling by class only.
* [Evergreen Countdown] - Added "redirect to URL" to actions.
* [Pro Slider] - Added "clip direction" option for creating one-way overflowing sliders.
* [Pro Slider Control] - New control type - "Autoplay Progress" displaying interval progress.
* [Pro Slider Control] - New control type - "Slide content" for displaying any dynamic slide content outside of the slider.
* [Pro Slider] - Added option to change easing on the slider.
* [Pro Slider] - Added support for Bricks' v.1.8+ lazy loading change.
* [Pro Slider] - Nav aria-labels now added in at the PHP level to prevent Google Page Speed not finding them.
* [Pro Slider Gallery] - Added option to group images when using inside Bricks' Lightbox.
* [Pro Slider] - Now loads the Splide CSS earlier on pages using Pro Slider to minimise FOUC.
* [Dynamic Table] - Added new option for stacked columns to move labels onto their own line.
* [OffCanvas] - Renamed to "Pro OffCanvas" in builder to prevent confusion with  Bricks' v.1.8+ element of same name.
* [Content Timeline] - Added support for filtering timeline items with WP Grid Builder.
* [Dynamic Chart] - (Dev) - Made chart Instance accessible for changing options/data dynamically using JS (see developer docs).
* [Pro Slider] - Fixed the width issue in Safari when combining gallery links and autoWidth setting.
* [interactive Cursor] - Fixed the issue where cursor would remain expanded after back to top was hidden.

= 1.2.6 ( May 10, 2023 ) =
* [Evergreen Countdown] - New element for evergreen countdowns.
* [Dynamic Chart] - New query loop option for dynamically adding new data points.
* [Header Search] - Added "expand" search type.
* [Pro Accordion] - Added an option to auto-add FAQ schema to all accordion items.
* [Notification Bar] - The "show again until the user clicks dismiss" now allows for showing again after a set time.
* [Pro Slider Gallery] - Added an option to change the size of the image when adding links (for use with Dynamic Lightbox).
* [Hotspots] - Markers can now be links.
* [Slide Menu] - Added customizable aria-label for dropdown arrows.
* [Table of Contents] - Added "conditional display" option to remove the table if no headings are found.
* [X-Ray] - Moved the position of the icon and can now be enabled/disabled from the plugin settings page.
* [Dynamic Lightbox] - Plyr assets are no longer being fetched from the CDN.
* [General] - Added support for using elements inside content filtered by Piotnet Grid's facets.
* [General] - Some minor UI changes are ready for Bricks v1.8.
* [Lottie] - Fixed an issue with the "hover" trigger where child elements would restart the animation.
* [Pro Slider] - Fixed an issue where styling wasn't correct inside the builder if was inside Bricks' template element.
* [Table of Contents] - Fixed an issue where adding non-numeric values in offset wasn't accepted.
* [Modal] - Fixed an issue where the very bottom of the modal sometimes wasn't visible on mobile devices.

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
