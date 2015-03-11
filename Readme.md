# Kitchen Sink

A lightweight and complete framework for projects.

## To Do

Partial out SCSS into folders (partials/common/components)
Load in JS components

## Key Points

Lean, standards compliant and accessible re-usable code and components.

CSS classes with consistent and relevant naming conventions. 

Should work down to IE7 - it'll hopefully degrade nicely.

## HTML

Based loosely on HTML5 Boilderplate

Use semantic class names when naming things.

## CSS

Any element with a role= gets the same class name.

Name elements using only classes. 

Use .js-[name] or #js-[name] for hooking into JavaScript/jQuery

Do not nest selectors more than 3 levels deep. We want the output to be efficient.

Remove any rules that are not needed and cleanse before production

### Clearfix / Group
### Grid Layouts
### Forms
### Responsive Images
### Icons

## Design Standards

Margins and padding based on multiples of 15px at 960px. 

Typography 19px @ 1:1.618 (base font size) 960px @ 1:1.618 (outer wrapper width)

## JavaScript / jQuery Components

Call jQuery first from Google, then if this fails call locally. Use ARIA roles on JS components to increase accessibility.

### Accordions
### Form Validation
### Grid Equal Height
### Hidden Text - with progressive disclosure
### Image sliders

### Modal Window
  http://kylefox.ca/jquery-modal/examples/index.html
  http://www.jacklmoore.com/colorbox/
### Responsive Accessible Drop-down Navigation
  https://github.com/adobe-accessibility/Accessible-Mega-Menu

### Responsive Tables
### SVG Animation
### Tabs
  [roled my own]
### Tool Tips or Hint Text
### Video Polyfill
  https://github.com/davatron5000/FitVids.js
