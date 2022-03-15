# This is the log for the fresh version 2 of serato css, new melody

## [1.0.6] - Serato Version 2 - New Melody, 2022-02-26

- dev: started altering the project structure and architecture to better.

## [1.0.6] - Serato Version 2 - New Melody, 2022-02-27

- dev: scrapped the project to use open Props
- CSS: updated base and added new custom scrollbar
- CSS: added theme modes eg. dark theme.

## [1.0.7] - Serato Version 2 - New Melody, 2022-03-3

- CSS: changed colors to use open props, almost done with the transition of grays and the core theme colors.
- CSS: changed class names to the new proposed convention of balancing between predictability and seamless experience.
- CSS: Changed some helper classes to :where and reduced specificity issues!

## [1.0.8] - Serato Version 2 - New Melody, 2022-03-3

- CSS: Done with grays and core theme colors, their implementation might shape how we will work with the rest of colors from open props.
- CSS: finally rolled up all open prop colors, they just need per feature testing, specificity fixes and some other minor fixes!

## [1.0.9] - Serato Version 2 - New Melody, 2022-03-5

- CSS: fixed the glitch with shade-1 and shades basic color helpers eg. color-grape-1 now are included!
- **Colors**: done with colors finally, but we still need to work on gradients and make internal components like cards have dark mode built in. We will need to make --glass a separate modifier with ranges eg. glass-low, medium etc to reduce the current bloatness of implementing it on every color!
- Issue: in house or serato colors have been given a higher specificity than other colors but we're still getting some specificity issues, this needs further inspection!

## [1.1.0] - Serato Version 2 - New Melody, 2022-03-6

- Todo: use open prop transitions instead of the current!
- CSS: Added in open prop gradients, now border gradients pending...
- CSS: started experimenting with open props built in darkmode
- Next: borders, border radius,z-index, aspect ratio, spacing and more!

## [1.1.1] - Serato Version 2 - New Melody, 2022-03-7

- CSS: added various open prop variables and also mapped them out to in house sass variables. Added aspect ratios, typography stuff, z-index, border stuff and more!
- Note: We still need to look into conditional props and also implement generators for all the added open prop variables.
- Next: Sizes, reading content size and add the remaining open prop variables

## [1.1.2] - Serato Version 2 - New Melody, 2022-03-12

- Todo: Fix dark button colors in dark mode.
- Theming: Started to make theme responsive components such as light / dark buttons. Will just need some more touchs offs.

## [1.1.3] - Serato Version 2 - New Melody, 2022-03-14

- Todo: Fix dark button colors in dark mode.
- CSS: Added animations, all sizes variables and all easings.
- CSS: completed adding in house variables for all open prop variables.
- Note: Media Queries need some further inspection and perhaps some setup to work i.e the post css plugin.
- Next: Start generating helper utility classes for all open prop variables.

<!-- Todo: Fix custom scrollbar for firefox, eg. add block padding! -->

