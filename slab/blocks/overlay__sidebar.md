# Sidebar


## Overview

A configurable sidebar overlay component that can slide in from either the left or right side of the screen. Creates a responsive sidebar drawer with customizable styling, positioning, and content.


## Common use cases

- Provide a unique overlay_id for each sidebar instance
- Use the visibility settings to control display on different device sizes
- Consider user experience when configuring close button visibility
- Create navigation menus, filters, or supplementary content panels


## Child blocks

This block includes the following nested blocks:

- Container (for sidebar content)
- Container (for sidebar footer)


## Block settings

| Setting | Description | Options |
|---------|-------------|---------|
| Overlay preset | Select a preset overlay ID or use a custom one | Account, Search, Menu, Primary cart, Alternative cart, Quick buy, Quick edit, Custom (default) |
| Overlay ID | Custom identifier for the overlay (used to trigger it programmatically) | Text input. Visible when overlay preset is "Custom" |
| Show close button | Displays a close button in the sidebar | Checkbox (default: false) |
| Color scheme | Controls the background and text color combination | Body, Neutral, Accent 1 (default), Accent 2, Accent 3, Shade 1, Shade 2, Shade 3, Primary, Secondary, Tertiary, Blur, Transparent |
| Border color | Controls the border color | Subtle (default), Strong, None |
| Horizontal position | Position of the sidebar along the horizontal axis | Left, Right (default) |
| Visibility | Controls when the block is visible | All (default), Mobile only, Desktop only |

