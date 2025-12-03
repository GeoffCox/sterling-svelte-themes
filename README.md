# sterling-svelte-themes

A modern theme for the sterling-svelte component library.

To learn how to use this theme, please see the [Sterling Theme](https://geoffcox.github.io/docs/sterling-svelte/topics/theme") documentation.

## Installation

```
npm install @geoffcox/sterling-svelte-themes
```

## Light and Dark Modes

Version 2.0 supports light and dark modes automatically.
A single set of CSS vars that leverage the light-dark() function to pick colors based on the color-scheme property
set on the root document element.

## Repository

https://github.com/GeoffCox/sterling-svelte-themes

## Change Log

### 2.0.8

- Added styles for checkbox button variant
- Added styles for radio button variant
- Cleaned up disabled styles for checkbox and radio

### 2.0.7

- Added styles for new Splitter component

### 2.0.6

- Fixed a few of invalid CSS declarations for background and border colors

### 2.0.5

- Fixed issue with new button disabled state not applying due to specificity of colors and variants

### 2.0.4

- Standardized disabled styles: Removed no-step diagonal stripes in favor of traditional background, border, and color.
- Removed progress disabled styling (progress is not interactive)
- Fixed MenuItem disabled styling selector issue
- Improved layout of Label to help content/input responsd to width changes
- Improved layout of Label with boxed style to display message across the bottom.
- Fixed modifies of button colors to separate multiple modifiers with multiple double dashes (e.g. --blue-hover => --blue--hover)
- Fixed Switch hover, active, selected background colors for better contrast
- Improved focus styles of Slider, Switch to focus on button/thumb element
- Added border width variables for common, button, and input.
- Fixed missing use of outline border width variable across all styles.
- Reduced border and outline width from 2px to 1px to avoid heaviness with border styles
- Fixed bug in Pagination missing input:hover style
- Updated drop shadows to be consistent for Callout, Dialog, Dropdown, Menu, Select, and Tooltip.

 
### 2.0.3

- Slider - support for reverse direction of slider

### 2.0.2

- Autocomplete - added styles

### 2.0.1

- Label - fix justification of text vs chilren in horizontal layout
- Label - fixed spacing between text and children in horizontal and vertical layouts
- Label - fixed CSS specifier for required reason inside Tooltip
- Label - increased min-width of required indicator to made hover easier

### 2.0.0

- light-dark() theme support

### 1.0.4

- Dropdown - added classes for button and icon slots, dropdown content
- MenuItem - moved MenuItemDisplay.css styles into MenuItem.defaultItem.css
- Pagination - added styles
- Select - added class for select content

### 1.0.3

- Button, Checkbox, Dialog, Input, Label, MenuItem, Radio, Switch, Tab, and TextArea - Added appearance:none to avoid built-in styles in some browsers


### 1.0.2

- Reorganization of CSS
- Label - Fixed css var typos   
- Button - added colors

### 1.0.1

- Fixed CSS exports in package

### 1.0.0

- Moved CSS into this package to separate Sterling Theme from sterling-svelte