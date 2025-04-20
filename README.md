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