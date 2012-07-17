# Expand-o-matic

_A mobile-first CSS grid framework based on Skeleton and Foundation_

Expand-o-matic is based on two wonderful CSS responsive grid systems, namely [Skeleton](getskeleton.com) and the [mobile-first version of Foundation](github.com/adamfairhead/mobile-first-foundation). It is also much simpler (or more basic, if you prefer) and consequentially may have less of a learning curve. Based on a mobile-first responsive grid, you should be able to quickly develop websites that look beautiful at any size and on any device.

Preview page: http://cr0ybot.github.com/Expand-o-matic

## The CSS Files

### base.css

Contains base styles applied site-wide.

* __CSS Reset__: Uses [Normalize.css](http://necolas.github.com/normalize.css/)
* __Basic Styles__: Default font, color, background
* __Typography__: Heading fonts, blockquotes, and a handy `hyphenate` class
* __Links__: Yup, links
* __Lists__: Some nested list styling
* __Images__: Scale images with the grid
* __Buttons__: Ready-made button styles
* __Forms__: Ready-made form styles
* __Misc__: Handy classes for floating, aligning text, and adding/removing margins

### grid.css

Contains grid definitions (based on Foundation) and Nicholas Gallagher's [Micro Clearfix Hack](http://nicolasgallagher.com/micro-clearfix-hack/).

* Mobile-First Base
* Larger than 480 (481 -> 768)
* Larger than 768 (769 -> 1024)
* Larger than 1024 (1025 -> ?)
* Clearing

### styles.css

Contains _your_ custom styles!

* __Base Styles__: Styles that apply to all devices or are overridden by the next section
* __Media Queries__: "Standard" width breakpoints (320, 480, 768, 1024) - You are encouraged to create new breakpoints based on where your design breaks when you resize the window
* __Font-Face__: @font-face definitions
