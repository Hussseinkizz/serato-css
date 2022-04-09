# SERATO CSS V2 - NEW MELODY

## Serato CSS V2 Plan & Roadmap

* Biggest Change: We will build on top of open props instead.

* We will change our whole reset to use open props's flavoured normalize.
  > It has zero specificity resets, not bloated and probably more expert curated with built in darkmode!
  > Note that we will still use our typography reset, it's way better typo reset for now!!!

* We will change the color system!

 > We will replace basic and gray shades colors with open props's open colors and also adapt gradients from open props.

* We will make everything modern css, easy to customize and zero specificity!

 > We will use modern css like :is, :where, and logical properties like margin-inline except for special combos or modifiers eg. --hoverable, cause these are always !important.

* We will change our build process!

 > We will change our build pipeline, we will now use post css for real time sass to css compilation, this will allow us to benefit from open props's custom media goodies!
 > By the way, our documentation site will now be deployed to github pages instead, this gives our open source a more open source edge over the vercel deployment.

* We will fix known bugs and also include new features!

 > We will fix the bugs identified in recent project studies and also include those essential utilities which were found missing apparently.
 > We will opt for a balance of great developer experience and easy type experience, that says... we will use short naming conventions for common known short names and leave the rest to flat naming carefully.
 > For example, background-color-red will be bg-red, margin-top-1 will be mt-1 and so on, we are sure these are widely common for css frameworks users and its kinda poor experience having to type long class names.This also means combining breaking names such as border-radius-circle to borderRadius-circle or text-decoration-none to textDecoration-none etc.
 > All modifiers and stateful classes such as hover states and hoverable will now start with a double hypen -- eg. bg-blue--hoverable to allow easy recognition and avoid confusion with other stateless or un modified classes, while serato own classes or values off those from open props will now start with underscore to denote that they're scoped to serato only eg. _color-gold!

* We will change the animations library except the hover animations

 > We might replace awesome animations plugin for open props animations or any other css animations library like animate.css, the awesome animations cause a funny z-index issue identified on float animation.

* We will use Una Kravet's css gram to mimic instagram photo effects [CSS Gram](https://una.im/CSSgram/)

 > We will allow devs to turn any photo to a lit one with just a single class utility!

*Author: Hussein Kizz*
