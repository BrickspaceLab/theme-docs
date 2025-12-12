# Button


## Overview

A customizable button component that renders a link styled as a button with various appearance and layout options. Supports responsive visibility controls, multiple style variants, and custom actions including overlay triggers, form submissions, and navigation.


## Common use cases

- Create call-to-action buttons throughout your theme
- Use custom actions to trigger overlays, form submissions, or JavaScript functions
- Configure button size and color to match your theme's design system
- Use full-width option for prominent mobile CTAs
- Trigger account, search, menu, or cart overlays with preset actions
- Submit forms or perform logout/login actions with custom button behavior


## Compatible blocks

The following blocks can be nested within this block - click the listed blocks below for more detailed documentation:

- [Rich text](richtext.md)
- [Icon](icon.md)
- [Image](image.md)
- [Localization label](localization-label.md)
- [Cart count](cart-count.md)
- [Cart price](cart-price.md)


## Block settings

### Content

| Setting | Description | Options |
|---------|-------------|---------|
| URL | Link destination for the button | URL input (default: /collections/all)<br><br>Visible when enable custom action is false |
| Enable custom action | Enables custom JavaScript actions instead of URL navigation | Checkbox (default: false) |
| Overlay preset | Select a preset overlay action or use custom | • None (default)<br>• Account<br>• Search<br>• Menu<br>• Primary cart<br>• Alternative cart<br>• Custom<br><br>Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable logout is false and enable back to top is false |
| Overlay custom | Custom overlay ID for custom overlay actions | Text input<br><br>Visible when enable custom action is true and overlay preset is custom |
| Enable close overlays | Closes all open overlays when button is clicked | Checkbox (default: false)<br><br>Visible when enable custom action is true and enable form submission is false and enable logout is false and enable back to top is false and overlay preset is none |
| Enable form submission | Submits the nearest form when clicked | Checkbox (default: false)<br><br>Visible when enable custom action is true and enable close overlays is false and enable logout is false and enable back to top is false and overlay preset is none |
| Enable logout | Redirects to account logout URL | Checkbox (default: false)<br><br>Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable back to top is false and overlay preset is none |
| Enable login | Redirects to account login URL | Checkbox (default: false)<br><br>Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable back to top is false and overlay preset is none |
| Enable back to top | Scrolls page to top when clicked | Checkbox (default: false)<br><br>Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable logout is false and overlay preset is none |


### Spacing

| Setting | Description | Options |
|---------|-------------|---------|
| Enable internal padding | Adds internal padding to the button | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the button | Checkbox (default: false) |
| Enable top padding | Adds top padding around the button | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the button | Checkbox (default: false) |


### Color

| Setting | Description | Options |
|---------|-------------|---------|
| Button color | Controls the button color scheme | • Primary<br>• Secondary (default)<br>• Tertiary<br>• Neutral<br>• Plain<br>• Outline<br>• Inverted outline<br>• Blur<br>• Link<br>• Inverted link |


### Style

| Setting | Description | Options |
|---------|-------------|---------|
| Button size | Controls the button size | • Extra small<br>• Small<br>• Standard (default)<br>• Large |


### Layout

| Setting | Description | Options |
|---------|-------------|---------|
| Horizontal alignment | Controls horizontal alignment of the button | • Left (default)<br>• Center<br>• Right<br><br>Visible when enable full width is false |
| Enable full width | Makes the button span the full width of its container | Checkbox (default: false) |


### Display

| Setting | Description | Options |
|---------|-------------|---------|
| Visibility | Controls when the block is visible | • All (default)<br>• Mobile only<br>• Desktop only |
