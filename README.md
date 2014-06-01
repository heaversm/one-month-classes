one-month-classes
=================

###GROWTH HACKING

* CSS Framework: Twitter Bootstrap 3
* Javascript Library: jQuery Latest
* Fonts: Open Sans from Google Web Fonts
* Breakpoints: 991px and 767px
* Container Max Width: 970px
* Icons: Twitter Bootstrap 3 Glyphicons

#### Implementation Notes

This page was built with modifiability and simplicity in mind. All class naming conventions are kept generic so as to apply to any site's content.

Because the site uses Bootstrap, any non-bootstrap related styles have been tied to IDs. Although in some cases it would make more sense normally to attach these styles to classes rather than IDs, because the site is so simple and because I wanted to create a clear distinction between what is bootstrap and what is custom CSS, I put them on IDs.

#### BOOTSTRAP BUILD

 In order to keep file sizes down, this site uses a custom build of Twitter Bootstrap, requiring only the following components:

**COMMON**:
* Typography
* Grid System
* Tables
* Buttons

**COMPONENTS**:
* Glyphicons
* Button Groups
* Labels
* Jumbotron
* List Groups
* Panels
* Wells

**JAVASCRIPT COMPONENTS**:
*Modals

**UTILITIES**:
*Basic Utilities
* Responsive Utilities

This build is inclusive enough to allow for some extensibility and customization, but removes most of the heavy navigational and form-related styles of Bootstrap 3.

#### CROSS BROWSER COMPATIBILITY

This site uses some HTML5 semantic markup. The html5 shiv is recommended, though it was not included for simplicity of explaining how to build the site. The site also uses media queries, border radius,  box-shadow, svg, and web fonts. For maximum compatibility, you might consider polyfills for these elements, though again, they were left out for code simplicity.

#### LIBRARIES

To reduce the file size even more, I would consider using a customized build of jQuery 2, even though it is not compatible with older versions of IE.

Both jQuery and Twitter Boostrap were minified to reduce file size. If you need the unminified versions, let me know.
