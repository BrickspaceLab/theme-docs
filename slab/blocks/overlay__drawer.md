# Drawer


## Overview

A customizable drawer component that displays content in a sliding overlay panel. This component creates an interactive drawer that can be positioned at the bottom, left, or right of the screen with a button to trigger its visibility.


## Common use cases

- Use for navigation menus, filters, cart drawers, or any content that should appear on demand
- Consider the best position based on content type (e.g., filters often work well as left/right drawers)
- Ensure drawer content is accessible and navigable by keyboard
- Customize colors and borders to match your theme design


## Child blocks

This block includes the following nested blocks:

- Container (for drawer content)
- Container (for drawer footer)


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Overlay preset | Select a preset overlay ID or use a custom one | Account, Search, Menu, Primary cart, Alternative cart, Quick buy, Quick edit, Custom (default) |
| Overlay ID | Custom identifier for the overlay (used to trigger it programmatically) | Text input. Visible when overlay preset is "Custom" |
| Show close button | Displays a close button in the drawer | Checkbox (default: false) |
| Color scheme | Controls the background and text color combination | Body, Neutral, Accent 1 (default), Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Border color | Controls the border color | Subtle (default), Strong, None |
| Horizontal position | Position of the drawer along the horizontal axis | Left, Center, Right (default) |
| Vertical position | Position of the drawer along the vertical axis | Top (default), Bottom |
| Enable full height | Makes the drawer extend to full viewport height | Checkbox (default: false) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |

