# Changelog

## [1.0.0] - 2021-11-21

- dev: Added this CHANGELOG file
- dev: Structured project
- css: Added all base resets
- css: Added utilities (media queries & variables)
- css: Added helpers and it's subsidiaries
- css: Started on animation stlyes
- dev: Added test.scss to test sass output in isolation

## [1.0.0] - 2022-01-01

- dev: Back to coding...
- css: Added flex helper classes
- css: Added spacing helpers
- css: Added typography
- css: Added positioning
- css: Added displays
- css: Added buttons
- css: Added components

## [1.0.0] - Log Per Feature, 2022-01-02

- css: Added plugins
- plugins: Added and modified hvr.css animations
- css: renamed variables to global variables

## [1.0.0] - Breaking Changes, 2022-01-06

- css: Changed highlight color in experiment partial
- css: played with scrollbar colors in experiment partial
- css: renamed various variables and arranged global variables
- colors: created about 3 reusable color styles
- css: made button styles and with native builtin click animation
- css: added a mixin
- testing: added more test html markup to test things out
- colors: added more color variables
- css: started on card component

## [1.0.0] - Time to style up, 2022-01-07

- colors: added colors variables
- colors: added serato color system colors, a bunch of them!
- colors: generated color classes

## [1.0.0] - Tune up the looks, 2022-01-08

- colors: added famous brands colors like linked & twitter's blue,
- css: added serato css brand colors for default components styling
- colors: started on color gradients, serato-gradient ready!
- flexbox: added flex-all-center class helper
- css: added border radius classes, they might need some revison!
- colors: modularized all colors into partials
- colors: Completed this module, with basic, grays, extended and famous brand colors all blended in with their respective shades!
- css: added more and old serato (tie-and-dye) mixins
- gradients: added text gradient helpers
- animations: added font-awesome animations, done with animations for now!

 **warning: button light needs some fixing!**
 **Todo: Animations should be in repect to prefers-reduced-motion media query**

## [1.0.1 Beta] - Beta relaese finally!, 2022-01-09

- css: Added media queries, next working on responsiveness
- css: added more mixins, just non configured yet but coming...
- Dev: release of beta v1.0.1 pending...
- Dev: starteed to work on gulp and other preprocessing tasks to compile production ready css!

*Warning: Dev dependencies and packages need to be installed along with gulp-cli

## [1.0.2 Beta] - Beta relaese fixes & improvements!, 2022-01-12

- fixies: fixed button light issue,
- css: added height and width helpers,
- css: added responsive margin and padding helpers,
- css: added gap spacing helpers for flexbox,
- css: added aspect ratio helpers but need revision,
- css: added object-fit property helpers,
- css: added list-style-type helpers,
- css: added opacity & opacity on-hover helpers

## [1.0.3 Beta] - More improvements!, 2022-01-13

- css: added transition helpers
- css: fixed spacing between list items
- css: added functions & make hoverable mixin
- css: button-light variant made default variant for button component and removed the button-light helper class!
- css: added color helpers for hover states!
- css: added box-shadow helpers
- css: added width-content helper for buttons to not span the whole width but respect their content within!
- animations: fixed colors in hover animations!
- css: added text decoration helpers
- css: added link helpers
- css: added iconic button helpers

## [1.0.3 Beta] - Almost ready to launch!, 2022-01-14

- css: added gradient borders
- mixins: added space-on-hover mixin
- css: changed transiton helpers to more predictable class names!
- css: added more list helpers, plus hoverable variant which uses space-on-hover as default animation
- css: disabled user selection on all gradient and glass-morphic styled elements!
- css: added transition smooth
- css: added smallest gap helper gap-x
- css: added glass morphism helper
- css: added layouts and started working on them!
- layouts: completed the standard layout!
- responsiveness: added breakpoints & breakpoints mixin

## [1.0.4] - First Official Release, 2022-01-19

- dev: changed project structure to more standardized structure optimized for npm publishing.
- dev: configured development environment with gulp and plugins, moved away from using live sass compiler extesion to jump start development.
- dev: Removed irrelevant files, some are moved to serato docs repo.
- dev: Fixed slash div sass deprecation warning!
- dev: Updated Readme!
- dev: Created new zip archive for download,
- dev: Updated package on npm registry!

## [1.0.5] - First Official Release - patch, 2022-01-19

- dev: removed more irrelevant folders and file eg. /dist
- dev: added .npmignore to avoid pushing uncessary files to npm package.

### Back log ( Todos )

*Add dark mode for all components
*Improve color functions and mixins - rabit hole!
*Add hoverable border-colors & border helpers*
*Add form & input helpers*
*design product page, product card and layout components*
*Animations should be in repect to prefers-reduced-motion media query*

#### Special Issue

> Get an appropriate color for text and background based on whether the text is on a light / dark background and vis a vis for the background, also use tint and shade functions respectively to highlight or darkify any given color on hover instead of using lightness and darken sass builtin functions. This is really a rabbit hole!!!
