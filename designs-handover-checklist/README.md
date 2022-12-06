# Designs handover checklist

## Overall
* Have you published your final designs? Are they signed off by the client?
* Number of views defined: mobile, desktop, tablet? Which breakpoints should be used for each view? Minimal and maximum supported screen width?
* How the layout would change for ultrawide screens (for example > 1920px), which components are going to expand and which would have fixed max width.
* Does it include potential edge cases, empty states, and error states for pages or tables?
* Behaviour when network errors occur (for example to show notification with specific text)
* Are there page designs for 404, 500 errors and outdated browser warning page?


## Grid
* Number of columns (do they change on mobile, tablet and desktop)
* Main container max width & margins (fixed or fluid)
* Breakpoints between mobile/tablet/views are defined. 
* Gutters (fixed or fluid)
* Margin/padding logic between components is defined, fixed predefined set of margin sizes or fluid based on width
* Vertical spacing & margin rules for components (fixed or fluid based on height)
* Sidebars & menus spacing logic defined: how do they work on different screens, is the width/height fixed, sticky behaviour, logic for expanding or opening the menus or sidebars.

## Fonts & text
* List of all font faces used in the project are provided
* Does font size depend on breakpoints or font size depends on viewport?
* Long text logic: is component size expanded or it’s limited by number of lines?

## Images & icons
* Responsive image approach: does image dimension change on different view? Can the user upload image with  different dimensions? Should they be filling the width or height, or be aligned and cropped. etc.
* Does image require focal point cropping? Is it supported in CMS?
* Are the images and icons made exportable?
* SVG icons: icon graphics are embedded as SVG in design and are exportable?
* SVG icons: standard icons have same proportions (for example, 50x50px), for example icons like search & trash bin that are used on the buttons should have the same dimensions
* SVG icons: icons allow changing color via “fill” property, that are used in different colors

## Form controls
* Same form controls designs are used across all the forms site? If not, suggest to unify the design
* For dropdown select in open state should be using native browser control rather than custom designed where possible.
* Validation status (status invalid / valid) & messages displayed
* Form control states designs are provided: hover, focus, active, input tooltips if required
* Form states: during submit, and when successfully submitted

## Animations & interactions
* Transition timings and easing: default behavior and points where it varies
* Animation sequence timeline if applicable
* Animation examples 
