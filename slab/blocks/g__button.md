# Button

## Overview

A customizable button component that renders a link styled as a button with various appearance and layout options. Supports responsive visibility controls and multiple style variants.

## Common use cases

- Create call-to-action buttons throughout your theme
- Use custom actions to trigger overlays, form submissions, or JavaScript functions
- Configure button size and color to match your theme's design system
- Use full-width option for prominent mobile CTAs

## Child blocks

This block includes the following nested blocks:

- Rich text
- Icon
- Image
- Localization label
- Cart count
- Cart price

## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| URL | Link destination for the button | URL input (default: /collections/all). Visible when enable custom action is false |
| Enable custom action | Enables custom JavaScript actions instead of URL navigation | Checkbox (default: false) |
| Overlay preset | Select a preset overlay action or use custom | None (default), Account, Search, Menu, Primary cart, Alternative cart, Custom. Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable logout is false and enable back to top is false |
| Overlay custom | Custom overlay ID for custom overlay actions | Text input. Visible when enable custom action is true and overlay preset is custom |
| Enable close overlays | Closes all open overlays when button is clicked | Checkbox (default: false). Visible when enable custom action is true and enable form submission is false and enable logout is false and enable back to top is false and overlay preset is none |
| Enable form submission | Submits the nearest form when clicked | Checkbox (default: false). Visible when enable custom action is true and enable close overlays is false and enable logout is false and enable back to top is false and overlay preset is none |
| Enable logout | Redirects to account logout URL | Checkbox (default: false). Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable back to top is false and overlay preset is none |
| Enable login | Redirects to account login URL | Checkbox (default: false). Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable back to top is false and overlay preset is none |
| Enable back to top | Scrolls page to top when clicked | Checkbox (default: false). Visible when enable custom action is true and enable close overlays is false and enable form submission is false and enable logout is false and overlay preset is none |
| Enable internal padding | Adds internal padding to the button | Checkbox (default: true) |
| Enable horizontal padding | Adds horizontal padding around the button | Checkbox (default: false) |
| Enable top padding | Adds top padding around the button | Checkbox (default: false) |
| Enable bottom padding | Adds bottom padding around the button | Checkbox (default: false) |
| Button color | Controls the button color scheme | Primary, Secondary (default), Tertiary, Neutral, Plain, Outline, Inverted outline, Blur, Link, Inverted link |
| Button size | Controls the button size | Extra small, Small, Standard (default), Large |
| Horizontal alignment | Controls horizontal alignment of the button | Left (default), Center, Right. Visible when enable full width is false |
| Enable full width | Makes the button span the full width of its container | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |

