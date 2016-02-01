# Fusion-CSS

Fusion-CSS: A Flexible, Responsive  CSS framework for Mobile-Friendly Developement - Build with Sass.

Current version: 1.0-Alpha

# Features

* CSS Reset.
* Print ready!
* Components normal, like typography, buttons, forms and tables.
* Utilities
* Components advacned.


## Choose your own features

If you don't want something that is imported by the FusionCSS.scss file. Then just put two slashes (//) before the @import begins.
Example:
 Features we're going to import: CSS reset, typography and tables.
 Our FusionCSS.scss will looks like this:
 ```SCSS
 /* :: Fusion CSS ::
 * - Copyright 2016 Cyril de Wit.
 * - Version: 1.0
 * - Licensed under MIT
 */
 //
 // Charset
 //
 @charset "UTF-8";


 //
 // Config
 //
 @import "lib/config";

 //
 // Core variables and mixins
 //
 @import "lib/variables";
 @import "lib/mixins";


 //
 // Reset and dependencies
 //
 @import "lib/reset";

 //
 // Core CSS
 //

 //
 // Components normal
 @import "lib/components/typography";
 @import "lib/components/tables";
 ```

# Milestone

### Global

* [X] Reset
* [ ] Print ready
* [ ] Utilities

### Elements

* [ ] Typography
* [ ] Buttons
* [ ] Forms
* [ ] Tables

### Components

* [ ] Divider
* [ ] Headers
* [ ] Icons
* [ ] Images
* [ ] Labels
* [ ] Lists
* [ ] Loader
* [ ] Steps
* [ ] Dotnav
* [ ] Slidenav
* [ ] Pagination
* [ ] Progress bar
* [ ] Sliders
* [ ] Notifications
* [ ] Button groups
* [ ] Addres cards
* [ ] Panels
* [ ] Pricing tables
* [ ] Tags
* [ ] Advertisement
* [ ] Cards
* [ ] Comments
* [ ] Feeds
* [ ] Statistic

### Collections

* [ ] Breadcrumbs
* [ ] Form layouts
* [ ] Grid
* [ ] Menu
* [ ] Messages

### Modules (JS)

* [ ] Accordians
* [ ] Modals
* [ ] Dimmers
* [ ] Dropdown functions
* [ ] Progress
* [ ] Rating
* [ ] Search
* [ ] Sidebar
* [ ] Sticky
* [ ] Tabs
* [ ] Transition
